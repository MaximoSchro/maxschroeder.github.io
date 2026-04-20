---
draft: false
title: "Schrodinger's Delivery Service"
summary: "Made for Champlain Montreal Game Jam 2024."
cover:
    image: "img/schrodingers.png"
    alt: "Schrodinger Image"
coverGif: "img/SchrodingersDeliveryService.gif"
hiddenInHomeList: true
weight: 100
---
![Fincremental Image](img/schrodingers.png)
## Overview

In **Schrodinger's Delivery Service**, the player is presented with a box and must shake it to determine whether a cat is inside. If there is a cat, the player must deliver the box by throwing it at the house. If there is no cat, the player must throw the box aside to get a new one. 

{{< itch "https://itch.io/embed/3132390?dark=true">}}

**Platform:** Windows

**Role:** System Designer

**Engine:** Unity

**Date:** Novemeber 2024

**Theme:** Hometown

### Constraints

Our game had three constraints: it must include physics components, a sound-based mechanic, and a paradox.   

## My Work

I led my team during the 48 hours we had to make this game. In the first few hours, we decided on Schrodinger's cat to be our paradox, and shaking and throwing boxes to complete our sound and physics constraints. My work consisted of dividing out tasks and creating the shaking and throwing mechanic. Throughout my short time developing, I went through multiple iterations of the throwing mechanic. Cleaning it up to make a satisfying game mechanic.

## In-Depth: Shaking and Throwing

![Schrodinger's Image](img/SchrodingersDeliveryService.gif)

Since shaking and throwing were our core mechanics, I wanted to make sure they felt as good as possible. I started by implementing the box's click-and-drag, allowing the player to move it around the screen. I also attached it to a unity spring joint to handle moving it back to the center, but after many issues with it, I ended up scrapping it and having it slowly move back to the middle. For the throwing, I handled the choice between throwing the box at the door and throwing it away based on the box's velocity.

Moving the box quickly around the screen would activate the shaking. If there was a cat, you would hear a sound. If not, it was safe to throw away. After the box was tossed either way, I made the next box, chosen at random from a set of boxes our artists made, move to the center of the screen and have a random chance of having a cat. Once all of that was comeplete, I hooked the function for throwing the box to the door to the function to move the car forward to the next house.

---

**Artists:**
[Jason Richter](https://www.linkedin.com/in/jason-t-richter/) |
[Coleman Fitzgerald](https://www.linkedin.com/in/coleman-fitzgerald-03b828271/) |
[Even Donahue](https://www.linkedin.com/in/evandonahue77/) 


**Designers:**
[Grace Gardella](https://www.linkedin.com/in/gracegardella/) |
[Max Schroeder](https://www.linkedin.com/in/max-schroeder-972b112b5/) |
[Alec Turgeon](https://www.linkedin.com/in/alec-turgeon/) |
[Elliot Mornewick](https://www.linkedin.com/in/elliot-morneweck-11742b29a/)
