
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


## Normalised Drug Category Count for each Police District

<object type="text/html" data="{{ site.baseurl }}/DistrictDrugs.html" width="1200" height="400" style="border: none; padding: 0;"></object>