---
layout: post
title: "Robots.txt"
date: "2009-11-11 12:18:00"
updated: "2015-01-21 18:36:30"
description: 
---

Hi Friends,
Did you hear anything about this robots.txt file .This file is important for web development.The **bold**Robot Exclusion Standard, also known as the **bold**Robots Exclusion Protocol or **bold**robots.txt protocolis used to prevent files from **bold**web crawlers or **bold**Robots or **bold**Web Spiders .**bold**Web Crawlers ..What is this ? What is the purpose of this ? The answer is Web Crawlers areused(frequently used in search engines like Google ) to get data from [World Wide Web](http://en.wikipedia.org/wiki/World_Wide_Web) .How Search engines work ??![Alt text](http://1.bp.blogspot.com/-_w11_ktWZ-k/UhpiZRAuk2I/AAAAAAAAIJk/xngKkwsfVB0/s1600/searchenginechart.gif)![Alt Text](http://1.bp.blogspot.com/-_w11_ktWZ-k/UhpiZRAuk2I/AAAAAAAAIJk/xngKkwsfVB0/s320/searchenginechart.gif") 
1. Web Spiders(Google) are getting the data from the [World Wide Web](http://en.wikipedia.org/wiki/World_Wide_Web") and organizing the datain to their databases based on Meta Tags (this thing has been assigned for Index of this page).For example the web spiders get the meta tag as index(asp) and mapped to <a href="http://www.asp.net/" target="_blank">Asp.Net</a>.
2. when we are searching the word ‘asp’ in Google , it searches the database(Google's Database-It was already filled by using Webcrawlers ) by using the keyword ‘asp’ and get theresults(in the order of maximum hit counts(Rank)) like ![](http://4.bp.blogspot.com/-F07dvslIUGI/UhpiZTesrdI/AAAAAAAAIJw/XoeZk-6stcQ/s1600/aspsearch.jpg") ![Alt Text](http://4.bp.blogspot.com/-F07dvslIUGI/UhpiZTesrdI/AAAAAAAAIJw/XoeZk-6stcQ/s320/aspsearch.jpg)
Now i am coming to that point **bold**robots.txt , this WebCrawler will get all datas from our web server.So we have to stop the web crawler to getting our personal datas or something you needto hide(example: login page) from our webserver, this is the time we need this **bold**Robot Exclusion Standard(robots.txt).Step 1: You can add the pages(need for hide ) one by one in the robots.txt file.Step 2: Upload this file to your Web Server.That's It…

 This example allows all robots to visit all files because
 the wildcard "*"  specifies all robots:
{% highlight ruby %}
User-agent: *
Disallow:
This example keeps all robots out:
User-agent: *
Disallow: /
This example allows all robots to visit all files because
the wildcard "*" specifies all robots:
User-agent: *
Disallow:    This example keeps all robots out:
User-agent: *
Disallow: /
{% endhighlight %}
References:
1. <a href="http://en.wikipedia.org/wiki/Robots_exclusion_standard" target="_blank">Robots.txt</a><span style="color: #333333;">
2. <a href="http://computer.howstuffworks.com/search-engine.htm" target="_blank">How Search Engine Works</a>
Examples:
1.<a href="http://www.google.com/robots.txt" target="_blank">Google robots.txt</a>
2.<a href="http://en.wikipedia.org/robots.txt" target="_blank">Wikipedia robots.txt</a>


