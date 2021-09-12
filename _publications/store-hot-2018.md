---
title: "An Edge Datastore Architecture For Latency-Critical Distributed Machine Vision Applications"
collection: publications
permalink: /publication/store-hot-2018
excerpt: 'Arun Ravindran, Anjus George'
date: 2018-07-10
venue: 'USENIX HotEdge'

paperurl: 'https://link.springer.com/chapter/10.1007/978-3-030-76063-2_20'
---
Machine vision applications at the IoT Edge have bandwdith and latency constraints due to large sizes of video data. In this paper we propose approximate computing, that trades off inference accuracy with video frame size, as a potential solution. We present a number of low compute overhead video frame modifications that can reduce the video frame size, while achieving acceptable levels of inference accuracy. We present, a heuristic based design space pruning, and a Categorical boost based machine learning model as two approaches to achieve scalable performance in determining the appropriate video frame modifications that satisfy design constraints. Experimental results on an object detection application on the Microsoft COCO 2017 data set, indicates that proposed methods were able to reduce the video frame size by upto 71.3% while achieving an inference accuracy of 80.9% of that of the unmodified video frames. The machine learning model has a high training cost, but has a lower inference time, and is scalable and flexible compared to the heuristic design space pruning algorithm.
