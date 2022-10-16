---
title: "Distributed messaging system and storage for IoT-Edge"
---

1. Developed a distributed messaging framework (in Golang) for computer vision applications at the Edge that achieved 10.1x end-to-end latency improvement over the state of the art messaging systems.
1. The messaging framework has a microservices based Publish-Subscribe architecture that enables communication through simple APIs.
1. The messaging system also incorporates a network latency controller that dynamically adjusts the video frame quality to satisfy latency, and application accuracy requirements.
1. To achieve low latency read-write operations, the messaging framework implements an in-memory distributed storage (written in Golang) uniquely tailored for computer vision applications deployed on resource constraint IoT embedded nodes.
