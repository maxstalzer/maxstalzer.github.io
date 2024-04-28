<h2> Overview of Terror Attacks in Central Sahel Africa </h2>

## Intro
Initial work was to look for currently highly affected regions by terrorism using stats like global terrorism index[2] or our and map plots we understood that Central Sahel Africa  is currently one of the most terrorism affeted regions in the whole world. 
This region is interesting with Islamic extremism uprising in the last decade and major islamic terrorist powers taking advantage of the poor and remote regions of south-sahara, with boko haram, ISGS (Islamic State in Greater Sahara) had been or are activiely affiliated with Islamic state, as well as Jama’at Nusrat al-Islam wal-Muslimim(JNIM) affiliated with al-qaeida and with governements failing to provide security and power to defeat these groups, terror and fear has taken regions economy in time of uncertainty.

### What is the Sahel region of Africa?
The Central Sahel is a region in West Africa comprised of the countries Burkina Faso, Mali and Niger.Political violence is a major issue in each of these countries and they have all been subject to [1] 
Notably leaders of these countries are not even visiting the more remote northern regions of the countries due to lack of control and security there, the ongoing clashes between violent groups and citizens keep causing chaos. Motives for these groups vary, some have feudal territorial claims, fight for political power, gain and control over smuggling routes for human and drug trafficking over sahara. In 2017 UN passed a bill for global powers to intervene and help combat terrorism in the region.[3] France has greatly contributed with it's military powers, Sahel region has been largest Frances offshores active military operation. 

### Global Terrorism Database
It is understandable to argue that the GTD is currently the only database with comprehensive covereage of  global and domestic terrorism.

Terrorism definition by the UN that as a minimum terrorism is "Terrorism involves the intimidation or coercion of populations or governments through the threat or perpetration of violence, causing death, serious injury or the taking of hostages." [5]

It is important to seperate government oppression, war crimes, genocides, guerilla warfare from this set as although they can be far worse, these events do not fall into the category of the definition. 

### Plot 1 INDex, Terror data, world map?? Need an intro plot 

### Lack of coverage 
When looking at central Sahel region and important note is that some of attacks, especially attacks dating prior 2010 go unnoticed and do not get reported due to local issues, lack of media coverage and the threat that is posed on getting exposed when reporting events such as terrorist attacks. Media outlets in west africa are fewer and poorly funded with certain report bias e.g. of attacks with governmental or political motives in the region getting sponsorerd or tolerated by the local authorities. [4]

## Terror Groups
As modern world has set more focus in combating the Islamic extremists and global Jihad, reporting of attacks greatly imporoved with groups such as Boko Haram had revceived greater notice due to it's islamic attakcs on Nigerian government and dominantly Christian society as  [5]

### What are the major terror organisations involved?
Through looking at the GTD we found that the most prevalent terrorism organisations were:

1. Unknown
2. JNIM
3. ISGS
4. Boko Haram 
First observation is the significant growth of islamic groups. Some of them have pledged alliegance to Al Qaeda (JNIM) or ISIS (ISGS). These groups largeley focus on local targets, sometimes targeting also western interests. Unknown attacks that have no affiliation to any group was an important area of interest to scope potential patterns and understand the situation better. 


*Maybe the bar plot of count over the years with the different groups stacked.
*explain that the unknown means attacks which were not attributed to any group

<object type="text/html" data="{{ site.baseurl }}/GroupCountBar.html"  width="1200" height="900" style="border: none; padding: 0; width:100%; height:30vw"></object>

<html>
<head>
    <title>Bokeh Plot Selector</title>
    <script>
        function showPlot(plotId) {
            var plots = document.getElementsByClassName("bokeh-plot");
            for (var i = 0; i < plots.length; i++) {
                plots[i].style.display = "none";
            }
            var selectedPlot = document.getElementById(plotId);
            if (selectedPlot) {
                selectedPlot.style.display = "block";
            }
        }
    </script>
</head>
<body>
    Normalise graph for:

    <select id="plotSelector" onchange="showPlot(this.value)">
        <option value="plot1">Attack Types</option>
        <option value="plot2">Target Types</option>
        <option value="plot3">Weapon Types</option>
    </select>

    <object id="plot1" type="text/html" data="{{ site.baseurl }}/attackTypeNorm.html"  width="1200" height="900" style="border: none; padding: 0; width:100%; height:30vw"></object>

    <!-- <iframe id="plot1" src="attackTypeNorm.html" class="bokeh-plot" style="display: none; width: 800px; height: 600px;"></iframe> -->

    <iframe id="plot2" src="targetTypeNorm.html" class="bokeh-plot" style="display: none; width: 800px; height: 600px;"></iframe>
    <iframe id="plot3" src="weaponTypeNorm.html" class="bokeh-plot" style="display: none; width: 800px; height: 600px;"></iframe>
</body>
</html>


### Where are the different groups most prevalent?

<object type="text/html" data="{{ site.baseurl }}/MapPlot2.html"  width="1200" height="900" style="border: none; padding: 0; width:100%; height:30vw"></object>

*Maybe some kind of plot of groups by country?



### What are the differences in terms of attack/target/weapon types between the groups?
*insert some nice plots maybe bokeh here 

## Counter Terrorism
*What have been the major counter terrorism movements or governments involved?
Since Sahel lacks strong and stable politics and governance counter-terrorism operations have greatly struggled to initiate a strong counter-terrorism policy, corruption and lack of power in rural threaten stability. Extremist groups take advantage of this mismanagement and cause disruption in the government. Sahel also holds significant natural resource wealth, making it one of Africa's most affluent areas in terms of natural assets. Placing region in the centre of attention in a global scale. With Russia, France and USA beeing largest military conrtinbutors to the region. 
Local military police are very often involved in attacks and to this day from 2010-2020 there have been reportet xx causalties from military deaths. 
* G5 Joint Task Force 
In 2014 a group of 5 Sahel region countries comprised of five member countres: Burkina Faso, Mali, Niger, Chad and Mauritania. Created to provide the institutional and enforcement structure to provide security within. In support of local governmen as well as cooperate and exchange criminal and ectremism information globally.  [6]

* France 
There are several groups involved in combating the regime with each having their own underlying reasons and motives, french government has had an on and off military pressence in sahel since 19th century as of today France wants to publilcly show their alligiency to democratic uprising in the region as well as defend their assets such as oil fields owned by total and uranium mines.
    Frances involvment is not particularly taken well by the local authorities and recent regime changes has had a significantly impacted public opinion of french government 
* USA 
Data up till 2020 shows that United States had contributed 6 billion Usd in military aid in the region. Although us physical military footprint has remained small. It's pressence with training programms and other assistance have been noticable. They have also developed TSCTP (The Trans-Sahara Counterterrorism Partnership) as a multi year partnership to combat terrorism and strenghten security of the region. 

## Conclusion

### What can we conclude??????????????????



## Reference List
[1] <a href="https://acleddata.com/conflict-watchlist-2024/sahel/" target="_blank">acleddata.com</a>
[2] <a href="https://www.visionofhumanity.org/maps/global-terrorism-index/#/" target="_blank">acleddata.com</a>
[3] <a href="https://www.nytimes.com/2017/06/21/world/africa/security-council-sahel-france-united-states.html?searchResultPosition=33" target="_blank">acleddata.com</a>
[4] <a href="https://journals.sagepub.com/doi/abs/10.1177/0975087813512070?casa_token=uC2_FQvgR64AAAAA%3AEGSftNC8XdQ5oiqxzdzqYh5r8JTnZ0hfnRNji74Zexeu1jLnnMQBLqxv-L6Go3K1CoXIAw6IsvsxXg&journalCode=ioaa" target="_blank">acleddata.com</a>
[5] <a href="https://www.ohchr.org/en/terrorism" target="_blank">acleddata.com</a>
[6] <a href="https://www.interpol.int/es/Delitos/Terrorismo/Proyectos-de-lucha-contra-el-terrorismo/G5-Sahel" target="_blank">acleddata.com</a>
[7] <a href="https://crsreports.congress.gov/product/pdf/TE/TE10044" target="_blank">acleddata.com</a>
