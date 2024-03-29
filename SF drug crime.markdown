
Through the past 20 years drugs have been an ever present issue in the city of San Francisco. Analyzing the public record of police data we can uncover some of the trends in the different types of drugs involved. 

The police data we looked at is available online at <a href="https://data.sfgov.org/Public-Safety/Police-Department-Incident-Reports-Historical-2003/tmnf-yvry/about_data" target="_blank">data.sfgov.org</a>, it includes every crime incident from January 2003 till May 2018 in San Francisco. For each crime it includes information such as the time and date, the district, a description, etc. We filtered the dataset to only look at those incidents in which the category was drug/narcotic and then labelled by the drug involved e.g. possession of marijuana, sale of marijuana and transportation of marijuana all fall under the drug type "marijuana", and so on with all the types of drugs seen in San Francisco.

**Figure 1:** time-series Bokeh plot showing selected drug types and normalised crime count from 2003 to 2017:

<object type="text/html" data="{{ site.baseurl }}/TimeSeries.html" width="1200" height="400" style="border: none; padding: 0;"></object>

### Notable 
Citing: 
* **2011**: California decriminalizes marijuana possession (reduced the charge of possession of one ounce of cannabis or less, from a misdemeanor to an infraction, similar to a traffic violation a maximum of a $100 fine and no mandatory court appearance or criminal record) **(SB 1449)**. [CBS News](https://www.cbsnews.com/texas/news/california-governor-signs-marijuana-decriminalization-bill/)
* **2014**: California reclassifies certain drug possession offenses **(Proposition 47)**, In San Francisco, law enforcement has responded by scaling back efforts against drugs, de-emphasizing incarceration and effectively allowing public drug use. [The New York Times, 2024](https://www.nytimes.com/2024/01/31/upshot/san-francisco-drug-crisis.html)
* **2016**: The Adult Use of Marijuana Act, Legalization of certain amounts of marijuana as adults for personal use. [California Judicial Branch](https://www.courts.ca.gov/prop64.htm) 

**Figure 2:** Map scatter plot of the Drug Crimes.

We plotted the occurences of drug related crimes onto a map of San Francisco of April 2009, showing the selected drug types: 

<center><span style="font-size: 12px; font-weight: bold;"></span>Crimes related to drugs documented in April 2009</center>
<object type="text/html" data="{{ site.baseurl }}/scatterplot_layer.html" width="800" height="400" style="border: none; padding: 0;"></object>

### Notable 
* **Tenderloin**: Throughout the years the Tenderloin has kept it's reputation for being the drug, crime and poverty filled district. Streets filled with tents, heroin needles keep the police and in April 2009 the district is the epicenter of Base/Rock Cocaine use. [The New York Times, 2018](https://www.nytimes.com/2024/01/31/upshot/san-francisco-drug-crisis.html) [The San Francisco Standard, 2022](https://sfstandard.com/2022/10/20/how-serious-is-tenderloins-drug-problem-heres-what-city-data-says/)

* **Park**: District with relatively low numbers in drug abuse dominates other districts in marijuana and hallucinogenic related crimes mainly due to it's geographic location, suggesting that police must have different approach when fighting these crimes

* **Southern**: District with high rate of criminality across all categories, that being said district borders tenderloin and large amount of crimes are reported near district borders 
 
**Figure 3:** Normalised Drug Type count by Police District:

<object type="text/html" data="{{ site.baseurl }}/DistrictDrugs.html" width="1200" height="400" style="border: none; padding: 0;"></object>

### Notable 
* Meth, Rock, Heroin, Opium, methadone all show very similar patterns district abuse 
* Marijuana, hallucinogenics following an simliar pattern **NEED HELP** 


