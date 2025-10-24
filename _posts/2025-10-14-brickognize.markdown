---
layout: post
title:  "Brickognize: Sorting LEGO the Hard Way"
date:   2025-10-14 13:12:19 -0400
categories: software
---

I finally found a use for my Hackintosh.

This summer I got the motivation to sort and itemize my entire LEGO collection that I had spent the first 20 years of my life amassing. I had previously sorted the collection with my brother during COVID, so why did I want to redo the weeks worth of mundane sorting I had done prior?
Initially, the collection was sorted solely by color. Each color (or groups of similar colors) had 1 or more gallon-sized bags. These bags were labeled "'red 1', 'red 2', 'brown 1', etc.".

There were a handful of reasons for doing it this way intially.

1. Sorting by color is intuitive for the human brain. People are much better at identifying colors than they are shapes. I think of the Stroop Effect, where it was found in a study that when partipants were shown color names that did not match their ink color (e.g., the word “RED” printed in blue ink), they took a longer time answering the color of the ink. This demonstrates the importance in priority of the color of an object when recognizing it.
2. Sorting by color would require less bags. In a usual LEGO collection, the number of colors is less than the number of parts. For reference, the number of active colors in LEGO sets in use in 2024 and 2025 is 74. The number of actively used unique LEGO pieces is roughly [3760](https://brickarchitect.com/bricks/). I didn't want to waste that much plastic, so I decided on a sort-by-color approach.

The effects of this sorting process was pretty immeadiate once I tried to actually use it. If I needed 1 small 1x1 black stud, I would be tasked looking through every single black brick for a tiny piece. There were agonizing times where I would be searching for a 2x2 plate just to think I found it in the pile, then pull it out and find it was a 2x3 plate.

This naive approach was not working for me. My ultimate goal with this project was to resurrect as many old sets as I could from the "bin". If I were able to rebuild, or at least create bags or to-be built sets, I would then have complete sets to either display or sell.

I decided to refactor my collection, this time sorting by piece instead of color. This would be difficult for the reasons inverse of sorting-by-color: It will be unintuitive and require more bags. I started with some of the pieces I knew I had a lot of in my collection, like 2x4 Bricks and plates. I started with the black bag, pulled out all the qualifying piece, counted them, then put them in their respective bag. I repeated these steps with the other colored bags. Once I went through all the colors, I moved onto the next element.

By counting each piece that I reorganized into a new bag, I was able to digitize [my collection](https://rebrickable.com/users/Eggbeater6071/partlists/) onto the website ReBrickable. The wesbite has a neat feature which is able to parse your loose parts collection to see what sets you can build (or are close to building). Using this feature, I was able to reremember some of my earliest LEGO sets and rebuild them, which was extremely rewarding.

So, how did I digitize my collection? I am not a LEGO expert, so while I knew some knowledge of lego piece naming conventions, there were more piece names that I didn't know than piece names I did know. Forunately, there are some LEGO recognition apps that work relatively well on iOS. Unfortunately, these apps are often paywalled with a limited amount of scans. There is a website called [Brickognize](https://brickognize.com/) that is a free service anf is extremely accurate from my experience. However, navigating the website on mobile, constantly having to take a photo and then upload it was clunky. Brickognize has it's API open for use, so I figured this would be the perfect usecase to try to develop an iOS app for my phone to use.

A few days later, I had a working app that scanned LEGO bricks, displayed the brick alongside it's name and brick ID (usefully for quick itemizing), and a history pane which allowed you to view previous scans. The app works about 2-3x quicker than the website. Was it worth the development time and diverge from sorting LEGO using the previously working website? Probably not, but I did learn a lot about iOS app development on XCode and REST apis.
