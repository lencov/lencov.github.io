---
layout: project
type: project
image: img/beetleImage.jpeg
title: "Pest Species Classifier"
date: 2015
published: true
labels:
  - Machine Learning
  - Python
summary: "Image processing software for identifying pest species in hyperspectral images."
---

Site: USDA ARS Pacific Basin Agricultural Research Center, Hilo, Hawaiʻi
Mentor: Pei Liang

This project aims to develop machine learning algorithm(s) to identify key agricultural pests, specifically targeting beetle pests of macadamia orchards. This will enhance pest management strategies, providing entomologists researchers with a powerful tool to effectively monitor and control pest populations. The research conducted by entomologists often involves testing the effectiveness of different traps and lures and monitoring pest populations. As some of the lures are not species specific (i.e. attracting more than one species in one trap), part of the workflow would then involve identifying and counting the trapped insects before the population sizes can be estimated. Manually identifying and counting beetles is a time-consuming process that can take hundreds of man-hours per year and requires highly-trained personnel. In addition, the number of different species caught in these traps is inconsistent, making it difficult to rely on average fractions to determine species counts accurately. In this study, we utilize near-infrared hyperspectral imaging to capture the spectral signatures of these beetles. Near-infrared hyperspectral imaging provides spectral information based on the chemical composition of the materials being measured. We collect hyperspectral images of known beetle species, segmenting them to isolate beetles from the background and extracting spectral features to train a machine learning model. By automating the identification process, this project aims to significantly reduce the time and effort required for manual sorting, providing a scalable solution for continuous monitoring and assessment of pest populations and aiding in the protection of Hawai’i’s agricultural resources.

Link to github repo: https://github.com/lencov/PestClassifierModel
