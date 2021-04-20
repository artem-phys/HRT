# HRT
Solution of Hospital/Resident Problem with Ties

Problem instance:
An instance of the classical Hospitals/Residents problem (HR) with Ties involves two
sets, a set R of residents and a set H of hospitals. Each resident in R seeks to be
assigned to exactly one hospital, and each hospital h ∈ H has a specified number
ph of posts, referred to as its quota. Each resident ranks a subset of H in non-strict (oppositely to classic HR instance)
order of preference, and each hospital ranks, again in non-strict order, those residents
who have ranked it.

Several types of matching's stability appears when extending classic HR to HRT. Strong stable matchings are considered here.

More: https://en.wikipedia.org/wiki/National_Resident_Matching_Program#Matching_algorithm


This repository implements the algorithm from the following article:
Irving, Robert & Manlove, David & Scott, Sandy. (2003). Strong Stability in the Hospitals/Residents Problem. 10.1007/3-540-36494-3_39. 


