---
title: "Lone Driver"
date: "2016-07-07T09:00:00+10:00"
summary: "Keeping drivers safe in the deserts of WA."
icon: "lone-driver-launcher.png"
screens: ["lone-driver-screen1.png", "lone-driver-screen2.png"]
draft: false
---

At [Gridstone](https://gridstone.com.au), this app was built for a client based out of Western Australia. They have hundreds of workers that drive alone in WA's deserts where they're completely out of mobile coverage. Should anything happen to them they have no way of contacting their home base.

The solution we built interfaced with the Iridium satellite network in order to provide up-to-date information on the driver's location and current status. This proved challenging, as we interfaced with a CANBUS engine monitoring system over bluetooth, switched on and off satellite internet via a SOAP server running on an Iridium GO unit, transferred data over an amazingly slow connection, all whilst using the accelerometer to detect any potential accidents.

This was one of the most technically challenging but also rewarding applications I've ever worked on.
