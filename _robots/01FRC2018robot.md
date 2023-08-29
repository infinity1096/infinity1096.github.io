---
title: "2018 FRC robot"
excerpt: "<div class='image-container'>
  <img src='/images/robots/2018FRC_square.jpg' alt='robot1' class='resizable-image'>
  <div class='image-description'>
    <p>Our robot for the 2018 FRC competition. It can deliver recycle boxes both to ground entrance and lift them up to around 2 meters and dump into a scale. For the game rule it can also hang itself up with a wrench. In this season I developed and installed a compact odometry module on the vehicle for our autonomous. We made it to world championship!</p>
  </div>
</div>

"
collection: robots
---

## Robot:
Robot in action [FRC TEAM5449 Prototype 2018 Robot Reveal](https://www.bilibili.com/video/BV15W411J7XA/?share_source=copy_web&vd_source=025e24f7ef104c44de4b2abc2633a5f3)

<img src='/images/robots/2018FRC.jpg'>

## Localization Module:
This localization module consists of 3 encoders connected to a free-spinning omni-directional wheel. Omni wheels are important to used to measure rotation along its direction while allowing velocity along its axial. The three linear rails and rubber band allows them to fit uneven ground. I used a Arduino to read encoder pulses with interrupt and integrate the encoder unit increments. This device ensured accurate localization for the autonomous period.

<img src='/images/robots/localization_module.jpg'>

