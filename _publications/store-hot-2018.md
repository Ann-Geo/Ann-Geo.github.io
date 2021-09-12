---
title: "An Edge Datastore Architecture For Latency-Critical Distributed Machine Vision Applications"
collection: publications
permalink: /publication/store-hot-2018
excerpt: 'Arun Ravindran, Anjus George'
date: 2018-07-10
venue: 'USENIX HotEdge'

paperurl: 'https://www.usenix.org/system/files/conference/hotedge18/hotedge18-papers-ravindran.pdf'
---
Multi-camera real-time vision at the Edge is facilitated by low-latency distributed data stores. In this paper, we take the position that latency criticality in the challenging operating conditions at the Edge can only be attained through application specific designs incorporating autonomous computing techniques. In our initial prototype, we implement a key-value Edge data store that autonomously monitors run-time conditions to maintain latency-criticality of one class of data (feature vectors), while sacrificing the latency and accuracy of another class of data (keyframes). Early results show a median latency improvement of 84.8% over non-autonomous operation, for videos with large scene dynamics, and operational conditions of intermittent wireless channel interference.
