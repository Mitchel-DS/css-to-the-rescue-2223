# CSS to the Rescue @cmda-minor-web 2022 - 2023

## Table of contents

- [Description](#description)

## Introduction

During this project it's all about CSS. We have to experiment with new CSS techniques and try to implement them into one of the assignments using only vanilla HTML and CSS. No javascript allowed.

The assignments we could pick from were:
- A modulair controle panel.
- An interactive fireworkshow.
- A 3D rubiks cube.
- Tailwind without Tailwind.

## Live demo

Check out the live demo [here.](https://mitchel-ds.github.io/css-to-the-rescue-2223/eindopdracht/)

## What is this project?

For the assignment I chose the modulair control panel. The idea is to make a MIDI keyboard with different interactive functions that show of these new CSS techniques.

## Week 1 - Concept

Before I got started I had some trouble with coming up with an idea, that could work. I had a few ideas, but I ended up with a MIDI keyboard. I thought it would be a fun project to make and it would be a good challenge to make it interactive.

I started with making a sketch on how I wanted the keyboard to look like and what I wanted to do what. 

![original](/eindopdracht/images/week1/orginal.jpeg "Original")

This is what the original design looked like. I wanted to make something similar, but with interactive functions.

![concept](/eindopdracht/images/week1/concept.png "Concept")

Here you can see the concept sketch I made for it and what I imagined every thing did and what was supposed to happen.

![progress](/eindopdracht/images/week1/progress1_1.png "Progress")

I started with making the design, the keys div and a power button.

### Feedback / insights 

*"Just make a display. Show that the key does something. There are no speakers, so maybe you can make a sound wave for each key."*

- This is something I was planning on doing. In my concept the display only has text, but that's a bit boring.

## Week 2 

Started with making the individual keys. First styled and positioned each div individually. 

Next, I got some feedback from a classmate that I could use flexbox to make the keys positioned next to each other. This was easier and with less code to write.

![progress](/eindopdracht/images/week2/progress2_1.png "Progress week 2_1")

Next, I got the power button to work. It didn't do anything before, but now it turns the display "on", aka it changes color.

![progress](/eindopdracht/images/week2/progress2_2.png "Progress week 2_2")

And then of course the display. For now a 'work in progress' and not positioned in the right place, but just at the bottom for more clarity.

![progress](/eindopdracht/images/week2/progress2_3.png "Progress week 2_3")

## Week 3 - Holiday

During the holiday I tried to get some more things working. Here I changed the styling of the keys, so it looks better when the key is pressed. Made it more realistic.

![progress](/eindopdracht/images/week3/progress3_2.png "Progress week 3_2")

![progress](/eindopdracht/images/week3/progress3_1.png "Progress week 3_1")

Here I got the styling of the display to work when the power is turned on. 

![progress](/eindopdracht/images/week3/progress3_3.png "Progress week 3_3")

## Week 4

Styling of the power button changed. Now it looks more like a real power button.

![progress](/eindopdracht/images/week4/progress4_1.png "Progress week 4_1")
 
If you press a key without power nothing happens.

![progress](/eindopdracht/images/week4/progress4_2.png "Progress week 4_2")

If you turn on the power and press a key, the display turns on and the power button turns red. The power button also keeps blinking while the power is on.

![progress](/eindopdracht/images/week4/progress4_3.png "Progress week 4_3")

![progress](/eindopdracht/images/week4/progress4_4.png "Progress week 4_4")

If you now press a key, an animation will appear on the display. It doesn't do anything weird for now, but it's a start.

![progress](/eindopdracht/images/week4/progress4_5.png "Progress week 4_5")

Pressing anything else doesn't do anything yet.

## Assignment resit

I didn't pass for this assignment at first. So I had to do a resit. I got some feedback from my teacher, which was:

*"You didn't experiment enough with the css techniques. It just isn't enough. There's only one animation that plays when pressing a key. When pressing anything else nothing really happens. Show that you use multiple new techniques. The display screen is basically screaming for you to use it for something like that."*

## Reflection

### Version 1.0 

I underestamated this assignment at first, I thought during my first submission that I experimented enough and did enough research. For me I used a lot of new things and tried to implement them in this project. 

### Version 2.0

## New CSS techniques used

I also made a list of all the CSS techniques I ended up learning more about.

- animation
- has() selector
- :checked

## License

This project is licensed under the MIT License - see the LICENSE.md file for details
