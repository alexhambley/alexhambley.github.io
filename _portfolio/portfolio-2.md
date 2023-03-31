---
title: "SmartBall: A Ubiquitous Computing Project"
excerpt: "A &quot;SmartBall&quot; designed to gamify a patient's recovery of hand injuries.<br/><img src='/images/portfolio/smartball.jpg' alt='A ball with a Raspberry Pi inside. In the background is a laptop displaying graphs.'>"
collection: portfolio
---

This "SmartBall" was one of my first HCI projects. Looking back, it was (probably) what got me into Human-Centred AI and Human-Data Interaction. The ball contained a six-axis MEMS accelerometer and gyroscope. This tracked the user's throws, catches and spins. 

![Picture: A ball with a Raspberry Pi inside. In the background is a laptop displaying graphs.](/images/portfolio/smartball.jpg)

The data passed through high and low pass filters, and I wrote an algorithm to make inferences on this data. For example, how high the user threw the ball or how much of a spin there was.

The project was focussed on assisting users with accessibility issues - this later became a focus of my PhD, albeit in a different context. The ball attempted to gamify the recovery process for people with hand injuries through the use of psychological principles such as positive reinforcement, and hand exercises rooted in physiotherapy research. 

The ball also stored the points total for a session of successful catches and spins, and a user could see how their progress improved over time. The ball also supported a two-player implementation of "Hot Potato"!