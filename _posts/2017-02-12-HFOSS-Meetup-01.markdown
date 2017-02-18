---
title: "Meetup 1"
layout: post
date: 2017-02-12 19:00
headerImage: true
image: https://challengepost-s3-challengepost.netdna-ssl.com/photos/production/challenge_photos/000/425/251/datas/full_width.png
tag:
- HFOSS
- RIT
blog: true
author: peterzujko
---
This past weekend I attended BrickHack with two of my friends. Our project was to develop a live video chatting application which would tell the other user what the person's emotion was. In order to accomplish this, we used the [Microsoft Emotion API](https://www.microsoft.com/cognitive-services/en-us/emotion-api) which would give us data on what the user's facial expression is saying.

At first, we tried getting a simple live video chat app going but realized that none of us have ever done anything related to live video, so trying to figure out how exactly we were going to do this proved to be a difficult task. We ended up just trying to take a screenshot and send that to the API for processing. 

The initial implementation that we wrote had a client and a server. The client would send the screenshot to the server, the server would send that image to the emotion API, parse the response, then respond to the client with the emotion of the user in the image. 

A lot of time was spent on trying to get our Azure virtual machine to work, but after we got that going, everything seemed to work. The client side code was written by my friend in C# and I wrote all the server side code in Go. 

Overall, I would say that BrickHack was a good experience. I got to talk to some people about their own projects and talk to some cool companies!
