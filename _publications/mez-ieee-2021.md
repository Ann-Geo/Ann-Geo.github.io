---
title: "Mez: An Adaptive Messaging System for Latency-Sensitive Multi-Camera Machine Vision at the IoT Edge"
collection: publications
permalink: /publication/mez-ieee-2021
excerpt: 'Anjus George, Arun Ravindran, Matías Mendieta, Hamed Tabkhi'
date: 2021-01-02
venue: 'IEEE Access'

paperurl: 'https://ieeexplore.ieee.org/abstract/document/9343251'
---
Mez is a novel publish-subscribe messaging system for latency sensitive multi-camera machine vision applications at the IoT Edge. The unlicensed wireless communication in IoT Edge systems are characterized by large latency variations due to intermittent channel interference. To achieve user specified latency in the presence of wireless channel interference, Mez takes advantage of the ability of machine vision applications to temporarily tolerate lower quality video frames if overall application accuracy is not too adversely affected. Control knobs that involve lossy image transformation techniques that modify the frame size, and thereby the video frame transfer latency, are identified. Mez implements a network latency feedback controller that adapts to channel conditions by dynamically adjusting the video frame quality using the image transformation control knobs, so as to simultaneously satisfy latency and application accuracy requirements. Additionally, Mez uses an application domain specific design of the storage layer to provide low latency operations. Experimental evaluation on an IoT Edge testbed with a pedestrian detection machine vision application indicates that Mez is able to tolerate latency variations of up to 10x with a worst-case reduction of 4.2% of the application accuracy F1 score metric. The performance of Mez is also experimentally evaluated against state-of-the-art low latency NATS messaging system.

