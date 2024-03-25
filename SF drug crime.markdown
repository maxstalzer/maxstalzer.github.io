
Through the past 20 years drugs have been an ever present issue in the city of San Francisco. Analyzing the public record of police data from the years 2003-2018 we can uncover some of the trends in the different types of drugs involved. 

The police data we looked at is available online at <a href="https://data.sfgov.org/Public-Safety/Police-Department-Incident-Reports-Historical-2003/tmnf-yvry/about_data" target="_blank"> data.sfgov.org </a>, it includes every crime incident from January 2003 till May 2018. For each crime it includes information such as the time, type, district and coordinates.

Selecting DRUG/NARCOTIC category and sorting them by involved drugs, e.g. 'POSSESSION OF MARIJUANA', 'SALE OF MARIJUANA', 'POSSESSION OF MARIJUANA FOR SALES', 'TRANSPORTATION OF MARIJUANA','FURNISHING MARIJUANA' categories will all appear under a name **Marijuana** in our plots. 

We created a time-series Bokeh plot showing our selected drug types and normalised crime count from 2003 to 2017:

<object type="text/html" data="{{ site.baseurl }}/TimeSeries.html" width="1200" height="400" style="border: none; padding: 0;"></object>

### Notable 
Citing: 
* **2011**: California decriminalizes marijuana possession (reduced the charge of possession of one ounce of cannabis or less, from a misdemeanor to an infraction, similar to a traffic violation"”a maximum of a $100 fine and no mandatory court appearance or criminal record) **(SB 1449)** 
* **2014**: California reclassifies certain drug possession offenses **(Proposition 47)**, In San Francisco, law enforcement has responded by scaling back efforts against drugs, de-emphasizing incarceration and effectively allowing public drug use. [The New York Times, 2024](https://www.nytimes.com/2024/01/31/upshot/san-francisco-drug-crisis.html)
* **2016**: the Adult Use of Marijuana Act, Legalization of certain amounts of marijuana as adults for personal use 

## Map: Focus drugs 

We plotted the occurences of drug related crimes onto a map of San Francisco of April 2009, showing the selected drug types: 

<center><span style="font-size: 12px; font-weight: bold;"></span>Crimes related to drugs documented in April 2009</center>
<object type="text/html" data="{{ site.baseurl }}/scatterplot_layer.html" width="800" height="400" style="border: none; padding: 0;"></object>

### Notable 
* **Tenderloin**: For years the Tenderloin has kept it's reputation for beeing the drug, crime and poverty filled district. Streets filled with tents, heroin needles keep the police and april 2009 district is the epicenter of Rock/Cocaine abuse [The NYT, 2018](https://www.nytimes.com/2024/01/31/upshot/san-francisco-drug-crisis.html) [The San Francisco Standard, 2022](https://sfstandard.com/2022/10/20/how-serious-is-tenderloins-drug-problem-heres-what-city-data-says/)

* **Park**: District with relatively low numbers in drug abuse dominates other districts in marijuana and hallucigenic related crimes mainly due to it's geographic location, suggesting that police must have different approach when fighting these crimes 

* **Southern**  district with high rate of criminality across all categories, that beeing said district borders tenderloin and large amount of crimes are reported near district borders 
 


<object type="text/html" data="{{ site.baseurl }}/DistrictDrugs.html" width="1200" height="400" style="border: none; padding: 0;"></object>

### Notable 
* Meth, Rock, Heroin, Opium, methadone all show very similar patterns district abuse 
* Marijuana, hallucinogenics following an simliar pattern **NEED HELP** 
* **HELP** BIG mAXER come make some lines ||||| (˚ㄥ_˚)

