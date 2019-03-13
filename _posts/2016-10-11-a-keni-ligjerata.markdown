---
layout: post
title:  "A keni ligjerata? Creating a more complex Android Application."
date:   2016-10-11 00:00:00 +0100
categories: projects android
---
Back at our university in Kosovo the library has a limited number of seats and most get taken in the morning so if you want to study in the university you have to find a seat in one of the many lecture rooms. These often are used by teachers for lectures so often end up switching rooms all day instead of learning, so we created an interactive application which helps choosing the right room based on the schedule, where others can also add comments about those rooms and share their experience.

## How the app works:
The application consists of the main screen where the user can open maps to find the way to the faculty building, a lightning test and the fourth floor image where all the available classes are shown and are colored green if they're free and red if they're not. 

Here is where all the magic happens, the application sends a request for the schedule and comments to a web service middleman, coded in PHP, which outputs the information from a remote database in a JSON format and the app stores the JSON objects in the local database if internet is available, else it checks if they're any previous versions of the schedule and notifies the user that the schedule is outdated but continues working while disabling commenting. If the user is using the application for the first time and hasn’t updated the schedule at all the user can’t continue to the interactive floor plan.

The fourth floor image is made interactive by implementing an invisible copy of the fourth floor plan but where the rooms that we want to be touchable by the user are colored differently, so basically when the user touches the first image it gets the x and y coordinates and gets the color of the invisible plan on that exact pixel, if it matches any of our set colors then based on the color that was clicked a different room activity is opened.  

![Fourth Floor](https://github.com/gentrexha/A_Keni_Ligjerata/blob/master/Description_Images/fourth_floor_.png)
![Fourth Floor Color Hotspots](https://github.com/gentrexha/A_Keni_Ligjerata/blob/master/Description_Images/fourth_floor_area.png)

When a certain room is touched a new activity is opened, consisting of a class picture and two list. The first list shows the current’s room schedule for that day and the second one shows a list of comments which are shared between instances. The user can add a new comment if internet connectivity is available which also is done through our PHP middleman service, after which the list refreshes and shows the recent added comment.

## Group experience:
The biggest problem for us doing this project was on finding a way on how to approach developing the application, we spent a lot of time in researching for different application architectures which would best suit our needs. Since we wanted that all of the classes availability to be displayed in one picture, because nobody likes reading big list of schedules just to find out if the class is free or not, we had to draw the floor plans our self. We spent a lot of time on developing an architecture to sync the schedule between the local database and the online one, so even if the user isn’t connected to the internet the application would still work.

## What's next:
The first thing which come to mind by extending the application is to make it work for other faculties as well, since all of them share the same problem. Adding a rating system for the comment section would be good as well since at the moment comments only get sorted by date, a method to identify owners of comments through Facebook or Google+ identification must be added aswell. Also another handy feature would be for the user to receive information in the form of push notifications for a certain class, i.e. Class gets taken in 15 minutes. From a maintenance perspective the comment system needs to be updated to be able to be moderated more easily and the schedule retrieving method needs to be more automated because inserting all of the lecture rows in the database by hand can get very frustrating.

## Risks associated with the application:
Probably the biggest risk factor in the application is that the schedule can't be taken 100% for reliable, a lot of schedules change dynamically through the semester, classes are occupied by students taking tests or different school meetings happen. Which means we have to make it clear to the user that we can’t take responsibility for the correctness of the schedule in our application.

## Business and financial opportunities:
Considering that each year almost 8000 new students register at the University of Prishtina [1] there exist quite a big user base for the application to be used. Although not all of them use Android, because of this the application could be migrated to iOS to reach a bigger user base [2]. Adding ads to the application would be a very good alternative to create profit while still keeping the application free and not disrupting user experience.

## References:
[1] UP Registration Contest, http://www.uni-pr.edu/Lajmet/Konkurs-per-pranimin-e-studenteve-ne-vitin-e-pare-.aspx

[2] Should you build an iOS or Android App?, https://crew.co/how-to-build-an-online-business/build-ios-app-or-android-app/

## Github:
https://github.com/gentrexha/A_Keni_Ligjerata

### Group members:
Florim Hamiti, 998904
Gent Rexha, 998903

