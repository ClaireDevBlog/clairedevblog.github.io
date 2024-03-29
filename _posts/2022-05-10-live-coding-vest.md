The goal of this project is to create an interctive fashion piece - a clothing that you can wear, as well as play with it. My idea is to design a "vest" that can be live coded to generate some cool effects in AR. 

## Vest Design

Below are some of images of the prototype design:

<img src="https://i.imgur.com/g6yIqaG.jpg" style="zoom:20%;" />

There are markers attached to the front and back of the vest. In the AR environment, all the markers will become dynamic visual effects that can be live coded like the picture below. And different markers will represent different visual effects:

<img src="https://i.imgur.com/MJyccRo.png" style="zoom:20%;" />



## Prototype

I used some black and white cloth pieces to create the prototype for the vest. All the markers are stick to the vest with double-sided tape. Below are what the it looks like:

<img src="https://i.imgur.com/c7LpSpO.jpg" style="zoom:35%;" />

<img src="https://i.imgur.com/i4ooYko.jpg" style="zoom:35%;" />



To test the feasibility, I wrote some simple planes in different colors with three.js library and implement the objects in AR using minder.js library. To have better render effect, I adjust the size and position of the markers and it finally looks like this in AR:

<img src="https://i.imgur.com/7MnrMP2.png" style="zoom:30%;" />

<img src="https://i.imgur.com/RaB551D.png" style="zoom:30%;" />



## Live Coding Implementation

I created a web application to enable coders to live code the visual effects with three.js and can assign different visual effects to different markers. The code can be parsed and executed in real-time by pressing “ctrl+enter” on the keyboard:

![](https://i.imgur.com/TB4NwUB.png)

[Video>>](https://www.youtube.com/watch?v=3ZzPstpYdCU)



The system is designed inspired by [gibber](https://gibber.cc/alpha/playground/). The application is developed based on HTML and javascript. [Mindar.js](https://hiukim.github.io/mind-ar-js-doc/) library is used for the tracking in AR and the 3d objects are rendered based on [three.js](https://threejs.org/). I also used the [codemirror](https://codemirror.net/) to implement the code editor in the browser. Code can be found [here](https://github.com/yichenlilyc/ARFashion).