---
layout: post
title:  "React Native Maps (Google)"
date:   2019-05-16 16:01:03 +1200
categories: jekyll update
--- 

After our meeting with Grayson our new project manager he tasked me with probably the biggest job of all semester so far. This was implementing Maps using React into our Project. He suggested using Googles API as it was the most documented and easist to use. He wanted this task completed by 5 days so I put alot of time into this job straight away giving it all of my attention.

My first step was to obtain a Google API key. Alot of the tutorials required me to use a credit card to be put onto my google account to unlock a key. I eventually found a short cut for this from a youtube tutorial resulting in my achieving a key without giving payment information. 

Second step was to implement the maps, after researching I found plenty of resources to start my coding. I needed the app to load the users current location and position the google maps off their current GPS location based off their phone. I had to set multiple permissions in the manifest file, this file also housed the API key. After tinkering for a while I was able to produce what I was tasked to do. I completed some testing with the android elemulator by setting the elemulators location to random locations to check if it picked up the new GPS coordiations. Once all these tests passed I tried our physical device and worked without problem positioning the map and marker on Otago Polytechnic.

I was quite surpised when developing this due to when trying to use location services in Android Studio using Java I had countless problems compared to almost zero problems in React.<br><br>

**Screenshot of Maps-**<br>
![](/assets/may16_1.JPG)