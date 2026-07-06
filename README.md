# Average Make of a Rebel Leader

### Heres a link to my	[google sheet!](https://docs.google.com/spreadsheets/d/1YGbQfI2XaU03NBBCq2bmLsZSuejqWQg3q6UtoDvWIJo/edit?usp=sharing)

Over the past few days, I've been reading *Human Acts* by Han Kang during my BART commute. The novel's portrayal of rebellion and its violence despite good intention has given me a deeper appreciation for the human stories behind this dataset. While this information is not relevant to the project, I wanted to mention the relation between this analysis and my present life just as a fun fact. 

## Where did this information come from?

This dataset was brought together by the Rebel Leaders Project, a research group that documents armed rebel organizations involved in civil wars. These researchers collect information from many primary and secondary sources, including publications, government documents, the news, human rights organizations, and existing databases.

This source is trustworthy because it was created by academic researchers for research purposes. There is no underlying motive, considering who the creators are. Benjamin Acosta is a chief data officer at Arcturus Intelligence and political scientist specializing in political violence, armed resistance, identity politics, and data analysis; he combines datasets with network analysis. Reyko Huang is an associate professor at Texas A&M University whose research focuses on civil wars, rebel organizations, international security, and democratizations; she studies how rebel groups govern. And Daniel Silverman is an assistant professor at Carnegie Mellon University who researches violent conflict, particularly in the Middle East. These people are educated in this topic. The limitations of using this dataset are instead related to how information on rebel groups are often incomplete. Many times I found myself with empty spaces in charts because there were gaps of data. You might see a handful of “No Data” in the following graphs. It’s not surprising that the information is limited. Some rebel groups move secretly, leadership changes may be unreported, and reports from governments may be biased. 

Furthermore, how many rebel groups are missing from the list entirely. This means smaller, short-lived, or poorly documented groups may be underrepresented. Additionally, the way the project defines terms such as "rebel group" or "leader" influences which organizations are included and how they are categorized.

Overall, the dataset is a credible academic resource, but it should still be fact-checked and compared with other databases.

## Analysis
### Averages of a Rebel Leader's Age Compared with their Highest Level of Education
Here, I made a pivot table comparing the column that describes the age when a rebel first became a leader for their group and their level of education. My curiosity came with the question: How does education impact the age a person rebels? Though the differences aren’t drastic, it shows that people with less education become leaders a few years earlier than those who seek higher education. Though, despite the many years it takes to obtain a doctorate, the difference of years isn’t proportional. Because the number of leaders were as little as ten in some education categories, in my google sheets I also compared the education level to the MEDIUM of the rebels’ ages when they started. It provided the same chart as the following.

![Age of Rebels and their Education](https://docs.google.com/spreadsheets/d/e/2PACX-1vThUpIfhd_-rAOV3hq50J0M4k0uF-Y1Q5rQ9P9EuKSuBjPrftGC8VP0aXK2Uxu6-RT15RBlHOcJFTad/pubchart?oid=1069735015&format=image)


### Education Level Dristribution 
With a pivot chart, I counted the number of rebel leaders and their highest level of education. The chart shows that a bachelor’s degree is the most common, though there is a significant lack of data to say so definitively.

![Education Level Distribution](https://docs.google.com/spreadsheets/d/e/2PACX-1vThUpIfhd_-rAOV3hq50J0M4k0uF-Y1Q5rQ9P9EuKSuBjPrftGC8VP0aXK2Uxu6-RT15RBlHOcJFTad/pubchart?oid=1556631235&format=image)


### Highest Level of Education and Family Status
Here, I made a pivot table looking at if the leader came from an elite family or not, and then compared that to their highest level of education. The information shows that a bachalor's degree is the most common level of education among the rebel leaders. Leaders from elite families have higher populations to attend college level education. However, when it comes to a master's or doctorate level, the discrepency between family class upbringing is low. What's most surprising is the drastic number of non-elite rebels with an unknown education background. 
![Comparing Education to Family Status](https://docs.google.com/spreadsheets/d/e/2PACX-1vThUpIfhd_-rAOV3hq50J0M4k0uF-Y1Q5rQ9P9EuKSuBjPrftGC8VP0aXK2Uxu6-RT15RBlHOcJFTad/pubchart?oid=1607510344&format=image)


### Here is an interactive geographic chart of countries and its distribution of rebel leaders I made with DataWrapper [Geographic Distribution of Civil War Rebels!](https://www.datawrapper.de/_/j6VxJ/)
To make this map, I first made a pivot table comparing each of the countries with the number of leaders. Then I removed the “total” rows. Last I added the data to DataWrapper to customize this map. 

### Top 12 Countries with the Most Rebels
This chart comes from the same pivot table as the previous map. The biggest thing these countries have in common is a history of prolonged internal conflict combined with weak or contested state control. They are not all poor, authoritarian, or geographically similar, but most share conditions that make rebel movements more likely to emerge and persist. The difference between this chart and the previous map is I added gender and sorted the data by the count of rebel leaders per country. Something incredibly interesting to me is how there is only one female leader: Alice Auma. Shockingly to me, she is the only female rebel leader of the whole dataset, not just the top twelve. Many of the countries with prolonged civil wars also have deeply patriarchal social structures and histories of gender inequality, where women are often excluded from positions of political and military power. While this does not explain every case, it may help explain why female rebel leaders are so exceptionally rare in this dataset. Though rare, I still can’t believe Auma is the only one.

![Top 12 Countries with Most Rebels](https://docs.google.com/spreadsheets/d/e/2PACX-1vThUpIfhd_-rAOV3hq50J0M4k0uF-Y1Q5rQ9P9EuKSuBjPrftGC8VP0aXK2Uxu6-RT15RBlHOcJFTad/pubchart?oid=814854345&format=image)

### Niche Rebel Leaders' Educations Point of Interests
The following three charts look at the specifics of the rebel leaders’ educations. For all three, I used a pivot table. 


If a leader obtained a degree (bachelor’s, master’s, doctorate, or equivalent) from a university in the US, UK, Austria, Belgium, Canada, Denmark, Finland, France, Germany, Greece, Ireland, Italy, the Netherlands, Norway, Portugal, Spain, Sweden, or Switzerland, then they are considered to have a Western Education by this dataset. There is not a significant amount of leaders with a Western Education to determine that western education causes uprisings. 

![Distribution of Rebels with Western Education](https://docs.google.com/spreadsheets/d/e/2PACX-1vThUpIfhd_-rAOV3hq50J0M4k0uF-Y1Q5rQ9P9EuKSuBjPrftGC8VP0aXK2Uxu6-RT15RBlHOcJFTad/pubchart?oid=271725602&format=image)


Similarly, I thought that there would be a connection between leaders who had studied abroad and then were inspired to start a rebellion. There is no significant impact from studying abroad.

![Rebels that Studied Abroad](https://docs.google.com/spreadsheets/d/e/2PACX-1vThUpIfhd_-rAOV3hq50J0M4k0uF-Y1Q5rQ9P9EuKSuBjPrftGC8VP0aXK2Uxu6-RT15RBlHOcJFTad/pubchart?oid=2146567615&format=image)

Lastly, I used a pivot table to look at the relationship between the rebel leaders and their area of study. If there were majors that lead to more rebellions, there would be a followup question as to why. Surprisingly, there is a noticeable difference between studies like religion, military, and law compared to the other areas of study. The sum of those three make up 23% of the whole dataset. Although this does not suggest that studying these subjects causes someone to become a rebel leader, it may reflect the skills, authority, or social roles associated with these fields. Religious leaders often hold positions of influence within their communities, military training provides organizational and strategic knowledge, and legal education can expose individuals to issues of governance, justice, and political systems. 

![Most Popular Areas of Study](https://docs.google.com/spreadsheets/d/e/2PACX-1vThUpIfhd_-rAOV3hq50J0M4k0uF-Y1Q5rQ9P9EuKSuBjPrftGC8VP0aXK2Uxu6-RT15RBlHOcJFTad/pubchart?oid=303416000&format=image)


## Conclusion

This dataset digests the global distribution of rebel leaders using data from Rebel Organization Leaders (ROLE) Project. By mapping where rebel groups have operated and examining patterns across countries, the project highlights that rebel leaders are not evenly distributed throughout the world. Instead, they tend to be concentrated in regions experiencing political instability. 
Although the data reveal where rebel organizations have been active, they do not explain why conflicts emerged or how they evolved over time. Though this isn’t a big concern, a journalist should be aware that they need to supplement this data with more information. Simply showing that a country has many rebel organizations could lead readers to incorrectly assume that the country is inherently violent or unstable. In reality, many countries represented in the dataset have experienced only certain periods of conflict, while others have made significant progress toward peace. Yugoslavia, for example, was a country in the Balkans that existed from 1918 to 1992 and is featured in this dataset; but has since been divided into six independent countries and one recognized state. The map should therefore be interpreted as a record of documented rebel leaders rather than a measure of a country's present-day stability.

There are several ethical concerns that should be considered when presenting this information. One concern is the possibility of stigmatizing countries or populations that appear frequently in the dataset. Readers may unintentionally associate entire regions with violence, even though the vast majority of people living in those countries are not involved in armed conflict. Another concern is that rebel organizations are often labeled differently depending on political perspectives. Governments may classify a group as a terrorist organization while others describe it as an insurgency, resistance movement, or a liberation movement. Not knowing the exact primary and secondary sources that the authors used is a concern that readers should consider. Although I have faith that the ROLE Project follows consistent academic coding rules, those classifications still involve judgment and may not capture every perspective.

Another limitation is that the dataset depends on publicly available information. Rebel groups operating in remote areas or under highly secretive conditions may be underrepresented because reliable information is difficult to obtain. Civil wars are notoriously messy. Not every bit of information will be recorded, and even the recorded information may not be true. During war, accuracy of information in preparation for a biography is the least of a rebel leader’s concern. 

To produce a more complete story, additional reporting would be necessary. A journalist should examine the historical and political context behind the countries with the largest numbers of rebel organizations rather than relying solely on the visualization. Interviews with regional experts, political scientists, historians, humanitarian organizations, and people directly affected by conflict would provide important perspectives that are not captured by quantitative data alone. Comparing the ROLE dataset with other conflict databases, such as the Armed Conflict Location & Event Data Project (ACLED) or the Uppsala Conflict Data Program (UCDP), would also help verify patterns.

Additional reporting should also clarify how the data were collected and which conflicts were included or excluded. Readers should understand that this dataset is intended for academic research rather than as a definitive record of every armed group that has ever existed. 

Overall, this project demonstrates how data visualization can help communicate connections between rebel leaders. The ROLE dataset is a credible academic resource created by researchers who specialize in political violence and conflict studies. By combining quantitative evidence with historical context, multiple sources, and careful reporting, journalists can tell a more accurate and ethical story that informs readers without oversimplifying or misrepresenting the realities of armed conflict.

Seeing as there were 239 rebellion leaders who got their bachelor's or less (a whopping 56% of the dataset), I’m excited for my rebellion plan to come to fruition twenty years after I graduate, switch my major to religious studies, and move to a nation with prolonged internal conflict. 

### Source

Acosta, Benjamin, Reyko Huang, and Daniel Silverman. "Introducing ROLE: A Database of Rebel Leader Attributes in Armed Conflict." Journal of Peace Research. Online First.
Heres a link to their	[website!](https://www.rebelleaders.org/)
