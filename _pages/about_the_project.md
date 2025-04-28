---
title: "About the project"
permalink: /about_the_project/
layout: single
author_profile: true
---
## Summary

The ‘VIA-TARIQ’ is an interdisciplinary project that aims to explore key topic among the archaeologists and historians of the Near East: what is the level of persistency/discontinuity of the Roman road system in the _longue durée_ and what influences it had on the social and economic developments in the Medieval and modern period. The project will approach these issues through analysis of large aggregated archaeological datasets and advanced spatial modelling methods, enabled through training in these methods at the host institution. The project aims to add to our understanding of the centuries-long change and development of the road and transport networks in the Levant. It hopes illuminate the long-term effects of the Roman road infrastructure on the economic developments in the Medieval and Ottoman periods.

These issues can be tackled for the first time by **analysing a large, highly detailed digital dataset of the Roman road system** and by **creating a detailed digital representation of the Medieval and Ottoman road and transport network** in the Levant for the first time. By comparing and analysing these datasets it will be possible to come to a better understanding of the diachronic processes and mechanisms of persistency and change of the roads system over centuries. The broad chronological framework will allow us to identify the role of political and economic forces in shaping connectivity, transport, and economic performance in the Levant.

## Research Objectives

**RO 1**: to analyse the characteristics of known Roman roads in the Levant and to generate a set of generalized rules describing spatial characteristics of the road segments (e.g., gradient, preference for topographical position etc.).

**RO 2**: to build a geo-spatial model of the Roman road network in the Levant using GIS based on the results of RO1.

**RO 3**: to create a model of the Medieval to Ottoman Road System Model in the Levant from the 7th to 19th centuries in suitable time-slices.

**RO 4**: diachronic analysis of the historical transport in the Levant, to analyse and compare the datasets resulting from RO 2-3 and to analyse the evolution of the road and transport network in the Levant and its connectivity from the Roman to the Ottoman period; to interpret its changes and socio-economic importance of these changes for the Levant and neighbouring regions including the Mediterranean and Europe.

## Why this research?

In the years 2021-2024 I was part of a project 'MINERVA: Understanding the centuries-long functioning of the Roman economy' with Tom Brughmans at Aarhus University. My role was to digitize available evidence for Roman roads and create digital representation of the Roman road network that would be much more detailed than what was available back then. During the data collection and digitization I started to notice huge discrepancies between various regions when it comes to 'road density' - **some regions have very detailed reconstructions of Roman road system** coming down to second and third order local roads, but **in other places very little is known save for few main roads** known from milestones and ancient itineraries. It made me realize how fragmentary our understanding of the Roman road network really is and that there are huge gaps in our maps. As an archaeologist proficient in GIS, I decided to **approach this problem through computational modelling and network science**.

### Roman roads

In the Roman Near East there are some 3,100 km of Roman roads that are well documented and could be digitized with high spatial accuracy (within few meters of error on the ground). The idea is to identify range of key topographic variables (slope, topographic position index, ruggedness index) on these roads and use this data **to create updated computational model of the Roman road network and try to 'fill the gaps'** in places where little is known or where little research was done on Roman roads.

There are multiple ways how to 'fill the gaps' and I am few different concepts from GIS modelling and network science. The first is notion of **'natural corridors of movement'**, i.e. finding places where movement in landscape is drawn to, typically because of its ease of movement (least-cost path, or LCP analysis). In such a case, we are not concerned with definite places (archaeological sites) as origins and destinations and instead we focus on the landscape and its potential for movement as a whole. The second concept comes from network science and combines **modelling of theoretical networks between archaeological sites and least-cost path analysis (LCP networks)**. In this scenario, road network is modelled with archaeological sites as principal nodes in the network as origin and destination points. The connections between nodes are modelled based on LCP analysis (only the best accessible neighbouring nodes are connected) and theoretical network model (k-nearest neighbours, Gabriel graph, etc.) - e.g., only closest 4 neighbouring sites are connected to site A etc. and from this rule the whole network is reconstructed. In both cases, the resulting network must be validated by additional archaeological or cartographic sources.

![Map of Roman roads digitized with very high spatial accuracy in the Levant.](/assets/images/road_2.png)
<figcaption>Map of Roman roads digitized with very high spatial accuracy in the Levant.</figcaption>

### Medieval and Ottoman roads

When I was doing bibliographical survey for my data collection on Roman roads, quite often I encountered statements such as 'the Roman road was here because there was also a Medieval road' or 'the Roman road was abandoned in the Medieval period'. It made me start to think about couple of things: the first is methodological problem . Evidence for Roman use of a road is often used to postulate continuity into Medieval period, and vice versa, evidence from Medieval period is often extrapolated into the Roman past. This might result in a circular argument in certain cases. In order to disentangle this issue and to analyse the persistency/non-persistency of Roman roads into later periods one needs **a digital representation of the Medieval and Ottoman road network**. Such resource is until now, surprisingly, lacking ([ath-Thurayya Project](https://althurayya.github.io/) comes closest to that, but it is not exactly that). As it was the case with the Roman roads, the **data on Medieval and Ottoman road stations (khans), bridges, fords, roads and other archaeological proxies** are available. Moreover, there is plethora of **Medieval and Ottoman written sources** on road netwroks, itineraries and post systems that can be used to reconstruct the road network and create its digital model. Once this resource is available it is possible to study the long-term development of transport networks in the Levant.

![Crossroad of a Roman road with another (later Medieval?) road in the Golan.](/assets/images/road_1.png)
<figcaption>Crossroad of a Roman road with another (later Medieval?) road in the Golan.</figcaption>