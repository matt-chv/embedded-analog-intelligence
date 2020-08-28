# Sensor Fusion Before getting started

![](../static/img/maze_with_help_grey.png)

> Are you lost, not sure where to start let alone where to go?
Why ? Wieso ? Pourquoi ? 为什么?


Notes: Make it clear this is for those who think they need sensor fusion but not sure why, nor what it is let alone how to make it work
We will try in the next 20mn to answer those questions.
* Why would you need sensor fusion
* What is sensor fusion
* How can you get your first PoC and secure a path to production

---

## Why is everyone talking about sensor fusion

> Sensor fusion is a key set of technologies for autonomous vehicles

| self driving cars | self landing planes |  self driving robots |
|-------------------|---------------------|----------------------|
| ![][driverless]        | ![][Airbus]         |   ![][wheeled]       |

[driverless]: https://thumbs.gfycat.com/HairyMeatyCranefly-max-1mb.gif
[Airbus]:https://omyplane.com/wp-content/uploads/2020/07/sszaih1uyh4maxresdefault-1280x400.jpg
[wheeled]:https://media1.giphy.com/media/MsghJNDA0Od2w/source.gif

----

<!-- .slide: data-background-iframe="https://books.google.com/ngrams/graph?content=sensor+fusion&year_start=1980&year_end=2019&corpus=26&smoothing=3" data-background-interactive-->

## But do they talk about it ?

1. This is a perfect illustration of the hype cycle of sensor fusion.
2. The peak of inflated expectations was in the 90's then came the through of desillusion
3. we are now clearly climing on the plateau of productivity

----

## Who talks about it?



---

## What is Sensor Fusion 

> Leaning to ride a bike is often the human first sensor fusion experience 

----

### Sensor Fusion: the 3 C's of fusion

* Competitive: dual channel approach ( 2 overlaping cameras) <!-- .element: class="fragment" data-fragment-index="1" -->
* Complementary: appending overlapping sensor data (e.g. front and rear camera) <!-- .element: class="fragment" data-fragment-index="2" -->
* Cooperative: complemntary to add more incormation (2 cameras to enable stereoscopic views) <!-- .element: class="fragment" data-fragment-index="3" -->

Notes: Remmeber to say something funny here: 3C of F has nothing to do with the 3 coins in the fountain from Sinatra (1954 movie)

----

### Sensor Fusion: the 5 Levels of fusion

0. Data alignment <!-- .element: class="fragment" data-fragment-index="1" -->
1. Entity assessment (e.g. signal/feature/object). <!-- .element: class="fragment" data-fragment-index="2" -->
2. Tracking and object detection/recognition/identification <!-- .element: class="fragment" data-fragment-index="3" -->
3. Situation assessment <!-- .element: class="fragment" data-fragment-index="4" -->
4. Impact assessment <!-- .element: class="fragment" data-fragment-index="5" -->
5. Process refinement (i.e. sensor management) <!-- .element: class="fragment" data-fragment-index="6" -->
6. User refinement <!-- .element: class="fragment" data-fragment-index="7" -->

---

### How: ROS first

<ul>
   <span class="fragment"><li> 2007 *real* start to avoid constant re-inventing the wheel </li></span>
   <span class="fragment"><li> 2012 <a href="https://rosindustrial.org/briefhistory">ROS-I</a> github launched </li></span>
   <span class="fragment"><li> 2017 <a href="https://index.ros.org/doc/ros2/Releases/">ROS2<a/>, 
      <span class="fragment"><small><a href="https://www.generationrobots.com/blog/en/ros-vs-ros2/">1v2,</a></small></span>
       <span class="fragment"> <small><a href="https://design.ros2.org/articles/why_ros2.html">why</a></small></small> </li>
</ul>
<iframe data-src="https://www.theconstructsim.com/timeline-robot-operating-system-ros/" width="800" height="600" frameborder="0" marginwidth="0" marginheight="0" scrolling="yes" style="border:3px solid #666; margin-bottom:5px; max-width: 100%;" allowfullscreen> </iframe>

Notes: What is ROS, let's do a little look back in the future of robotics. We can also have a look at the official ROS timeline in this small iframe

---

<!-- .slide: data-background-iframe="https://wiki.ros.org/ainstein_radar/Tutorials/Radar%20and%20camera%20sensor%20fusion" data-background-interactive-->

<div style="position: absolute; width: 40%; right: 0; box-shadow: 0 1px 4px rgba(0,0,0,0.5), 0 5px 25px rgba(0,0,0,0.2); background-color: rgba(0, 0, 0, 0.9); color: #fff; padding: 20px; font-size: 20px; text-align: left;">
    <h2>mmWave and vision fusion in ROS </h2>
  <ul> 
    <li> Why re-invent the wheel? </li></span>
    <span class="fragment"><li> When demo already on ROS tutorial </li></span>
    <span class="fragment"><li> Well because TI mmwave has many more built-in features making fusion stronger and faster </li></span>
    <span class="fragment"><li> and because next step is to do fusion with industrial cameras with  </li></span>
  </ul>
</div>

---
