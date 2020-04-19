---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

Some of my representative projects are highlighted below.

* **Enabling On-Demand Personalization in Connected Cars** ([US Patent](https://patents.google.com/patent/US10129767B2/))<br>
  This project designs a connected car framework to enable on-demand personalization for each seat. It identifies and localizes a user based on her mobile device and signals received from pre-installed Bluetooth beacons. In particular, the proposed framework features a SVM-based in-car location engine, which robustly extracts signal fingerprints and distinguishes between seats under various dynamics. To support on-demand usages, a cloud platform is implemented in [Parse](http://parseplatform.org/) to store each car's seat prediction model and each user's personalization profile.<br><br>
  ![]({{ base_path }}/images/blueid.jpg){:width="500px"}

* **Samba: An Energy-Efficient Platform for Aquatic Environment Monitoring** ([IPSN'15](https://drive.google.com/file/d/1iZZJgOqOlWQAts6525Zv0SPOK5tcPlP6), [TOSN](https://drive.google.com/file/d/1byQ8PooJikYa4Ot8YiYQ9atfzcgDOliP))<br>
  Samba is a mobile sensing platform that integrates an Android device with a robotic fish for aquatic environment monitoring. A key feature of Samba is leveraging motion sensors to assist computer vision tasks. Specifically, through online learning and updating mapping models between inertial and visual features, Samba estimates the target visual features based on real-time motion sensor readings, thus avoiding the compute-intensive computer vision algorithms. According to the experiments, it reduces the per frame computation overhead by over 97%.<br><br>
  ![]({{ base_path }}/images/samba.jpg){:width="660"}

* **SOAR: A Smartphone-Based System for Floating Object Detection** ([IPSN'14](https://drive.google.com/file/d/1BaazCz9iL6bVFr_PSVdd6-mD-LFZJvI4), [TMC](https://drive.google.com/file/d/1yXbnTRNxek2wRLXirEOz7Q1XccScBLFP))<br>
  SOAR is a vision-based, cloud-enabled, and intelligent robotic system for floating object detection and recognition. In particular, SOAR implements a lightweight and robust computer vision algorithm pipeline to address the unique challenges in aquatic environment, e.g., camera shaking caused by waves and highly variable luminance. Moreover, SOAR features a cloud offloading scheme, which dynamically allocates the computer vision tasks between cloud computing and local processing to save system energy.<br><br>
  ![]({{ base_path }}/images/soar.jpg){:width="500px"}

* **Spatiotemporal Process Reconstruction Using Robot Swarms** ([RTSS'12](https://drive.google.com/file/d/1eoGvNX5292trnudLo8EFVY-YfMx4Fa5g), [TOSN](https://drive.google.com/file/d/1n8LqAxQFjAInBF3Z-5hfPL_cZLial2xM))<br>
  This project explores spatiotemporal process reconstruction using robot swarms. The proposed approach features a rendezvous-based mobility control scheme, where robots collaborate in the form of swarm and sense the environment in a series of rendezvous regions. The position of each rendezvous region is selected by an objective function driven by [mutual information](http://en.wikipedia.org/wiki/Mutual_information) to maximize information gain, and the size is adjusted to maintain wireless connectivity of the robot swarm through a feedback control loop.<br><br>
  ![]({{ base_path }}/images/recon.jpg){:width="500px"}

<p align="center">&mdash; <strong>build apps that matter</strong> &mdash;</p>