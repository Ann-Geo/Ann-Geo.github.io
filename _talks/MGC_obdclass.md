---
title: "Lustre MGC and Obdclass Deep Dive"
collection: talks
type: "Tutorial"
permalink: /talks/MGC_obdclass
venue: "Lustre User Group (LUG) Conference 2022 by OpenSFS"
date: 2022-05-09
location: "USA"
---

[Presentation](https://wiki.lustre.org/images/6/68/Anjus_George_LUG2022_tutorial.pdf)

1. The talk covers the two core subsystems in Lustre - MGC and Obdclass
1. MGC subtopics include - Introduction to MGC, MGC module initialization and obd operations, workflow of mgc_setup and its operation, Lustre log handing along with other mgc operations such as precleanup, cleanup and import event.
1. ObdClass subtopics include - obd_device structure, MGC lifecycle and its various stages, different stages in obd device lifecycle such as class_attach, class_export and cleanup, description on imports and exports and some useful APIs in obdclass.
