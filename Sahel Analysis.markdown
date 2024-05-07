<h2> Overview of Terror Attacks in Central Sahel Africa </h2>

## Introduction
Initial work was to look for currently highly affected regions by terrorism using statistics from the global terrorism index [1] or our own exploratory map plots, we understood that the Central Sahel region is currently one of the most terrorism affected areas in the world.
This region is interesting with Islamic extremism uprising in the last decade and major islamic terrorist powers taking advantage of the poor and remote regions of south-sahara, with boko haram, ISGS (Islamic State in Greater Sahara) had been or are activiely affiliated with Islamic state, as well as Jama’at Nusrat al-Islam wal-Muslimim (JNIM) affiliated with al-Qa'ida and with governements failing to provide security and power to defeat these groups, terror and fear has taken regions economy in time of uncertainty.

### What is the Sahel region of Africa?
The Central Sahel is a region in West Africa comprised of the countries Burkina Faso, Mali and Niger. Political violence is a major issue in each of these countries and they have all been subject to Jihadist insurgency. [2] 
Notably leaders of these countries are not even visiting the more remote northern regions of each of the countries due to the lack of control and security there, the ongoing clashes between violent groups and citizens causing chaos. Motives for these groups vary, some have feudal territorial claims, fight for political power, gain and control over smuggling routes for human and drug trafficking over Sahara. In 2017 the United Nations passed a bill for global powers to intervene and help combat terrorism in the region. [3] France has greatly contributed with it's military powers, with the Sahel being its largest offshore active military operation. 

### Global Terrorism Database
It is understandable to argue that the GTD is currently the only database with comprehensive covereage of  global and domestic terrorism. Data base draws most of its information from the media reports putting focus on not only interantional but also domestic incidents happening around the globe.

The United Nations states that as a minimum terrorism is defined as "Terrorism involves the intimidation or coercion of populations or governments through the threat or perpetration of violence, causing death, serious injury or the taking of hostages." [4]

It is important to separate government oppression, war crimes, genocides, guerilla warfare from this set as although they can be far worse, these events do not fall into the category of the definition. 

Plotting terrorism incidents by country for sub-saharan Africa:
<object type="text/html" data="{{ site.baseurl }}/choroplethMap.html"  width="1200" height="900" style="border: none; padding: 0; width:100%; height:30vw"></object>

### Lack of coverage 
When looking at central Sahel region and important note is that some of attacks, especially attacks dating prior to 2010 go unnoticed and do not get reported due to local issues, lack of media coverage and the threat that is posed on getting exposed when reporting events such as terrorist attacks. Media outlets in West Africa are fewer and poorly funded with certain report bias e.g. of attacks with governmental or political motives in the region getting sponsorerd or tolerated by the local authorities. [4]
<object type="text/html" data="{{ site.baseurl }}/AttackCountYR.html"  width="1200" height="900" style="border: none; padding: 0; width:100%; height:30vw"></object>


## Terror Groups

Through looking at the GTD we found that the most prevalent terrorism organisations were:

<object type="text/html" data="{{ site.baseurl }}/GroupCountBar.html"  width="1200" height="900" style="border: none; padding: 0; width:100%; height:30vw"></object>

1. **Unknown:** The largest group shown on the plot is, by far, the incidents where the affiliated group is unknown. This means while recording the incident it was unclear which group was behind the attack and none claimed responsibility.
2. **JNIM:** Jama'at Nasr al-Islam wal Muslimin, formed in March of 2017 when the four groups Ansar al-Din, al-Murabitun, the Macina Liberation Front (MLF), and the Sahara Emirate subgroup of al-Qa'ida in the Lands of the Islamic Maghreb (AQIM) merged together. The leader has pledged allegiance to the emirs of AQIM, al-Qa'ida and the Taliban. This group is based in Mali but has attacked all across the Sahel region. [6]
3. **Muslim Extremists:** An umbrella term where the incident was likely committed by one of the other islamic groups mentioned here.
4. **Boko Haram:** Refer to themselves as Jama'atu Ahl as-Sunnah li-Da'awati wal-Jihad (translates to "People Committed to the Prophet's Teachings for Propagation and Jihad") was founded in 2002 in Nigeria. In July 2010 the previous second-in-command took control, threatened western influence in Nigeria and pledged allegiance to al-Qa'ida. Capability and activities increased greatly in 2014. [7]
5. **Other:** The groups which were not in the top 14 most active were labelled "Other". Together these make up the fifth largest group. The three largest organisation in it were Fulani extremists, Al-Mua'qi'oon Biddam Brigade (Those who Sign with Blood) and the Movement of Niger People for Justice (MNJ) with 11, 10 and 9 attacks respectively.
6. **ISGS:** The Islamic State in the Greater Sahara, formed from a division from the Movement for Oneness and Jihad in West Africa (MUJAO) group. Leader pledged allegiance to ISIS in May of 2015 but this was recognised only in October of 2016. Started out more active in western Niger and the Menaka region in Mali, but has since also been attacking in northern Burkina Faso. [8]
7. **AQIM:** Al-Qa'ida in the Lands of the Islamic Maghreb mainly based in Algeria was originally founded in 1998 as the Salafist Group for Preaching and Combat (GSPC) but was renamed after joining al-Qa'ida in September of 2006. In 2012 the group, working with local Tuareg national elements, took control of some cities in northern Mali. They were fought back by the French military intervention in 2013 and lost the territory as well as some important members. They have been regrouping since 2015 and have had several attacks on United Nations forces present in the region. [9]
8. **Ansar al-Dine (Mali):** Formed from the aforementioned AQIM group in November of 2011 to establish an Islamic State in Mali. After the 2012 coup of Mali the group seized control over territory in the north, they were then fought back by the French intervention but re-emerged in 2016 and merged with three other groups to form JNIM in 2017. [10]
9. **MUJAO:** Movement for Oneness and Jihad in West Africa, split from AQIM in October 2011. More focused on the Sahel region than AQIM. Split in 2015 and part of the members later join either ISGS or JNIM.

*Maybe the bar plot of count over the years with the different groups stacked.

### Where are the different groups most prevalent?
We plotted all terrorism incidents from 1970 until 2020 for Mali, Burkina Faso and Niger. Each point is sized by the number of deaths and colored by the select option. Hovering over a point shows more details on that attack. Clicking once on an entry in the legend will hide/unhide it from the map, while double clicking will isolate only this group.

<html>
<head>
    <title>Map Plot Selector</title>
    <style>
        /* Style for dropdown select */
        .select-wrapper {
            position: relative;
            display: inline-block;
        }
        .select-wrapper select {
            appearance: none;
            -webkit-appearance: none;
            -moz-appearance: none;
            background-color: #f5f5f5;
            border: 1px solid #ddd;
            padding: 10px 40px 10px 20px;
            font-size: 16px;
            font-family: Arial, sans-serif;
            cursor: pointer;
            width: 200px;
            border-radius: 5px;
        }
        .select-wrapper select:focus {
            outline: none;
        }
        .select-wrapper::after {
            content: '\25BC';
            position: absolute;
            top: 50%;
            right: 15px;
            transform: translateY(-50%);
            pointer-events: none;
        }
        /* Style for options */
        .select-wrapper select option {
            background-color: #fff;
            color: #333;
        }
    </style>
    <script>
        function showMap(plotId) {
            var plots = document.getElementsByClassName("map-plot");
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
    Show map colored by:

    <select id="mapSelector" onchange="showMap(this.value)">
        
        <option value="map1">Groups</option>
        <option value="map2">Attack Types</option>
        <option value="map3">Target Types</option>
        <option value="map4">Weapon Types</option>
        <option value="map5">Years</option>
        
    </select>

    <object id="map1" type="text/html" data="{{ site.baseurl }}/MapPlotGroups.html" class="map-plot" width="1200" height="900" style="display: block; border: none; padding: 0; width:100%; height:30vw"></object>

    <object id="map2" type="text/html" data="{{ site.baseurl }}/MapPlotAttacks.html" class="map-plot" width="1200" height="900" style="display: none; border: none; padding: 0; width:100%; height:30vw"></object>

    <object id="map3" type="text/html" data="{{ site.baseurl }}/MapPlotTargets.html" class="map-plot" width="1200" height="900" style="display: none; border: none; padding: 0; width:100%; height:30vw"></object>

    <object id="map4" type="text/html" data="{{ site.baseurl }}/MapPlotWeapons.html" class="map-plot" width="1200" height="900" style="display: none; border: none; padding: 0; width:100%; height:30vw"></object>

    <object id="map5" type="text/html" data="{{ site.baseurl }}/MapPlotYears.html" class="map-plot" width="1200" height="900" style="display: none; border: none; padding: 0; width:100%; height:30vw"></object>

</body>
</html>

We notice how the majority of attacks are roughly concentrated to the bordering region that is northern Burkina Faso and southern Mali as well as some in western Niger. 

The "Unknown" and "Muslim Extremist" attacks are especially concentrated to this bordering area. We see for JNIM how some attacks follow along settlements by the Niger river in Mali, such as through the cities of Timbuktu and Gao. All but three of Boko Haram's attacks were in Niger, and the majority are very concentrated to the eastern border with Nigeria around Lake Chad as well as some more towards the border with Burkina Faso in the west. ISGS attacks are found almost exclusively along the southern border of Mali. We also see that most of the attacks with larger number of deaths were not perpetrated by the unknown group. For the attack types see that many of the incidents with many deaths (larger circles on the map) were armed assaults. Similarly, the military target type seems to show many deaths.

### What are the differences in terms of attack/target/weapon types between the groups?

For each group we found what share of their incidents are in the different categories of attack, target and weapon types. Below select graph for the different types and hover on the bars to see what share that category constitutes.

<html>
<head>
    <title>Bokeh Plot Selector</title>
    <style>
        /* Style for dropdown select */
        .select-wrapper {
            position: relative;
            display: inline-block;
        }
        .select-wrapper select {
            appearance: none;
            -webkit-appearance: none;
            -moz-appearance: none;
            background-color: #f5f5f5;
            border: 1px solid #ddd;
            padding: 10px 40px 10px 20px;
            font-size: 16px;
            font-family: Arial, sans-serif;
            cursor: pointer;
            width: 200px;
            border-radius: 5px;
        }
        .select-wrapper select:focus {
            outline: none;
        }
        .select-wrapper::after {
            content: '\25BC';
            position: absolute;
            top: 50%;
            right: 15px;
            transform: translateY(-50%);
            pointer-events: none;
        }
        /* Style for options */
        .select-wrapper select option {
            background-color: #fff;
            color: #333;
        }
    </style>
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
        <option value="bokeh1">Attack Types</option>
        <option value="bokeh2">Target Types</option>
        <option value="bokeh3">Weapon Types</option>
    </select>


    <object id="bokeh1" type="text/html" data="{{ site.baseurl }}/attackTypeNorm.html" class="bokeh-plot" width="1200" height="400" style="display: block; border: none; padding: 0; width:120%; height:50vw"></object>
    <object id="bokeh2" type="text/html" data="{{ site.baseurl }}/targetTypeNorm.html" class="bokeh-plot" width="1200" height="400" style="display: none; border: none; padding: 0; width:110%; height:50vw"></object>
    <object id="bokeh3" type="text/html" data="{{ site.baseurl }}/weaponTypeNorm.html" class="bokeh-plot" width="1200" height="400" style="display: none; border: none; padding: 0; width:110%; height:50vw"></object>

</body>
</html>

* **Normalised by attack types:** We see the most common attack type for the six largest groups was armed assault, for the next three largest (AQIM, Ansar al-Dine (Mali) and MUJAO) it is bombings and for the remaining again armed assault. The group which had largest share of armed assault were the Tuareg Guerillas with 88% of their attacks being in this category. 

* **Normalised by target types:** Over half of JNIM attacks were on Military which is significantly more than the other groups. Boko Haram on the contrary has over half of its attacks on Private Citizens & Property, while Ansar al-Dine (Mali) least frequently targeted this category. Notable also is Ansar al-Islam (Burkina Faso) targetting Police significantly more than any group.

* **Normalised by weapon types:** The muslim extremist group showed a larger share of their attacks being perpetrated using Firearms compared to the other top groups. Again by the trend seen in the attack types plot AQIM, Ansar al-Dine (Mali) and MUJAO used a larger share of explosives in their attacks. The Tuareg Guerillas and CMA used almost exclusively Firearms in their attacks.

## Counter Terrorism
*What have been the major counter terrorism movements or governments involved?
Since Sahel lacks strong and stable politics and governance counter-terrorism operations have greatly struggled to initiate a strong counter-terrorism policy, corruption and lack of power in rural threaten stability. Extremist groups take advantage of this mismanagement and cause disruption in the government. Sahel also holds significant natural resource wealth, making it one of Africa's most affluent areas in terms of natural assets. Placing region in the centre of attention in a global scale. With Russia, France and USA being largest military conrtinbutors to the region. 
Local military police are very often involved in attacks and to this day from 2010-2020 there have been 2791  reported causalties from military deaths and 315 police deaths in the region. 

* **G5 Joint Task Force** <br />
In 2014 a group of 5 Sahel region countries comprised of five member countres: Burkina Faso, Mali, Niger, Chad and Mauritania. Created to provide the institutional and enforcement structure to provide security within. In support of local government as well as cooperate and exchange criminal and extremism information globally. [11]

* **France** <br />
There are several groups involved in combating the regime with each having their own underlying reasons and motives, french government has had an on and off military presence in sahel since 19th century, as of today France wants to publicly show their alligiance to democratic uprising in the region as well as defend their assets such as oil fields owned by total and uranium mines.
French involvment is not particularly taken well by the local authorities and recent regime changes have significantly impacted public opinion of french government 

* **USA** <br />
Data up till 2020 shows that the United States had contributed 6 billion USD in military aid in the region. Although US physical military footprint has remained small. It's presence with training programs and other assistance have been noticeable. They have also developed TSCTP (The Trans-Sahara Counterterrorism Partnership) as a multi year partnership to combat terrorism and strenghten security of the region. [12]



## Reference List
[1] <a href="https://www.visionofhumanity.org/maps/global-terrorism-index/#/" target="_blank">visionofhumanity.org, Global Terrorism Index</a> <br />
[2] <a href="https://acleddata.com/conflict-watchlist-2024/sahel/" target="_blank">acleddata.com, Sahel Background</a> <br />
[3] <a href="https://www.nytimes.com/2017/06/21/world/africa/security-council-sahel-france-united-states.html?searchResultPosition=33" target="_blank">nytimes.com, United Nations in Africa</a> <br />
[4] <a href="https://www.ohchr.org/" target="_blank">ohchr.org, Terrorism Definition</a> <br />
[5] <a href="https://journals.sagepub.com/doi/abs/10.1177/0975087813512070?casa_token=uC2_FQvgR64AAAAA%3AEGSftNC8XdQ5oiqxzdzqYh5r8JTnZ0hfnRNji74Zexeu1jLnnMQBLqxv-L6Go3K1CoXIAw6IsvsxXg&journalCode=ioaa" target="_blank">Sage Journals, Missing Terrorism Data</a> <br />
[6] <a href="https://www.dni.gov/nctc/ftos/jnim_fto.html" target="_blank">dni.gov, JNIM info</a> <br />
[7] <a href="https://www.dni.gov/nctc/groups/boko_haram.html" target="_blank">dni.gov, Boko Haram info</a> <br />
[8] <a href="https://ecfr.eu/special/sahel_mapping/isgs" target="_blank">ecfr.eu, ISGS info</a> <br />
[9] <a href="https://www.dni.gov/nctc/groups/aqim.html" target="_blank">dni.gov, AQIM info</a> <br />
[10] <a href="https://www.dni.gov/nctc/ftos/ansar_al_dine_fto.html" target="_blank">dni.gov, Ansar al-Dine info</a> <br />
[11] <a href="https://www.interpol.int/es/Delitos/Terrorismo/Proyectos-de-lucha-contra-el-terrorismo/G5-Sahel" target="_blank">Interpol.int, G5 Sahel</a> <br />
[12] <a href="https://crsreports.congress.gov/product/pdf/TE/TE10044" target="_blank">CRS Reports, US Counterterrorism in Africa</a> <br />