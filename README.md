# Hello World

Hi, I'm Carmen and I like to code. I like it enough that I like helping everyone who's got even the faintest inclination towards learning to code, as best as I can.

This repository is going to host the code I've written for events where I've taught coding. You'll have generative art ideas, text & typography play, physical computing, and web design. Even if you're coming from absolute baseline - you haven't even written your first "Hello World" code - you can use the resources here to build up your skills. I want you to learn something cool and run with it. 

### Mission

My goal is to provide resources and information that is always free to use. Learning is a right, and especially if you're learning through the library system, every resources made available to you shouldn't be paywalled. I will aim to list costs or stipulations should they be relevant, but overwhelmingly, I want to focus on providing free content for all.

### Table of Contents
[Circuit Playground](https://github.com/varsvisualizes/creative-coding-classes#circuit-playground)
[Creative Coding Club](https://github.com/varsvisualizes/creative-coding-classes#creative-coding-club)
[NaNoWriMo Prompt Generator](https://github.com/varsvisualizes/creative-coding-classes#nanowrimo-prompt-generator)
[Web Design 101](https://github.com/varsvisualizes/creative-coding-classes#web-design-101)
[Resources](https://github.com/varsvisualizes/creative-coding-classes)


# Circuit Playground
In 2022, I borrowed 4 Circuit Playground Bluefruits through SEFLIN. I ran a couple of physical computing programs during the summer, teaching the kids how to use CircuitPython. I think I also ran one session teaching Arduino.

I've also used the Circuit Playground for outreach - see more at [the Prizewheel repo](https://github.com/varsvisualizes/circuitplayground-prizewheel).

For libraries looking to access the Circuit Playgrounds, please get in touch with SEFLIN regarding their use. Let them know that the last time they were used was at the Acreage Branch Library.

If you want to purchase one for your own hobby practice, you can find them through Adafruit! I personally have used the Classic and Bluefruit, but not the Express--though seemingly, the majority of tutorials are tailored to the Express, so do what you will there. Make sure you have a USB-MicroB cable to connect the Circuit Playground to your computer.

# Creative Coding Club
Since 2023 I've hosted programs for kids and teenagers teaching them how to use p5.js. I decided to use p5.js because I wanted to give kids a chance at coding beyond a block editor like Scratch or MakeCode - let them really get their hands wet! Plus, p5.js is intentionally designed for creatives who are perhaps beginners at programming, so the code is more intuitive to follow for early coders.

I set up laptop computers with the [p5.js editor](https://editor.p5js.org/) from the webpage opened, plus the [documentation page](https://p5js.org/reference/) for easy reference. The kids sit at the laptops and type along with my code, which I have projected on a large TV screen. Sometimes I'll also have the fully-formed code printed out for them to read, if they want to skip ahead of where I am in the class.

In this repo I have sample codes that I'd present to the class. We would follow some or all of one example, depending on how quickly we were getting through material. Some of the examples are more complicated than what I would teach, but more made to show the kids what's possible. To run the codes yourself, simply copy & paste the script into the p5.js editor. Delete any of the template stuff that's already there (the empty 'setup' and 'draw' functions) and paste the code in the file.

### December 2020: Snowman Animation

Before the creative coding club, there were one-off coding classes. My very first one was hosted virtually, and it was an animated snowman. You can wave his arm using your mouse.

### September 2023: Generative Art

The first in-person creative coding club, as it's known today. I took inspiration from 5 artists and created interactive art based on their geometric styles, with an explanation on how digital artwork can be generative. This is best seen with the Bridget Riley works.

### December 2023: Fractals

More snow-themed work: using snowflakes, the kids learned about fractals in mathematics in nature. This code also incentivized learning how changing paramters changed the shape, so there was plenty of room for experimentation. 

### January 2024: Computer Vision

This session used the ml5 library in combination with p5.js. I using a few [CodingTrain videos](https://www.youtube.com/watch?v=h8tk0hmWB44&list=PLRqwX-V7Uu6aG2RJHErXKSWFDXU4qo_ro) to understand PoseNet, plus [documentation from their page](https://learn.ml5js.org/#/reference/posenet) and [examining Maya Mann's samples](https://googlecreativelab.github.io/posenet-sketchbook/). 

### February 2024: Text-to-Speech
### March 2024: DIY Controller
### April 2024: Poetry Generator

# NaNoWriMo Prompt Generator
For NaNoWriMo 2022, I ran a virtual workshop walking attendees through creating a prompt generator. My prototype used lines from musicals I was obsessed with at the time. (and still today, honestly, but at this very moment I've chilled out the slightest bit)

At this time, I was using OpenProcessing as the editor. It's also free, but I don't get the same side-by-side viewing as I do with the native p5.js editor. The upside is that it automatically fills up the full page, which is a nice effect, I think.

# Web Design 101
In March 2024 I hosted my first in-person coding class for adults. The aim was to create a 1-paged website, drawing inspiration from [freeCodeCamp's Responsive Web Design course](https://www.freecodecamp.org/learn/2022/responsive-web-design/). You can see [my sample webpage here](https://varsvisualizes.github.io/mr-whiskers/).

Full disclosure: I majorly overshot what could be accomplished in an hour. Our webpages really turned out something like this: (picture to come, lol)

Initially, I felt disappointed that I couldn't help my class achieve the full vision I'd had in mind. However, for the attendees, it was - for the most part - their true first time coding anything, ever. That alone makes the outcome wildly special. They've jumped the hurdle of not knowing anything: now they know they can learn to code, because they've got the proof. My hope is that they will continue to grow and make even cooler things in the future.

# Resources

## Circuit Playground

NOTE: As of late 2023, something's been up with CircuitPython burning onto the Circuit Playgrounds. The bootloader itself is messed up - the forums were all in a fuss about it, and I couldn't get any of the CircuitPlaygrounds running using Circuit Python. It drove me bananas for a solid 8 hours. Hopefully by the time you get your hands on a Circuit Playground, should you decide to try CircuitPython, the issue will be resolved. If not, good old Arduino is there for you.

* Hardware & Software
  * [Purchasing through Adafruit](https://www.adafruit.com/product/3333) (you can also use Digi-Key, Sparkfun, even Amazon)
  * [Setting Up CircuitPython](https://learn.adafruit.com/adafruit-circuit-playground-bluefruit/overview)
  * [Setting Up Arduino](https://learn.adafruit.com/introducing-circuit-playground/arduino)
* Learning Resources
  * The Arduino's Circuit Playground library will come with examples to try, so definitely explore those
  * [Tutorial ideas from Adafruit's page](https://learn.adafruit.com/category/bluefruit)
  * [John Gallagher's Circuit Python school](https://www.youtube.com/playlist?list=PL9VJ9OpT-IPSsQUWqQcNrVJqy4LhBjPX2)

Check out this handy PDF I created for reference!

## p5.js 
* [p5.js](https://p5js.org/)
* CodingTrain videos
  * [Nature of Code 2 playlist](https://thecodingtrain.com/tracks/the-nature-of-code-2)
  * [General YouTube channel](https://www.youtube.com/@TheCodingTrain)
* [HappyCoding tutorials](https://happycoding.io/tutorials/p5js/)

## Processing
* [Processing](https://processing.org/)
* [CodingTrain videos](https://www.youtube.com/watch?v=2VLaIr5Ckbs&list=PLRqwX-V7Uu6ZYJC7L-r6rX6utt6wwJCyi)
* ["The Nature of Code" by Daniel Shiffman](https://natureofcode.com/)
* [HappyCoding tutorials](https://happycoding.io/tutorials/processing/)

## Web Design & Front-End Development

* Learning
  * Udemy
    * Free with a library card
  * CodeAcademy
   * Listed in the library's resource page, but much of the content is paywalled - I'm not sure if a library account is available for this site
  * freeCodeCamp
* Doing
  * [VS Code Text Editor](https://code.visualstudio.com/)
    * I download this software so I can use the Live Server extension - that way I can see my work as I update it!
  * [CodePen](https://codepen.io/)

 ## Miscellanea

 You've made it this far. Here are some things I just think are neat.

 * [sadgrl.online personal webpage things](https://goblin-heart.net/sadgrl/projects/)
 * [JavaScript Neko pet](https://webneko.net/)
 * Circuit Playground Express + Crochet Skills = [DIY DDR Mat](https://www.youtube.com/shorts/4NJ3nWqSJL4)
 * The Arduino Uno tutorials I followed to get started in physical computing
 * [Maya Mann](https://www.mayaontheinter.net/), because I kind of love her
 * [Tigris Li](https://tigris.li/Work), with whom I am also obsessed
 * [Simone Giertz](https://www.simonegiertz.com/), the roboticist who really started it all for me
 * [Wearable robotics](https://urbanarmor.org/)