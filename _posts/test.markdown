---
layout: post
title:  "test post"
date:   2023-04-26 21:48:45 +0900
categories: blog
image: "/assets/images/screenshot_2023-04-265_205611-1.png"
---
this is test post.
this post can be edit anytime.

 tried to figure out how to fix ['remote rejected'] build my github blog.
 I found this solution.(very easy.. but I spend a lot of timesT-T)

delete all 'git' credential in "windows control panel - Credential Manager"
and go to github - Settings - Developer Settings - Personal access tokens - 
 -token(tab) - generate new token - check workflow - generate token(under the checklist) - push git - login for token - 
 -you can check blog url. and done!
