# Watching-a-Crosswalk
This repository contains the source code for the final project "Watching the Crossroad" at the Intro2CV Skoltech 2022 course. We propose a method for moving car detection at street videos based on classical CV algorithms.

The code is organized in jupyter notebooks:
* 'Compare Algos.ipynb' - implementation of the proposed algorithm
* 'YOLO baseline.ipynb' - YOLO applied to moving car detection
* 'SpeedDetection.ipynb' - speeders detection algorithm

'vids' directory contains source video clips obtained from real-world CCTV cameras.

## Requirements

* cv2 = 4.6.0
* torch >= 1.13
* torchvision >= 0.14.0
* skimage = 0.18.1
* sklearn = 1.0.2
