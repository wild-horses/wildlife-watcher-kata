# 1. Introduction

This document describes the Wildlife Watcher, short WW, which is an open-source wildlife camera that gets triggered based on the movement of target animals, identifies the species
on the device and reports the observation in near real-time to biologists, enabling more efficient
species conservation efforts worldwide.

The following goals have been established for this system:
| Priority | |
|----------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1 | Users should be able to communicate with the camera using a mobile app (to set the cameras on/off and adjust settings without opening the cameras) |
| 2 | Users should be able to analyse the videos using common camera trap labelling platforms (Wildlife Insights, TrapTagger or Trapper) |
| 3 | Users should be able to publish frames from the videos to iNaturalist for experts to help with the identification of the species |
| 4 | Users should be able to easily train edge models. using their own labelled videos, and upload the models to the cameras (using third party services like Roboflow, Edge Impulse or TensorFlow Lite) |
| 5 | Users should be able to publish the species occurrences to GBIF the Camtrap DP, data exchange format |
| 6 | Cameras should be able to process the footage on the device and send a small alert message to the users via LoraWan, 3G or satellite |

## 1.1 Requirements Overview

_Lets add our use cases here_.

| Id   | Requirement           | Explanation                                                             |
| ---- | --------------------- | ----------------------------------------------------------------------- |
| F1   | Upload camera setting | Upload camera settings in the vicinity of the camera without opening it |
| F1.1 | Turn camera on or off | Turn the camera on or off                                               |

## 1.2 Quality Goals
