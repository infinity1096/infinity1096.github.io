---
title: "XIMU - compact localization sensor bundle & ROS processing"
excerpt: "<div class='image-container'>
  <img src='/images/projects/XIMU_assembled_square.jpg' alt='XIMU sensor board' class='resizable-image'>
  <div class='image-description'>
    <p> This module is designed for localization need of my club Yonder Dynamics. I designed a compact PCB that holds IMU, pressure sensor, GPS, and magnetometer and communicates all information to ROS network through a ported rosserial package. I also learned to use ESKF to fuse all information. </p>
  </div>
</div>

"
collection: personal_projects
---

This module is designed for localization need of my club Yonder Dynamics. I designed a compact PCB that holds IMU, pressure sensor, GPS, and magnetometer and communicates all information to ROS network through a ported rosserial package. I also learned to use ESKF to fuse all information.

## Module
Github link: [link](https://github.com/infinity1096/XIMU)

<img src='/images/projects/XIMU_assembled.jpg'>
<img src='/images/projects/XIMU_information_flow.jpg'>

## Processing
I learned to use ESKF to fuse all information. Below is my processing algorithm ran on utbm dataset for validation.
<img src='/images/projects/ESKF.png'>

