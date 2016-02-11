---
layout: post
title: "Hashes vs Arrays"
date: 2016-02-11 09:25:00
comments: true
description: ""
keywords: ""
categories:
- welcome
tags:
- welcome
---

Henry Faversham


To start off, the biggest difference between hashes and arrays is their labeling. In arrays, everything is labeled numerically. So the first item will be zero, the second item will be one and so on. In hashes you create a key (or title) for each item. So if you’re first item is pineapple, the title (or label) you might want to put on it would be fruit or food (or anything you want). The number one reason why you would use an array is for an ordered list. For example, if you had a grocery list you’d rather have an array titled “Grocery list” than a hash containing the foods you’d like to buy. You would rather use a hash when you want to store information involving something with a title (or a key). So if you wanted to create a playlist full of songs, you would probably want to make a hash rather than an array. In the hash you could make the key (or title) the name of the band, and the content under it would be the song. Hashes are clearly better when it comes to customization, but if you have a simple list arrays are much more efficient way of storing this simple list. Also a similarity between the two is that you can store arrays inside of hashes, and you can store hashes inside of arrays. Although you can store hashes inside of arrays it’s not very useful, and I can’t think of many scenarios in which you’d want to store hashes inside of arrays. On the other hand, storing arrays inside of hashes can be very useful. For example, you can make a hash titled “Favorite Things”, and inside of that you can have all of your favorite things. Under the key “Favorite foods”, you can have a list (or array) of your favorite foods, and then under the key “Favorite animals” you can have a list (or array) of your favorite animals and so on. Also it is much easier (in my opinion) to edit and delete parts of hashes than arrays. Although it seems like arrays aren’t very useful because its customization skills are inferior to hashes, a simple array is much more useful that you think. 


Sources:
 https://teamtreehouse.com/community/when-do-you-use-an-array-versus-a-hash-in-ruby

http://stackoverflow.com/questions/25313658/when-is-it-better-to-use-an-array-instead-of-a-hash-in-perl

http://ruby-doc.org/core-2.3.0/Array.html

http://ruby-doc.org/core-2.3.0/Hash.html

