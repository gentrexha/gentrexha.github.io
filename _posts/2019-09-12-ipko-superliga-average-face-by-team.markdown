---
layout: post
title:  "IPKO Superliga 19/20 Average Face by Team"
date:   2019-09-13 00:00:00 +0100
categories: python facemorpher kosovo ipko superliga football soccer
---
Inspired by this [Reddit post](https://www.fsanmartin.co/soccer-world-cup-2018-average-face-by-team/), I wanted to try it out on some more familiar faces as well.

![average face visualization](https://raw.githubusercontent.com/gentrexha/gentrexha.github.io/master/assets/images/posts/kosovo-average-face.png)

The biggest obstacle was the data collection part, considering that not all pictures were available in one place. I tried collecting them programmatically from transfermarkt.com but wasn't satisfied with the results. I went over each club, found out their website, and downloaded the player pictures if it had any. Unfortunately, most of them did not. That's why some of the average faces for some clubs could be considered lackluster. 

Tools used: Python, facemorpher & Lunacy

Source: https://www.transfermarkt.com/jumplist/startseite/wettbewerb/KO1a
