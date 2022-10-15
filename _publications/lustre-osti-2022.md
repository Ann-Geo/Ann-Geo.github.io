---
title: "Understanding Lustre Internals Second Edition"
collection: publications
permalink: /publication/lustre-osti-2022
excerpt: 'Anjus George, Rick Mohr, James Simmons, Sarp Oral'
date: 2022-09-14
venue: 'DOE OSTI'

paperurl: 'https://www.osti.gov/biblio/1824954'
---
The Lustre file system has become a preferred storage resource for systems on the Top500 list, and it is often the file system of choice for small- to medium-sized HPC systems that require parallel shared access to data. Several resources exist to help users deploy and configure Lustre, but the same cannot be said for resources that explain the inner workings of the Lustre source code. A previous ORNL technical report entitled "Understanding Lustre Filesystem Internals" (ORNL/TM-2009/117) provided an excellent summary of Lustre subsystem operations. However, that report is over a decade old and is based on Lustre version 1.6. Since that report was published, Lustre has evolved significantly. Several subsystems underwent significant code changes and many new features have been added to the file system, bringing the current Lustre version up to 2.15.This report aims to document and explain the internal workings of the latest version of the Lustre file system. It will provide more complete and up-to-date information than the previous technical report and should serve as a foundational document for anyone interested in Lustre software development. Key data structures will be described along with the APIs used for interaction among the various Lustre subsystems. Although the Lustre software is constantly being developed, the details in this document should remain relevant for the forseeable future.
