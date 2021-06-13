# Concrete Wall Crack Detection using Deep Learning

This repository contains Deep Learning Crack Detection Algorithm for the conference paper "Automated Building Exterior Crack Inspection using UAVs, Open-Source Deep Learning and Photogrammetry"

Before Running, Install the following

```
pip install tensorflow keras matplotlib image numpy Pillow
```

and execute the following if you are using Jupyter Notebook on Ubuntu
```
source my_project_env/bin/activate
```

## Getting Started

Place the image to be analyzed in the input folder.

Open **Concrete Wall Crack Detection.ipynb** file, modify the input image name and execute the final code block.

## Simulation

The Webot Simulation file used in the paper is in **Webot Simulation** folder. Running this simulation on Ubuntu is recommended. The controller is written in C.


## Data Set

For training with own data set, have a folder at root named Data
