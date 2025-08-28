# Advancing Endangered Species Conservation: Leveraging Text-to-Image Diffusion for Realistic Image Generation and Computer Vision Model Training

This repository contains the model weights and resources for the paper, under review in the *Journal for Nature Conservation*.

## Overview

This project demonstrates a proof-of-concept pipeline for training object detectors for endangered species using purely synthetic data generated from a text-to-image model. We address the challenge of data scarcity for two species: the Javan rhinoceros and the lion-tailed macaque.

## Repository Contents

* `/weights`: Contains the final trained  model weights for each species.
* `/prompts`: Contains the text files with the full list of prompts used to generate the synthetic datasets.

## Installation

To use the models, you will need a local installation of [YOLOv5](https://github.com/ultralytics/yolov5). Follow their [installation guide](https://github.com/ultralytics/yolov5#quick-start) to get started.


## Data and Code Availability

The final model weights are available in the `/weights` directory of this repository. The full list of prompts used for synthetic data generation is available in the `/prompts` directory. Due to privacy considerations of the source images, the authentic image dataset used for testing is not publicly available at this time but may be provided by the authors upon reasonable request. The generated synthetic dataset will also be uploaded soon.

