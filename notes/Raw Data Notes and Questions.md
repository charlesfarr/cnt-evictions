# Raw Data: Questions / Notes
**Author:** Charles Farr
**Date:** 3/21/20

## H+T Affordability Index
- What does the CBSA col represent? How does this map to an MSA?
- What are the various H+T specific columns? ht_ami, ht_80ami, ht_nmi, + h_ and t_ only cols?
- What are the hh_gravity, frac_sfd, emp_gravity, emp_ndx cols?
- How is the actual index normalized / calculated? What columns contains this? Will we need to analyze multiple columns?
- **Necessary** to clean cbsa (col) and blkgrp (col) to remove the quotation marks

## General
- How can we identify the MSAs we're interested in? How can we split suburban and urban areas apart (e.g., Chicago versus metro-Chicago?)
- Look up how block groups are serialized - looks to be a 12 digit identification number
- Will need a standardized mapping of block groups to other levels or geographic data (neighborhood, MSA, county, etc.)

## Evictions Data
- Is the GEOID (col) an Evictions Lab specific ID or a more standardized identifier?
- Is the parent-location (col) always the county?
- In the block group file, is the GEOID the blockgroup ID?