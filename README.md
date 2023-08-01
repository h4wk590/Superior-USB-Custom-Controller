# Superior-USB-Custom-Controller

The Succ is a USB switch board powered by the TEENSY Arduino 3.2. It's for users looking to get into flight simulator 
games without forking out $$$ for more advanced equipment.

This was a university project from my Project Management class. 

**The main goals were:**

- To understand how Sprints work within a technology setting as a Project Manager

- To enhance collaborative abilities with a group of people to meet a due date

- To build a bomb-ass USB controller, and learn some new skills along the way

## Design

The first steps we took in this project were:

- What type of micro-controller we were going to use?

- What the end design would look like?

- How it would be wired together?

![alt text](https://github.com/h4wk590/Superior-USB-Custom-Controller/blob/master/SUCC/img/diagram_SUCC.jpg)

**This was the very first whiteboard design of how the wiring would look** (notice how we left the digital side out of the breadboard - *it wasn't in our scope*)

![alt text](https://github.com/h4wk590/Superior-USB-Custom-Controller/blob/master/SUCC/img/early_design_SUCC.jpg)

**Template we would be using for the placement of buttons and switches**

## Prototype


After we got all of the gear we needed, (Breadboard, Microcontroller, wires, switches, and buttons) we put it all together inside of 
styrofoam from some random monitor boxes. It made a nice unit for testing out the program & button mapping. 

![alt text](https://github.com/h4wk590/Superior-USB-Custom-Controller/blob/master/SUCC/img/proto_SUCC6.jpg)

We used this make-shift styrofoam, party because it was effective, but mostly because we didn't want to buy more than one 
plastic base. We also wanted to make sure that we had all the measurements exact before drilling and cutting into the base.



### Skills learned 

- We knew that we would have to solder. It was my first experience soldering, and it turned out I was alright at it -atleast for my first try!

- The wires we bought at our local robotics shop turned out to just be a little too short for the job, so we ended up using cat5 ethernet!

- The Teensy Arduino IDE is C++ based, but the original {Joystick} code was all that we really needed in order for our board to work, besides a slight change to include a delay between actuation of the physical switches & buttons.

![alt text](https://github.com/h4wk590/Superior-USB-Custom-Controller/blob/master/SUCC/img/test_soldering_to_teensy.jpeg)

**Soldering the Teensy to some headers, so it wouldn't move around as interupt the wires signals.**

![alt text](https://github.com/h4wk590/Superior-USB-Custom-Controller/blob/master/SUCC/img/wired_SUCC.jpg)

**The finished soldered cat5 ethernet cables.**


## Final Product

I am really happy the way this project turned out. It's a functional piece of tech that we built with love & some caffiene.

![alt text](https://github.com/h4wk590/Superior-USB-Custom-Controller/blob/master/SUCC/img/finished_SUCC2.jpg)



