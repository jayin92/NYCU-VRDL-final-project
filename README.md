# NYCU-VRDL-final-project

## Introduction

### Problem statement
The Image Matching Challenge 2023 aims to advance the field of 3D reconstruction from real-world image collections. In this competition, the goal is to estimate the six degrees of freedom (6DoF) camera poses for a collection of unordered images taken from diverse viewpoints and conditions. Given a batch of images without additional sensor data or structured metadata, participants are required to predict the relative rotation and translation of each image, enabling accurate 3D reconstruction of the scene via Structure from Motion (SfM) techniques.

### The importance of this problem.
Robust multi-view Structure-from-Motion (SfM) is a fundamental task in computer vision. It helps with things like search-and-rescue missions, self-driving navigation, preserving historical sites in digital form, and everyday services like street views in online maps. Google Maps, for example, relies on SfM to fuse crowdsourced photos into city-scale 3D models. As more and more people take photos with their smartphones, using this large amount of casual, shared photos could make it possible to create high-quality maps without needing specialized equipment. Therefore, solving this challenge will contribute to faster, more accessible, and more detailed reconstructions of the world around us.

### The difficulties we address.
The primary challenges lie in the diversity and unpredictability of real-world image data. Variations in viewpoint, lighting, weather, resolution, occlusion and noise make image matching highly challenging. Moreover, the absence of sequential or temporal context further increases the difficulty of finding robust correspondences. Another major challenge is scale and efficiency — real-world scenes can contain hundreds of images, and trying to match every pair of images quickly becomes computationally expensive and impractical. In this work, we aim to address these challenges by adopting learned feature extractors and robust pose estimation pipelines that generalize across diverse environments.
