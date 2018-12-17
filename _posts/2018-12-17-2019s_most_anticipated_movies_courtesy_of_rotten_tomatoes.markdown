---
layout: post
title:      "2019's Most Anticipated Movies Courtesy of Rotten Tomatoes "
date:       2018-12-17 17:21:23 +0000
permalink:  2019s_most_anticipated_movies_courtesy_of_rotten_tomatoes
---


For my first portfolio project, I focused on something that I love very much - movies. Rotten Tomatoes has become my go to for movie news and reviews so I decided to keep on top of 2019’s most anticipated films by scraping Rotten Tomatoes and delivering a list of the films people are buzzing about. 

The process was fairly straightforward and using the Nokogiri gem enabled me to scrape the site. I did run into initial issues using Nokogiri as it doesn’t scrape sites generated with JavaScript. After four attempts at setting up and scraping different sites which turned out to have some sort of JavaScript component, I finally found a compatible page with the information that I wanted to display. 

Fortunately, redoing the project setup gave me a thorough understanding of how to scrape a site. Always gotta find the bright side, right? 

I found myself getting stuck on my logic with my menu - I could get the if statement to work properly for two options but beyond that it was getting too complicated. I determined it was better to simply give two options  in my menu - “select a movie” or “exit”. 

This simplification enabled me to not repeat steps later in the program when the user had finished reading a move synopsis and chose to either select another movie or exit the program. 


