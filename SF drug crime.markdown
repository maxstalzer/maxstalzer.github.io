
Intro """" Intro 

Through the past 20 years drugs have been an ever present issue in the city of San Francisco. Analyzing the public record of police data from the years 2003-2018 we can uncover some of the trends in the different types of drugs involved. 

The police data we looked at is available online at <a href="https://data.sfgov.org/Public-Safety/Police-Department-Incident-Reports-Historical-2003/tmnf-yvry/about_data" target="_blank"> data.sfgov.org </a>, it includes every crime incident from January 2003 till May 2018. For each crime it includes information such as the time, type, district and coordinates.

Selecting DRUG/NARCOTIC category and sorting them by involved drugs, e.g. 'POSSESSION OF MARIJUANA', 'SALE OF MARIJUANA', 'POSSESSION OF MARIJUANA FOR SALES', 'TRANSPORTATION OF MARIJUANA','FURNISHING MARIJUANA' categories will all appear under a name **Marijuana** in our plots. 

We created a time-series Bokeh plot showing our selected drug types and normalised crime count from 2003 to 2017:

<object type="text/html" data="{{ site.baseurl }}/TimeSeries.html" width="1200" height="400" style="border: none; padding: 0;"></object>

### Notable 
Citing: 
* 2011: California decriminalizes marijuana possession (reduced the charge of possession of one ounce of cannabis or less, from a misdemeanor to an infraction, similar to a traffic violation"”a maximum of a $100 fine and no mandatory court appearance or criminal record) **(SB 1449)** 
* 2014: California reclassifies certain drug possession offenses (Proposition 47), In San Francisco, law enforcement has responded by scaling back efforts against drugs, de-emphasizing incarceration and effectively allowing public drug use. [The New York Times, 2024](https://www.nytimes.com/2024/01/31/upshot/san-francisco-drug-crisis.html)
* 2016: the Adult Use of Marijuana Act, Legalization of certain amounts of marijuana as adults for personal use 

### Map: Focus drugs 

We plotted the occurences of drug related crimes onto a map of San Francisco, coloring by the type of drug involved:

<object type="text/html" data="{{ site.baseurl }}/MapPlot.html" width="800" height="400" style="border: none; padding: 0;"></object>


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Map with Month Picker</title>
    <!-- Import Pydeck and DeckGL CSS -->
    <link rel="stylesheet" type="text/css" href="https://unpkg.com/pydeck@0.7.0/dist/pydeck.css" />
    <style>
        /* Add custom CSS styles here */
        #map {
            position: relative;
            width: 100%;
            height: 600px; /* Adjust height as needed */
        }
        #month-picker {
            position: absolute;
            top: 10px;
            right: 10px;
            z-index: 9999;
        }
    </style>
</head>
<body>
    <div id="map"></div>
    <div id="month-picker">
        <label for="month">Select Month:</label>
        <input type="month" id="month" name="month">
        <button onclick="filterByMonth()">Apply</button>
    </div>

    <!-- Import Pydeck and DeckGL JavaScript -->
    <script type="module">
        import {Deck} from 'https://unpkg.com/pydeck@0.7.0';
        import {ScatterplotLayer} from '@deck.gl/layers';

        const data = ${json_data}; // Replace with your JSON data

        // Function to filter data by selected month
        function filterByMonth() {
            const selectedMonth = document.getElementById('month').value;
            const filteredData = data.filter(item => {
                return item.Date.startsWith(selectedMonth);
            });

            renderMap(filteredData);
        }

        // Function to render the map with filtered data
        function renderMap(filteredData) {
            const layer = new ScatterplotLayer({
                id: 'scatterplot-layer',
                data: filteredData,
                pickable: true,
                opacity: 0.3,
                stroked: false,
                filled: true,
                radiusScale: 3,
                radiusMinPixels: 8,
                radiusMaxPixels: 20,
                lineWidthMinPixels: 1,
                getPosition: d => [d.X, d.Y],
                getFillColor: d => d.color,
                getLineColor: [0, 0, 0],
                radiusUnit: 'pixels'
            });

            const viewState = {
                latitude: 37.7749295,
                longitude: -122.4194155,
                zoom: 11,
                bearing: 0,
                pitch: 0
            };

            const deck = new Deck({
                layers: [layer],
                initialViewState: viewState,
                container: 'map',
                getTooltip: ({object}) => ({
                    html: `<div>${object.Descript}</div><div>${object.Date}</div>`,
                    style: {
                        backgroundColor: 'rgba(0, 0, 0, 0.7)',
                        color: 'white',
                        fontFamily: 'Helvetica, sans-serif'
                    }
                })
            });
        }

        // Initial rendering of the map
        renderMap(data);
    </script>
</body>
</html>
