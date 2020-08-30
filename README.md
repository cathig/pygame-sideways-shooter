# -*- coding: utf-8 -*-
"""
Created on Sun Aug 30 09:54:34 2020

@author: Cathig
"""
# Sideways Shooter
Welcome to a sideways shooter!

In this exercise from _Python Crash Course_ 2nd Ed (Chapter 12 p. 253), I practiced using pygame to place a moveable rocketship that shoots rectangles.

The rocket is constrained to the left side of the screen, remaining within the window frame.

The bullets start from the tip of the rocket ship and proceed across the screen. Once off screen, the program destroys each bullet.

![sample Sideways Shooter screen](/images/sampleScreen.jpg)

## How to Use
1. Run alien_invation.py.

   A game window with a rocket center left opens.

2. Move the rocket by pressing you keyboard's up and down arrow keys.

3. Shoot bullets from the rocket by pressing the spacebar.

   Note that only 3 bullets can exist at once. Once the bullets leave the other side of the screen, you can shoot more bullets.

4. Close the game window with the Close (X) button or press 'q'.