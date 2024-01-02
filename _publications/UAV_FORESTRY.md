---
title: "UAV for forestry: Metric-Semantic Mapping and Diameter Estimation with Aerial Autonomy"
collection: publications
permalink: /publication/UAV_FORESTRY
excerpt: 
date: Dec, 2023
venue: 'Journal: Mechanical System and Signal Processing'
paperurl: 'http://dx.doi.org/10.2139/ssrn.4518294'
citation: 
---
**Abstract:** To properly monitor the growth of forests and
administer effective methods for their cultivation, forestry re-
searchers require access to quantitative metrics such as diameter
at breast height and stem taper profile of trees. These metrics
are tedious and labor-intensive to measure by hand, especially
at the scale of vast forests with thick undergrowth. Autonomous
mobile robots can help to scale up such operations and provide
an efficient method to capture the data. We present a set of
algorithms for autonomous navigation and fine-grained metric-
semantic mapping with a team of aerial robots in under-canopy
forest environments. Our autonomous UAV system has 3D flight
capabilities and relies only on a LIDAR and an IMU for state
estimation and mapping. This allows each robot to accurately
navigate in challenging forest environments with drastic terrain
changes regardless of illumination conditions. Our deep-learning-
driven fine-grained metric-semantic mapping module is capable
of detecting and extracting detailed information such as the
position, orientation, and stem taper profile of trees. This map
of tree trunks is represented as a set of sparse cylinder models.
Our semantic place recognition module leverages this sparse
representation to efficiently estimate the relative transformation
between multiple robots, and merge their information to build a
globally consistent large-scale map. This ultimately allows us to
scale up operations with multiple robots. Our system is able to
achieve a mean absolute error of 1.45 cm for diameter estimation
and 13.2 cm for relative position estimation between a pair of
robots after place recognition and map merging

[Download paper here](http://dx.doi.org/10.2139/ssrn.4518294)
