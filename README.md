# Flag finder
This is my first ever Angular app. I've build it for an assignment during the PXL.Widgets Heroes Front End dev program. 

## View result
To see the page I created visit https://jeanettt.github.io/flag-finder

## Approach
1. First I watched tutorials from Angular University and a TypeScript tutorial.
2. Via the CLI I generated components, a custom search pipe and a service that fetches data from the countries API.
3. I built some custom filters. I wanted the filters to be dependent on each other. This was a good exercise for writing logic.
4. When everything was working, I did the styling and configured a standard image for broken image links from the API.
5. Finally I looked at my classmates work and added some improvements in the structure of my app.
6. Also I tried to switch my project to Sass, which gave me a headache but worked out in the end.

## Lessons learned
* Building a custom filter is a lot of work. I still have little bugs in it. F.i. when the filter is set to region, but currency is also used in other region, for instance if you select North America and then currency DKK, it also displays Denmark.
* Next time I am going to initiate my project with Sass and not switch later on.
