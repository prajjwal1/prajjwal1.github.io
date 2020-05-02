---
title: "Autonomous Object Detection"
collection: projects
permalink: /projects/autoobjdet
date: 2019-08-02
---

This project initially started as a code base for this [hackathon](https://www.machinehack.com/course/making-autonomous-vehicles-safer-for-humans-hackathon-by-intel/leaderboard). This is a winning entry (team B) on the leaderboard. It later was transformed into a common project for object detection for autonomous driving. It later was also used for ICCVW 2019 (AutoNUE) [paper](https://arxiv.org/abs/1909.13080). The code is publicly available at this [Github URL](https://github.com/prajjwal1/autonomous-object-detection).

This work provides support for the following datasets (related to object detection for autonomous navigation):
- [India Driving Dataset](https://idd.insaan.iiit.ac.in/)
- [Berkeley Deep drive](https://bdd-data.berkeley.edu/)
- [Cityscapes](https://www.cityscapes-dataset.com/)

These Dataset class complies with torchvision API. Users can create their own `Dataset` class if they want to use some other dataset. By default, FasterRCNN is loaded to perform the training and evaluation is performed in the same way as MS-COCO format.
