---
title: Web Scraping for Noobs
date: 2019-11-02
template: blog
image: ./noob.jpg
banner: ./noob.jpg
description: The state of webscraping - 2019s
---
So i'm a little late publishing articles. I have been working on them, just not publishing them. Lucky for me, no one reads this blog -- *yet*, so no one's upset! Hurray!

Anyway, this article's just my experiance with web scraping in 2019. I'm not very experianced, I hadn't done any webscraping for two years, so I looked at all my options and started fresh. 
In this article i'll tell you the steps and tools used in webscraping, as well as some tricks you can use to make your webscraping easier.

First of all what can you use for webscraping?
When I first started the project my first thought was, "it's 2019, surely I can automate this stuff by now, webscraping is so widespread." And thus it is, I looked into some of the tools that promised this which you can find with a quick google search.
These seem fine for simple web scraping projects or if you're probing a site for new information. For more complex applications you need to pay for pro versions or of course, program it yourself.

The project I was working on specifically involved parsing out a few links using regex, getting a list of links within those pages, and then recursively paging through documents in those links until the document was over.
Because of the complexity, online solutions weren't an option for me.


#### Overview:
What are the steps to create a webscraper?
Usually first you simply get the webpage's HTML from a web request.</br>
Next parse that HTML with a webparsing library. This is pretty much the core of your webscraper.</br>
And you're done!</br>

In today's world of shiny, *single page apps*,  and *javascript loaded content*, you might need something more powerful. A lot of people use something like puppeteer - a tool provided by google which allows you to programatically control your browser (chromium) so you can do fancy things like click, scroll, login, and what not. Some people claim this is overkill for webscraping and not what tools like puppeteer were built for, but hey it works 🤷‍♂️

#### Some specifics on tools:

###### Javascript </br>
I do most of my other programming in NodeJS, so I started with that first. The most popular libraries I found were Axios and Cheerio.
```
    npm install --save axios cheerio
```
First axios 
