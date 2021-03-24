---
title: "Do not waste time on re-inventing"
description: "Team Coding"
layout: post
toc: false
comments: true
image: images/march2021/cycleing.jpg
hide: false
search_exclude: true
categories: [dev_experience]
metadata_key1: metadata_value1
metadata_key2: metadata_value2
---

"Do not waste time on re-inventing the same thing other people has already invented!" Probably every new comer in tech industry heard this for at least several times. I can totally understand this feeling as a coding newbie, sometimes it is hard to resist the tempting of "oh I can invent a small function to make the project cooler / smoother!". After several hours when you are quite satisfied with what you have invented, which almost fit your task perfectly, "Just two more conditions to deal with!" and you want to show your work to your senior to show off a bit. Most of the time they will give you this heart-breaking response, and show you where you can find a basically the same if not better function (better structured / more flexible / more considering etc.) sleeping somewhere.

### Why is it important not to re-invent the same thing?
The obvious answer is time saving, there is no value add in re-inventing the same function again and again, right? But more importantly, this is also related to the maintenance of codes. By using the same function locating at the same position for similar job, not only we (as a newbie) can learn the coding practices, but our teammates can understand our code quicker, making it easier for them to pick up our work.

### But...how do I know if the function was invented??
Just goto the arsenal of your team / company / department. Usually we can find most commonly used function in the "utility" folder / file. For example my team has a utility folder with different weapons inside, functions for data cleansing, database, and more. Whenever I need to do something seems common (e.g. converting strings with different time format to datetime object), I went there and search for some keywords before I start inventing my own (sometimes I pick a function which did 80 \% of what I want, and start from there).
