---
layout: default
title: AV3 Remote Control
description: Information about TotallyWholesome's integration with AV3 parameters
---

# AV3 Remote Control

The AV3 remote control system allows you to mess with your pet(s) AV3 parameters remotely, do note that the pet has to enable the parameters to allow the master to see and mess with them.

## For Pets
The setup for a pet is pretty simple, from the main TW tab you can choose AV3 Remote Config, once in there you'll see a list of all the AV3 parameters that you can enable. You can currently select up to 6 of those parameters. Once you do you can back out of that menu and the selected parameters will be saved, enabled parameters are saved per avatar, so once you configure it once they'll stay like that.

## For Masters
The usage for masters is very simple, once your pet has enabled some parameters for you to control. All you need to do is go to the TW Tab, select Individual Pet Controls, choose the pet you'd like to mess with and choose AV3 Param Control. Once you're in the AV3 Param Control menu you'll see the parameters your pet has enabled and can mess with them all you'd like.

## Caveats
There are currently a couple of limitations to be aware of with the AV3 Remote Control system.

* You MUST be using an SDK3/AV3 Avatar for it to work, and that avatar MUST have parameters set on it
* You can only enable 6 parameters to be controlled right now, this may change down the road
* Floats are handled a bit weird, the slider values are only sent when you close the AV3 Param Control menu, they also go from -1 to 1, so if the avatar expects 0 to 1 it may not work as expected when below 0