# Australia's parkrun capital 🏃

It turns out that Melbourne is Australia's parkrun capital with 49 parkrun events calling the city home.

Every Saturday morning, thousands of Melburnians take part in their local community parkrun — running, jogging or walking their way around a 5-kilometre course.

This analysis set out to be a light-hearted look at how these different events compare in terms of which parkruns are the most popular and which one could lay claim to the title of 'speediest' course.

Find out which parkruns took the honours here: https://zthetrain.github.io/parkrun/

## Data collection

I had to first determine which parkruns were in the Greater Melbourne area from [a json file listing all parkrun events globally](https://images.parkrun.com/events.json) and figure out which definition of Greater Melbourne I was going to use. I ended up going for [OpenStreetMap's definition](https://www.openstreetmap.org/relation/4246124#map=9/-38.070/145.269) because I felt it would make more sense to a regular Melburnian than the stricter version defined by [the State Revenue Office/DataVic](https://www.sro.vic.gov.au/greater-melbourne-map-and-urban-zones#current-greater-melbourne). I then scraped the latest results page for each of the [49 Melbourne parkruns](https://www.parkrun.com.au/) I was looking at in my analysis.

## Data analysis

I compared the different events in terms of number of participants to rank the parkruns in order of popularity.

I calculated which course was the speediest two different ways. First I calculated the mean time it took people to complete each course. And then because this didn't take into account the different ages of the participants, I also calculated the mean age grade score for each course.

I used Datawrapper to visualise all these results.

## Skills gained during this project

This project helped me reinforce and build my skills when it came to working with GeoPandas, scraping tools and cleaning data. It also allowed me to become more familiar with Datawrapper as a visualisation platform. I also gained confidence in taking an idea from initial conception through to the finished product, learning how to navigate obstacles and pivot the project as required along the way.

## Things I would have liked to do

I would still like to learn how to make auto-updating CSV files and visualisations but it became apparent this was not the right project to learn that on. I will keep it in mind for a future one.
