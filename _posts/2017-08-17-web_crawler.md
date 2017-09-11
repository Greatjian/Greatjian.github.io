---
title: "Web Crawler"
layout: post
date: 2017-08-17 18:00
tag: Android
headerImage: true
projects: true
hidden: true # don't count this post in blog pagination
description: "A web crawler crawling technology articles."
category: project
author: Greatjian
externalLink: false
---

# Web Crawler

A web crawler crawling technology articles.

I crawled url, article title, time, link, content and attitude from the following websites
and store them in the PostgreSQL database. I then searched processed the content of the articles
using the target words provided, collected them to generate a weekly news report.
I also uploaded this work on to Amazon EC2 so that it could automatically send emails.

This work has highly increased the efficiency for my intern VC firm to find
potential investment opportunities.

First demo (word_count): using Flask platform 
for manually input of interested search words [Github Link](https://github.com/Greatjian/flask_word_count).

Final version for this project: [Github Link](https://github.com/Greatjian/web_crawler).


## Crawling Websites:

- http://additivemanufacturing.com/news/
- http://www.3ders.org/
- http://www.materialstoday.com/
- http://spectrum.ieee.org/computing
- http://spectrum.ieee.org/robotics
- http://spectrum.ieee.org/semiconductors
- http://spectrum.ieee.org/telecom
- http://spectrum.ieee.org/transportation
- http://spectrum.ieee.org/energy
- http://spectrum.ieee.org/biomedical
- http://www.popsci.com/health
- http://www.popsci.com/science
- http://www.popsci.com/technology
- http://www.nature.com/news/

## Report Sample

![](https://raw.githubusercontent.com/Greatjian/web_crawler/master/report_sample.jpeg)




