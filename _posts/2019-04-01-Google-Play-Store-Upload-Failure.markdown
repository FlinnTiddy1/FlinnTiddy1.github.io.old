---
layout: post
title:  "Google Play Store Upload Failure"
date:   2019-04-01 16:01:03 +1200
categories: jekyll update
---

After submitting Taking Steps google has a checking process which can take up to 48 hours. We waited this time out and it was published, but we went to download the application no one could find it on their phones and we started to worry. We were able to reach the app from a URL but when the install button was pressed every device we tired was not compatible.

This stumbled me so I reached out to Albert who had publish multiple app's himself, he told me to check out check the gradle dependencies inside the grade.build file.

There were multiple outdated and unneeded dependencies that I updated or removed and generated another signed APK file. I rolled out another version onto the play store, waited and crossed my fingers it would solve our problem(Have to wait till google approves again.)
<br><br><br>
**Screenshot of build gradle dependencies -**<br>
![](/assets/depen.jpg)