---
layout: default
title: Decreasing drug-related crime in San Francisco and its Resurgence
---

## Decreasing drug-related crime in San Francisco and its Resurgence

San Francisco has in recent years seen a spike in crime related to drugs and narcotics after the covid 19 pandemic. Many factors can contribute to increased crime such as mental ilness, homelessness and economic downturn causing low prospective outlook on the future are a couple of reasons why people are drawn to drugs to escape their daily struggles and get a brief respite from everything around them. The crimerate related drugs had been steadly been decreasing since the financial crisis that hit the US in 2007-2009 along with changing laws around cannibis with proposition 64 in 2016 reducing the crime from a felony to a misdemeanor leading to less reported crime involving this popular drug [1]. 
## Trends in Drug-Related Crime from 2003 to early 2025

Looking at the drug and narcotics incidents over the years from 2003 to 2025 below we see that there has been a steady decreasing trend ending at the after the pandemic with an resurgence of crime but what are the causes behind this? Let us start by looking back. 
<div class="interactive-viz">
    <!-- <h3>Interactive Exploration of Drug Crimes by District</h3> -->
    <p>Use the dropdown menu to highlight specific districts and hover over data points for detailed information.</p>
    <iframe src="{{ site.baseurl }}/assets/interactive/drug_crimes_trend.html" width="100%" height="600px" frameborder="0"></iframe>
</div>

**Figure 1**: *Trend of drug/narcotics related crime from each district. The plot is interactive so each police district can be viewed independently, and the average trend across all the district is toggable.*

The effects of the financial crisis in 2007-2008 caused a significant increase in homelessness and drug usage in San Francisco due to the economic turmoil the effect of this is clearly visible in the graph. Afterwards a decreasing trend occured which got interrupted by the covid pandemic where the good folk in San Francisco were forced to work from home due to the "Stay Home order" on March 17th 2020 and did not fully cease until the 15th of june 2021. [2]\ 
So how did drug and narcotic crime increase if everyone was at home where policing would be difficult?\
An answer might lie in the feeling of hopelessness and isolation felt during the period with decreased contact with friends and family and an overall uncertain future driving people to escape from their troubles. Leading people to seek out drugs when venturing out when they got their groceries or necessary travels. Below is an interactive heatmap that shows the time period and location of reported drug crimes. 

<div class="interactive-viz">
    <iframe src="{{ site.baseurl }}/assets/interactive/drug_crime_heatmap.html" width="100%" height="600px" frameborder="0"></iframe>
</div>

**Figure 2**: *Interactive heatmap of San Francisco during the Covid 19 Stay Home Order from March 17th 2020 to June 15th 2021*

The tenderloin district has long been the biggest problem area in the bay area with homelessness and drug-selling contributing to its reputation. During covid a drug overdose epidemic had gotten out of control in San Francisco. Due to increasing numbers of overdoses the city declared emergency to combat the problem with crackdowns starting december 2021 [3][4]. The result of crackdown is visible in the figure below from 2021 and onwards with increasing crimerate. \
Due to the crackdown there would envietable be a rise in the crimerate due to more incidents getting reported leading to spikes in crimes reported.

<img src="{{ site.baseurl }}/assets/graphs/occurances_pandemic.png" 
     alt="Drug related crimerate during covid pandemic and onwards" 
     width="880px" 
     class="responsive-image">

**Figure 3**: *Crimerate in San Francisco for occurances from 2020 to 2024 for each month*

Drugs has always been a problem in the US and will most likely continue being a problem for the foreseeble future, but if the trend continues we could hopefully reduce the problem until everyone can get the help they need. 


## Data
San Francisco was chosen for its openness in sharing crime data, allowing researchers and data scientists to explore patterns that could benefit society. 
The dataset spans from 2003 to Q1 2025 and contains 1,702,398 datapoints. \
It includes the following crime categories: ROBBERY, VEHICLE THEFT, ASSAULT, BURGLARY, LARCENY/THEFT, DRUG/NARCOTIC, VANDALISM, WEAPON LAWS, PROSTITUTION, and STOLEN PROPERTY.\
And the following attributes: Category,	PdDistrict,	Longitude,	Latitude,	TimeOfDay,	DayOfWeek,	DayOfMonth,	Month	Year.

## Sources
[1] https://sfpublicdefender.org/services/prop-64-faq/\
[2] https://www.pbs.org/newshour/nation/california-fully-reopens-after-being-1st-to-shut-in-pandemic  
[3] https://sfmayor.org/article/mayor-london-breed-declares-state-emergency-tenderloin\
[4] https://www.sf.gov/data--reducing-violent-crime-and-drug-sales-tenderloin\
[5] https://www.sfchronicle.com/projects/san-francisco-drug-overdose-deaths/

