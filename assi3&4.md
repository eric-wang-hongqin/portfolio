# GDP by State, 2021-2022

## Original Data Visulizaition
[World Population Review](https://worldpopulationreview.com/state-rankings/gdp-by-state) produced a data visulization on GDP by state in 2021-2022. The article was to introduce GDP, and the top 10 states in US with the largest GDP number. The original map graph consists of lots of hex pieces, where each piece is representing one state. The 2-letter state abbreviates are labeled on each hex piece. States with larger GDP get darker blue color. The label line below the graph will change according to where your mouse is pointing at. 

![Image](original_viz.png)

## Wireframe
In the first wireframe, I redesigned the map graph, and decided to use real US map instead of hex ones. The new design can provide a more straight forward and vivid view linking the numbers to the state. It is easier to think about the numbers together with the states, including where the state is (east, west or middle), how big is the state area, is state a border state or an inland state, etc.

Initially, I was thinking about two options, which follows different color themes. In the left option, all colors are blue, but the states with higher GDP get darker color. In the right option, the color becomes from dark blue to dark orange.

![Image](wireframe1.jpeg)

In the second wireframe, I tend to highlight top 10 states with largest GDP. I thought of two chart type, pie chart and bar chart. Pie chart is good for presenting the percentage a state contributes to the country GDP, while bar chart is good for presenting ranking and absolute amount. To highlight top 10, I will combine the rest states as a whole, called others. 

![Image](wireframe2.jpeg)

## FeedBack

Interview 1:
- Can you tell me what you think this is?
* This is very straight forward to understand, this is GDP by State, as the title suggests. *

- Is there anything you find surprising or confusing?
* Not really, they are simple and staright forward. *

- Which color scheme do you prefer (all blue vs blue/orange)?
* All blues are great. But it could be better to highlight the top 10. *

- Do you prefer pie or bar chart when it comes to top 10 countries.
* Pie, it tells the percentage. I believe percentage makes more sense. *

- Who do you think is the intended audience for this?
* This might be for students who is studying economics and currently doing an research. *

- Is there anything you would change or do differently?
* The title can includs more information. *

Interview 2:
- Can you tell me what you think this is?
* GDP by State, Top states stats. *

- Is there anything you find surprising or confusing?
* No, quite clear. *

- Which color scheme do you prefer (all blue vs blue/orange)?
* Try blue/orange if you want your audience to look at both top and bottom. Otherwise use all blue to only highlight top ones. *

- Do you prefer pie or bar chart when it comes to top 10 countries.
* Why not try both, because they are telling different things, and usually the audience want to look at both. *

- Who do you think is the intended audience for this?
* Might be students or economic researchers. *

- Is there anything you would change or do differently?
* Put label and legend at a good place. *


## Final Visualization
<div class="flourish-embed flourish-map" data-src="visualisation/8626041"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

The story begins with a general look at GDP by state in 2021-2022. We can observe color get darker on the east and west coast, while the middle part has lighter colors, except Texas. California and New York stand out with the darkest color. This is true, California is the state producing the greatest GDP in the country, followed by Texas and New York. Apart from observing this general trend, we can move mouse to each state to review details in a pop-up window. The graph also provides a search function to fast locate a state, by simply type the state name in the searching bar.

However, one question that this graph cannot answer is what are other top states that also produce large GDP. We might find hard to find them out. So I decided to include additional two visuals to navigate audience attention to top 10 states. 

<div class="flourish-embed flourish-chart" data-src="visualisation/8637293"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

The bar chart gave up a staright look at the top 10 ranking and the amount of their GDP in 2021-2022. I used color to draw more attention on top 3 states and their numbers, while the rest are in a different colors. 

After knowing top 10 states, we are just curious how do they compare to the nation GDP?

<div class="flourish-embed flourish-chart" data-src="visualisation/8626187"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

Actually, from the pie chart, we found top 10 states almost produced double of the rest states combined. 

There are two state label is missing in the graph, which was not intended, but because Flourish does not support customised label position, so labels are either overlapping to each other, or some need to hide when there is no space. This problem can be solved by using other software. 


[Back to Main Page](/README.md)
