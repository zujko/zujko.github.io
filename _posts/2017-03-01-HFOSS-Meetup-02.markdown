---
title: "Meetup 2 RocPy"
layout: post
date: 2017-03-01
headerImage: false
tag:
- HFOSS
- RIT
blog: true
author: peterzujko
---

## Binary and WebSockets in Python
The theme of this RocPy meeting was talking about a basic implementation of a websocket server using python. 

## Binary
The meeting started out with a refresher on binary, then a discussion on binary in python.
Some useful functions talked about in Python 3 were 
```
bytes()
bytearray()
bytes()
bin()
bit_length()
```

One interesting thing that I learned was that there is no built in data type for representing binary bits in Python.

## WebSocker server
The rest of the meeting was a discussion on implementing a basic WebSocket server in python. To be completely honest I got pretty lost during this part of the talk. I do not know much about the internals of the WebSocket protocol so when we started going deep into the code I was lost. One cool thing that I took away from this meeting was actually learning more about the WebSocket protocol. The following site describes the specifications of the WebSocket protocol and really helped me understand how it works. [https://tools.ietf.org/html/rfc6455](https://tools.ietf.org/html/rfc6455)
