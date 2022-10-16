---
title: "QuickSilver: A Distributed Policy Driven Data Management System"
collection: talks
type: "Talk"
permalink: /talks/quicksilver
venue: "Women in HPC workshop at Supercomputing 2022 conference"
date: 2022-11-13
location: "Dallas, TX, USA"
---

Large scale parallel file systems with multiple storage tiers require policy driven data management to facilitate efficient storage and access of large-scale data. However, management of data across the tiers is challenging due to the massive scale of data being stored. In this talk, we present our initial work on QuickSilver, a light-weight flexible distributed policy engine. QuickSilver is composed of many single-purpose agents that handle tasks such as gathering file metadata, enforcing policy decisions, and executing policy actions like purging or data migration. These agents are designed to communicate using distributed message queues, allowing the number of individual agents to be scaled up as needed. Additionally, QuickSilver is designed to function while maintaining minimal state information. We will discuss the architectural details of the policy engine and its use of message queues to enable scaling.  Examples of the initial implementation will be shown along with preliminary performance numbers. Since this project is in its infancy, we will also discuss our plans for future work and areas of improvement.
