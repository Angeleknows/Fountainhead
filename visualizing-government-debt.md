## Assignment: [Visualizing Government Debt](visualizing-government-debt)
![OECD 2023 gen govnt debt percent of GDP](https://github.com/user-attachments/assets/db988fbf-4881-4528-a110-17c3586daf42)

<div class='tableauPlaceholder' id='viz1730710905777' style='position:relative'>
    <noscript>
        <a href='#'>
            <img alt='OECD General Government Debt (% of GDP, 2022)' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;OE&#47;OECD2022GDP&#47;OECDGeneralGovernmentDebtofGDP2022&#47;1_rss.png' style='border:none'/>
        </a>
    </noscript>
    <object class='tableauViz' style='display:none;'>
        <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F'/>
        <param name='embed_code_version' value='3'/>
        <param name='site_root' value=''/>
        <param name='name' value='OECD2022GDP&#47;OECDGeneralGovernmentDebtofGDP2022'/>
        <param name='tabs' value='no'/>
        <param name='toolbar' value='yes'/>
        <param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;OE&#47;OECD2022GDP&#47;OECDGeneralGovernmentDebtofGDP2022&#47;1.png'/>
        <param name='animate_transition' value='yes'/>
        <param name='display_static_image' value='yes'/>
        <param name='display_spinner' value='yes'/>
        <param name='display_overlay' value='yes'/>
        <param name='display_count' value='yes'/>
        <param name='language' value='en-GB'/>
        <param name='filter' value='publish=yes'/>
    </object>
</div>

<div class='tableauPlaceholder' id='viz1730716534124' style='position:relative'>
    <noscript>
        <a href='#'>
            <img alt='Understanding Median Government Debt Trends from 1995 to 2019' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Un&#47;UnderstandingMedianGovernmentDebtTrendsfrom1995to2019&#47;MedianGenGovtDebt90&#47;1_rss.png' style='border:none'/>
        </a>
    </noscript>
    <object class='tableauViz' style='display:none;'>
        <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F'/>
        <param name='embed_code_version' value='3'/>
        <param name='site_root' value=''/>
        <param name='name' value='UnderstandingMedianGovernmentDebtTrendsfrom1995to2019&#47;MedianGenGovtDebt90'/>
        <param name='tabs' value='no'/>
        <param name='toolbar' value='yes'/>
        <param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Un&#47;UnderstandingMedianGovernmentDebtTrendsfrom1995to2019&#47;MedianGenGovtDebt90&#47;1.png'/>
        <param name='animate_transition' value='yes'/>
        <param name='display_static_image' value='yes'/>
        <param name='display_spinner' value='yes'/>
        <param name='display_overlay' value='yes'/>
        <param name='display_count' value='yes'/>
        <param name='language' value='en-GB'/>
        <param name='filter' value='publish=yes'/>
    </object>
</div>


This visualization takes a look at five countries where the median government debt hit 90% or greater from 1999 to 2019. Over this decade, it’s evident that countries starting off with a sizable amount of debt kept piling on more. However, I realize this narrative can be a bit misleading since I didn’t fully account for the shifts in some countries’ values. For instance, Poland started off in 2009 with a median of 50.4%, yet its debt as a percentage of GDP steadily climbed, eventually landing it in the same ballpark as the other countries I focused on based on debt growth.

I zeroed in on Greece, the USA, Italy, Japan, and Canada because Tableau flagged them as outliers but I wasn't sure why. After closer inspection, what stood out to me was how these countries all experienced a notable bump in debt over the decade. I also overlooked Portugal when discussing increasing debt over time since it didn’t start with a median of at least 90% (beginning in the 70s), but its debt load still surged. Looking back, I think I could have done a better job visualizing this. Still, I’m pretty happy with how my dataviz highlights the outliers, using bright pops of color against a muted gray palette for the rest of the dataset. It really draws the eye to those key players and tells the story that certain countries with already high median debt levels just kept racking up more debt.

I personally prefer this representation over a two-toned heat map because it grabs the audience's attention and really communicates the narrative I want to convey. I leaned into using gray as a friend while letting color accentuate what I wanted to show. I initially tried bubble charts, but ultimately found their sizes, without any axes, to be out of context and challenging to interpret. So, I went with a Pointillism-inspired approach that’s visually striking due to the hierarchy I implemented by organizing the countries alphabetically. This worked in my favor, ensuring there was aesthetic balance in the frame. One tweak I would’ve loved to make, but didn’t know how, was to change the font color of the countries whose data is muted. Compared to the OECD bar chart, my dataviz emphasizes outliers through color and texture, and it’s rendered much cleaner than the heat map, which feels busy with distracting numeric values across the landscape.
