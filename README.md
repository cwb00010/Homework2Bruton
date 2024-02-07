# Farm Max App

I came up with the idea of this app with the hopes of helping farmers with the daily work. 
The plan for the app is to quickly and easily give them a way to look at climate trends. They can also look at more basic climate data or more in depth data, for example ground moisture
Lastly, the hope is the app can notify of future drought conditions or severe weather. 

## Table of Contents
- [Page Descriptions](#page-descriptions)
- [Research Summary](#research-summary)
- [GitHub Repository Research](#github-repository-research)
- [Future Enhancements](#future-enhancements)
- [Usage](#usage)
- [Citations](#citations)
- [Reflection on Resources](#reflection-on-resources)

## Page Descriptions

### HomePage
My home page contains the name of the app followed by a navigation menu. This navigation section contains links to other sections including the results/climate data.
This is followed by a small content section that talks to the user and welcomes them and talks to them about the app. It also encourages theuser to be involved in the environment.
Also a small footer that indictates the app is "owned" by Farm Max.

For the technical aspect, is relatively basic but has a semantic mark up. It has an HTML structure with various header and body tags. It has a nav menu using <nav> and anchor points for
the various sections. The main content page has a <main> with <h2> heading, and followed by <p> paragraphs with content. At the end is a small <footer> tag. 

### Results
My results/Climate Page contains the same navigation section and name of the app. This way users can navigate back to the home if need be. Below is the table with the climate data within. It's simple with just the date, temp, and humidity.
Like the other page it has a footer with copyright info for the app. 

In regards to the technical pieces, it has the same HTML structure with header tags for the app name. This followed by the navigation <nav> section to go back to home if need be. It has a main content 
<main> tag and header <h2> tag. Below, is the table structure with <thead>, <table>, <tbody>, <th> , and <tr> elements. These are the build up of the table. The <footer> tag contains the same "copyright"
info. This page has external and custom script to boost user interactivity, functionality, and style.

## Research Summary

### [NCEI - National Centers for Environmental Information](https://www.ncei.noaa.gov/cdo-web/)
From what I have gathered from inspecting this document is a lot of java script being used for the various buttons around the page. 
These buttons go to various tools and other areas within the site. I like the bootstrap used for the site. The color used is appealing.
Also, the general build of the site is relatively simple and user-friendly. I am very used to government sites being boring and painful to use. This is a change. 
The access to the climate tools and data is simple. Anyone can use this site and have an enjoyable experience.

### [Climate Data](https://en.climate-data.org/)
Off the bat, the site is much rougher than the previous one. It feels much more clunky and runs slowly. There are ads everywhere you look. 
This opening page also has much more content. In the inspection, there is a massive amount of java script. Significantly more than the NCEI site. 
This makes sense considering how much more content is on the site. Instead of a script that takes you to another page with cities/destinations, every city is a button. 
The lists are large and will all send you to another page. Visually, it is just ok. The bootstrap used isn’t bad at all. It’s just more bland and basic. 
The site is still simple to use, but not the same as the first sight.

### [Data.gov](https://data.gov/)
I see this site as the sweet spot between the initial two sites. The bootstrap is simple but catches the eye. It has a decent amount of content and buttons on the page but nothing excessive. 
The headers are self-explanatory and concise. It is simple for me and good for other users. When I typed climate into the search bar it gave me a Google-like result. 
It was a list of data sets related to climate and easy to look at each. Lastly, the site was redesigned in the last year are learned later. It may be my favorite of the three. 
Ran well, looked good, and user friendly.

## GitHub Repository Research

### [HamzaZaidiX/Weather-App](https://github.com/HamzaZaidiX/Weather-App/blob/main/README.md)
I like Hamza’s idea and final product. His repository is very organized and easy to navigate. His README is fantastic. He very briefly explains what he created followed by a GIF of the app in action. 
I had no idea you could put that in a README. He has sections for materials, APIs, icons, and fonts he used. Each is simple and clear for the reader. Even emojis to add some pop. 
At the bottom, he even has credits to another user and their repository. He explains this is where he got the idea and got an insight into UI/UX.

### [kshitizrohilla/weather-app-using-openweathermap-api](https://github.com/kshitizrohilla/weather-app-using-openweathermap-api/blob/main/README.md)
Like Hamza, Kshitiz his repository is well organized and it all comes together well in his README. 
He opens with an explanation as to what he created followed by a configuration section. This section mentions needing an API key to use the app and how to set up an API key. 
The instructions are clear and easy to understand. He has screenshots below that show the final product and provide multiple user views. He doesn’t put any sources he used for building the app in the README. 
Possibly he did this all himself but it would be nice if he provided a better breakdown for anyone looking to do something similar.

## Future Enhancments

I hope to be able to somehow connect it to an actual database, and provide extensive info for users while maintaining user friendly nature. I also have thought about sorting
by region or area. Lastly, I would consider adding graphs and imagery for users to look at.

## Usage

In this version of the app, It's extremely basic to use and has a basic home page. From there you can click into climate data that just shows the date, temperature, and humidity. 
NOTE!!!!! For it to work, I kept needing to add /HomePage to https://localhost:7102 for it work. It was a random error that I am stumped on. 


## Citations

https://chat.openai.com/
I aked for a markdown READ ME template to use. Provided a good template that I changed to meet the needs of my README. 
I asked for a project plan to most efficiently and completely the assignment. Provided a day by day plan for me to use. 
I asked for help creating a table to present data on my page. It gave me the general idea how to, from there I built it my way to meet my needs.

https://www.w3schools.com/html/default.asp

https://github.com/

https://www.google.com/

## Reflection on Resources

In the process of doing this assignment, outside resources were a huge help with everything I did. W3 Schools was super good to look at for examples to use in my assignment.
Google was how I found my repositories for research. It felt easier than searching in GitHub itself and I found two really good ones. I did use ChatGPT on a couple different
parts of my project. It was helpful in looking for mistakes in my code and also answering any questions I had regarding it. I also used it to create a work plan for this assignment
withing the time span I had. It created a pretty solid plan that worked well for me. I was impressed with how well it recognized code. Sometimes any code it put out was a little off. 
