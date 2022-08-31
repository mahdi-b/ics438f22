---
title: "Amazon Redshift and Aurora"
published: true
morea_id: experience-oltp-olap
morea_type: experience
morea_summary: "Understanding Aamzon OLTP and OLAP offerings"
morea_sort_order: 1
morea_labels:
---



The nyc.gov site provides, among other things, the data of  yellow and green taxi trip records. The  data includes fields capturing pick-up and drop-off dates/times, pick-up and drop-off locations, trip distances, itemized fares, rate types, payment types, and driver-reported passenger counts.

Donwnload the Yellow Taxi Trip Records for June 2022. 

Use the pyarrow library to read the parquet file. Answer the following: 

* How many records does the file contain?
* What the time of the first and the last observations?
* What payment tyeps values are there?
* Why are values in each column stored in sub-lists?