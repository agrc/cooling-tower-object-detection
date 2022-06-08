# Getting Started

## Prerequisites

This demo uses python and a Jupyter notebook. It is recommended to use Python 3.7 or greater. Visit [python.org](https://www.python.org/downloads/) and [jupyter.org](https://jupyter.org/install) for installation instructions.

_PyTorch has great instructions on how to [get started](https://pytorch.org/get-started/locally/) with these fundamental prerequisites._

Create a python virtual environment with conda or venv.

conda:

  1. `conda create --name demo python=3.7`
  1. `activate demo`

venv:

  1. `python -m venv .env`
  1. `source ./env/bin/activate`

PyTorch must be installed before this notebook can be run. Visit [pytorch.org](https://pytorch.org/get-started/locally/) for instructions.

For initial testing, UGRC used a CPU-only install with conda on windows.

- `conda install pytorch torchvision cpuonly -c pytorch`

And a pip install on MacOS

1. `pip install torch torchvision`

YOLOv5 need to be installed for the TowerScout weights to be applied. Quick start instructions for YOLOv5 can be found on [GitHub](https://github.com/ultralytics/yolov5)

1. `git clone https://github.com/ultralytics/yolov5`
2. `cd yolov5`
3. `pip install -r requirements.txt`

The sample images should be tiled to an appropriate tile size for processing by YOLOv5 (UGRC used 512x512 pixel tiles).

## Start the notebook

1. `jupyter notebook`
1. Select the
