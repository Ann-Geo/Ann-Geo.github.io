---
title: "Understanding Lustre File System Internals – A Documentation Initiative"
collection: talks
type: "Talk"
permalink: /talks/Lustre_docu
venue: "Lustre User Group (LUG) Conference 2022 by OpenSFS"
date: 2022-05-10
location: "USA"
---

[Presetantion](https://www.youtube.com/watch?v=OQuCG1Vjs0s)

The Lustre file system has become a preferred storage resource for systems on the Top500 list, and it is often the file system of choice for small- to medium-sized HPC systems that require parallel shared access to data. Several resources exist to help users deploy and configure Lustre, but the same cannot be said for resources that explain the inner workings of the Lustre source code. A previous ORNL technical report entitled “Understanding Lustre Filesystem Internals” (ORNL/TM-2009/117) provided an excellent summary of Lustre subsystem operations. However, that report is over a decade old and is based on Lustre version 1.6. Since that report was published, Lustre has evolved significantly. Several subsystems underwent significant code changes and many new features have been added to the file system, bringing the current Lustre version up to 2.15.  

In this presentation I describe the efforts taken to develop a comprehensive documentation of internal mechanics of the latest version of Lustre file system. The documentation is hosted in the main community repository for Lustre, wiki.lustre.org under the title “Understanding Lustre Internals”. Pivotal sections and subtopics in the documentation are Lustre architecture featuring its core components, software stack and file layouts, Lustre test suite, user utilities and core subsystems including MGC, Obdclass, Libcfs and File identifiers. In this talk, I first outline the limitations of the existing resources, then the methodology followed to focus on writing key data structures and APIs, and lastly exhibit the new documentation page hosted in wiki.lustre.org. Through this talk, I seek to encourage contributions from the Lustre community to extend the documentation further with relevant contents and keep it up to date with Lustre source code changes. 
