---
layout: page
title: Cloudsort
description: Sorting an image collection by Cloud Coverage for a small area of interest
img: assets/img/clouds.jpg
importance: 3
category: university
related_publications: true
---

Cloudsort was a project we completed in the course Practice Software development in Python. The goal was to create a Jupyter-Notebook, that used google earth engine as well as several other python packages to sort an image collection by cloud coverage for a small area of interest. 

The idea was to solve a problem another member of the group faced, where she wanted a small area of interest to be cloud free, but sorting the overall collection by cloud coverage meant that the area of interest may still be obstructed. The reason for this is that the built in sorting only accounts for the overall cloud coverage of an image tile, disregarding images where the area of interest may be cloud-free.

The Jupyter Notebook can filter out the images that are cloud free for an Area of interest, provided as a shapefile. 

The full Notebook can be found on [github](https://github.com/leaeffertz/PLUS_softwaredev_cloudsort/blob/main/cloudsort.ipynb).

