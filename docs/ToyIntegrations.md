---
layout: default
title: Toy Integrations
description: TotallyWholesome's integration with other mods and physical toys
---

# Toy Integrations

## Toy Control
if you want to get your toys controlled make sure to enable it in the settings and restart afterward (not always required but a good habit to do so)

## Control
Each pet can be controlled individually via the ActionMenu or via the QuickMenu. You won't get any feedback if the pet has a toy connected and allowed control. ~Well you will probably see a reaction on the pet if it works~

## VibeGoBrrr Integration
If you are already using VibeGoBrrr you can ignore everything afterward. If VGB is detected it is integrated into the VGB environment as a sensor. This means the strongest value between your Touchzones, DPS, and TW.

## Setup Intiface (Buttplug.io)
Luckily for you, you don't need to set up Intiface. If you still want feel free to [download](https://intiface.com/desktop/) and install it.
If you want to use your own installation make sure to start the Intiface server first before you start VRC.

_More information on this can be found here for [lovense toys](https://how.do.i.get.buttplug.in/hardware/lovense.html) as there are some specifics you need to be aware of_


# TW Toy Integration Guide - by Kin-Kay

## How to get ya toy to work with TW, hopefully.

## The Setup
> This guide assumes that you have a working/charged toy and a computer that can **Stably** run the Melonloader mod "TW".

> This guide also assumes you are using a lovense toy.

> This guide assumes you have turned on toy control in the TW settings.

> If your VRC is crashing or your toy physically isn't working. You should probably get that fixed first.

> ~~*This guide assumes too much*~~

First things first, figure out how you would like to connect your toy to VRC. At the moment there are **2** general ways of connecting your toy to VRC.
1. Toy -> Computer
1. Toy -> Phone -> Computer

## Toy -> Computer
There are a couple more options when connecting the toy directly to the computer.

### Bluetooth LE
You will need:
1. Built in Bluetooth 4 and LE capabilities

or

1. A Bluetooth dongle with Bluetooth 4 and LE capabilities

Ensure that the bluetooth dongle is plugged into the computer.

Ensure toy is set to pairing mode.
> This guide assumes you do not have the app open on your phone due to the fact that the toy may connect to the phone before it connects to the computer.

Boot up VRC with the TW mod. *Profit*


### Lovense Dongles
> This is one of the more unreliable forms of connection, *supposedly*.

You will need:
1. Lovense HID Dongle

or

1. Lovense Serial Dongle

Ensure that the Dongle is plugged into the computer.

Ensure toy is set to pairing mode.
> This guide assumes you do not have the app open on your phone due to the fact that the toy may connect to the phone before it connects to the computer.

Boot up VRC with the TW mod. *Profit*

## Toy -> Phone -> Computer
This one is one can be a simpler way of connecting your toy to your computer. But if its not working often requires knowledge of networking. If it works it works, if not better try something else

You will need:
1. Lovense Connect App
> This guide assumes you installed the Lovense ***CONNECT*** app not the Lovense ***REMOTE*** app. ~~*Yes those are different apps...*~~

Go through the steps of connecting your toy to the Lovense Connect App.

Once the toy is connected to the app, ensure that the computer and the phone with the app running are on the same network.
> **THIS MEANS NO VPNS** It has to be on *the same network*. 

Boot up VRC with the TW mod. *Profit*

# Something not working?
If something isn't working you can troubleshoot the problem yourself before seeking help.

## Running Intiface Desktop
TW runs using Buttplug.io which runs using Intiface.
> For reasons of simplicity Buttplug.io and Intiface are synonymous.

You can download/install a desktop version of Intiface allowing you to test **Bluetooth LE**, **Lovense Connect App**, and **Lovense Dongles** to see if they work outside of TW

If the toys connect and work outside of TW then they should work inside of TW
### Exceptions
Vibe Go Brr
> This guide assumes you aren't using Vibe Go Brr so won't cover the problems that can come up with using Vibe Go Brr.

> General solutions are to ensure that your Vibe Go Brr is the newest stable version and/or the version supported by TW
