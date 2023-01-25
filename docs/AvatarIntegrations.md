---
layout: default
title: Avatar Integrations
description: TotallyWholesome's direct Integrations with your VRChat avatar
---

# Avatar Integrations

## Leash Anchors
You can optionally override the placement of the leash on both the pet and master side, this allows you to specially set up the leash position where you'd like it, like let's say on a collar or otherwise. These anchors automatically override the bone selection.

This does require a touch more setup on the avatar, but it's pretty straightforward.

### Setting up the anchors
1. Create a GameObject on your avatars root named either TWLPetAnchor or TWLMasterAnchor, you can also add both if you'd like to override both. These should be in the same spot as your avatars' meshes.
2. Add a Parent Constraint component to the newly created GameObjects.
3. Position the GameObjects which you would like the leash to be attached to.
4. Add a new Constraint Source and select the closest bone to your anchor GameObject
5. Press the Activate button on the Parent Constraint component
6. You should now be ready to use your new anchor points!

## Avatar Parameter Integrations
Getting started with the Avatar parameter integrations is pretty easy, just add the parameters you wish to use to your avatar's parameter file and then TW will drive them when appropriate
### TWGag
TWGag is enabled when your master enables the pet gag toggle
### TWCollar
TWCollar is enabled when you are a pet
### TWMaster
TWMaster is enabled when you are a master