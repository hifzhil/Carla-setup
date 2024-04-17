# Carla-setup

Welcome to my custom setup for the Carla simulator!

Before diving in, if you're new to Carla, make sure to visit the Carla Simulator Quick Start Guide for an overview.

## Overview

My setup revolves around using the latest Carla distributions directly from the source. While the version available in Ubuntu 20 repositories is typically 13, I prefer version 15 for its updated features. However, version 13 works just fine for most cases.
![Screenshot_20240411_161423](https://github.com/hifzhil/Carla-setup/assets/73360005/4b8c4dfd-c992-4ddf-b168-791530e0a835)

## Installation
To get started, head over to the [Carla Releases Page](https://github.com/carla-simulator/carla/blob/master/Docs/download.md) and download the appropriate version for your needs. The crucial file is the binary distribution.

Once downloaded, extract the files using the TAR command in your terminal:
```
tar -xzvf <carla_file.tar.gz>
```

![Screenshot_20240417_034639](https://github.com/hifzhil/Carla-setup/assets/73360005/0e87e568-4b04-452a-a357-ff3e1dffef7e)


Grab a cup of coffee while you wait for the extraction process to complete!

## Usage
After extraction, it's time to test your Carla setup. Use the following command to run Carla:

```
./CarlaUE4.sh -quality-level=Low -ResX=360 -ResY=240
```

- 'quality-level': Adjusts the graphic quality.
- 'ResX': Sets the window resolution along the x-axis.
- 'ResY': Sets the window resolution along the y-axis.

Additional arguments you can use:
- 'benchmak': Sets Carla to benchmark mode for performance metrics.
- 'fps=X ':Adjusts the frames per second (replace X with your desired FPS).

## Getting Started with Examples

Carla Simulator is written in Python 3.7 and can be interacted with using its Python API.

Navigate to the PythonAPI folder within your Carla directory (typically ~/Carla/PythonAPI). Here, you'll find essential files for communication:

- utils: Contains important files like config.py to change the town settings.
- carla: Check the dist folder here if you encounter import issues with the Carla module.
- examples: Explore this folder for ready-to-use examples (although sometimes they may have issues).
 
~~~
cd ~/Carla/PythonAPU/examples
ls
~~~

Run any of the examples. For instance, to run manual_control.py, execute:
```
python manual_control.py
```
## Demos
For a demonstration of Carla in action, check out my demo!

[![here](https://github.com/hifzhil/Carla-setup/assets/73360005/410a65ed-f34e-46de-b4b4-8a33969dff71)](https://www.youtube.com/watch?v=36-x1GWF4Iw&t=6s)
