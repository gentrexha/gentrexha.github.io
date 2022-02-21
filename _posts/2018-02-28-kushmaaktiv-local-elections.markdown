---
layout: post
title:  "KushMaAktiv.com - An online dashboard for providing an overview of political parties on Social Media"
date:   2018-02-28 00:00:00 +0100
categories: facebook data mining visualization
---
For the municipality elections of Kosovo in 2017, and seeing the rising influence of social media in elections, I wanted to analyze the curret 5 candidates for my city and see how they performed online. Below you can see a snapshot of the data for for the local election day on 2017-10-21:

![Kushmaaktiv Local Election 2017 with results](https://github.com/gentrexha/gentrexha.github.io/blob/master/assets/images/posts/kushmaaktiv-local-election-2017-w-results.png?raw=true)

Having received very positive feedback on my initial analysis, I wanted to extend this analysis into a bigger application and decided to create a public dashboard for looking up all the public social figures in Kosove. For this I created KushMaAktiv.com (from Albanian meaning WhosMoreActive.com), which is an online dashboard for people to look up the social activities of policitcal figures in Kosovo and see how popular they are compared to others. Here's a view of the website:

![KushMaAktiv.com Website View](https://i.imgur.com/wrlAl0L.png)

All data presented in the graphs of the site is obtained in real time from the Facebook Graph API, through which the API provides access to public Facebook data, and then calculates the total activity through algorithm which takes into account all likes, comments and distributions of one page or profile posts in one day.

![](http://i.imgur.com/f4vJXJI.png)


Facebook Activity taken from [Facebook Graph API](https://developers.facebook.com/docs/graph-api/) using PHP and MySQL.

Election data taken from [Kosovo's Central Election Commission](http://www.kqz-ks.org/zgjedhjet-2/zgjedhjet-lokale/per-kryetar-te-komunave/zgjedhjet-per-kryetar-komune-2017/).