# Data Visualization Project

## Data

The data I propose to visualize for my project is that of the videogame sales This dataset contains a list of video games with sales greater than 100,000 copies. It was generated by a scrape of vgchartz.com. Fields include Rank - Ranking of overall sales, Name - The games name,Platform - Platform of the games release (i.e. PC,PS4, etc.), Year - Year of the game's release, Genre - Genre of the game, Publisher - Publisher of the game, NA_Sales - Sales in North America (in millions), EU_Sales - Sales in Europe (in millions), JP_Sales - Sales in Japan (in millions), Other_Sales - Sales in the rest of the world (in millions), Global_Sales - Total worldwide sales.

## Prototypes

I’ve created a proof of concept visualization of this data. It's a scatter plot with low opacity points and it shows the global sales of a game with respect to their platform.

[![image](https://github.com/VamsiSukamanchi/dataviz-project-template-proposal/blob/master/Screenshot%202020-09-30%20215515.png)](https://vizhub.com/VamsiSukamanchi/dcec3d913e2a46eaaef900af26dbde56)



## Questions & Tasks

The following tasks and questions will drive the visualization and interaction decisions for this project:

 * Do the sales of games increase every year, if so, which publisher is gaining more popularity?
 * How much correlated are the sales of a game in different regions?
 * Does a region favor any publisher, genre or platform?
 * How many sequels or remakes have made it to the list?

## Sketches
![image](https://github.com/VamsiSukamanchi/dataviz-project-template-proposal/blob/master/IMG20201001174437.jpg)

The axes represent the year and total global sales, using the publisher variable as color in bar (stack). Hopefully, the number of publishers are not high making it hard for viz. The first question will be answered through this. If the bars are like a waterfall, then then there is increase in sales every year. Using tooltip, we can see which stack of the bar is increasing in length, to see which publisher is gaining popularity.

![image](https://github.com/VamsiSukamanchi/dataviz-project-template-proposal/blob/master/IMG20201001174458.jpg)

For this viz, i'm considering a sample set of the data to draw conclusions. The axes are name of the game and region, with area representing the sales. If I observe a pattern like the ratio in area is same, then the sales are highly correlated. 

## Open Questions
 - Can rows be parsed word by word into a dictionary to find common words?
 - Can we take a sample set to represent the whole set fairly?

## Schedule of deliverables
 - For task 1, I will make a scatter plot with sales and year on axes with a menu filtering the publisher and see which one has an increase in sales (probably by producing a correaltion table for each publisher for an easy view of all publishers to the side). This will take two weeks to complete. Date of submission: 10/21/20
 - For task 2, I will create a line chart with each line representing a region with games and their sales as the axes and the interaction would be to choose a game such that it would highlight the points of the sales of a game in all lines(if possible). I will see if these points increase/decrease w.r.t. previous points. This will take one and a half week to complete. Date of submission: 11/1/20
 - For task 3, I plan to funnel/area/bubble chart for sales in every region. So the number of graphs is equal to number of regions and see which area is the greatest. This will take one week of time to complete. Date of submission: 11/8/20
 - For task 4, I would create a word search bar with autocomplete feature to find matching games to check whether there are there. This will take half a week to complete. Thus, totaling to five weeks of work. Date of submission: 11/11/20

## Final Vizs and insights

[![image](https://github.com/VamsiSukamanchi/dataviz-project-final/blob/master/1.png)](https://vizhub.com/VamsiSukamanchi/a202ddcc762f4d6a9a9e1d2af522b772)

[![image](https://github.com/VamsiSukamanchi/dataviz-project-final/blob/master/Screenshot%202020-11-08%20174739.png)](https://vizhub.com/VamsiSukamanchi/48ab2bdba2df494cbd688fbbfbf1f26f)

[![image](https://github.com/VamsiSukamanchi/dataviz-project-final/blob/master/Screenshot%202020-11-08%20175030.png)](https://vizhub.com/VamsiSukamanchi/c37eb738105840de9f43cdc889a72018)
