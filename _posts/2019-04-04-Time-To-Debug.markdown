---
layout: post
title:  "Time To Debug"
date:   2019-04-04 16:01:03 +1200
categories: jekyll update
---

After rolling out a second version of Taking Steps to the google play store we were hoping all issues would have been fixed so the client could finally be able to see the application we have help build. This was not the case, the previous error was still happening with no android devices being compatible.

I decided it was time that I did a major debug on the app especially with all the build files to try and solve the problem. **I estimated and allowed myself up to 2-3 sessions to work on this.** I researched a lot online but no one had a answer and no one else seemed to have the exact same issue as me. Many posts online keep highlighting the targetSDKVersion and MinSDKVersion sections on the build gradle file which can cause a lot of issues if not correctly set up. I edited this, generated a new APK and rolled it out to the google play store. Once again we have to wait 24 hours for google to update to the new version.

If the third attempt doesn't work Adon suggested create a new project and building it step by step with the old code to help identify which component breaks the application exactly. Pressure is also mounting from the client Leon as he is wanting to conduct a study using the app as soon as possible.

**New Gradle Setup** -
![](/assets/gradle.JPG)