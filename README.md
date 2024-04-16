# Carla-setup

This is my custom setup on carla simulator 

Please read a carla simulator page on this https://carla.readthedocs.io/en/latest/start_quickstart/

My own is to using a binary from carla source because it has latest carla distriutins, as we know, to work with carla_ros_bridge on Ros 1 you need a Ubuntu 20, and a carla version that available on Ubuntu 20 repo's iis version 13
But, I want the latest version, that is 15, but you can still fine with version 13 as well
![Screenshot_20240411_161423](https://github.com/hifzhil/Carla-setup/assets/73360005/4b8c4dfd-c992-4ddf-b168-791530e0a835)

When you read it, you will be going to this repo, choose your version and download it, the most important file is the first one : https://github.com/carla-simulator/carla/blob/master/Docs/download.md

Oncce download completed, extract it with TAR (Dont extract it with GUI), open terminal type :
![Screenshot_20240417_034639](https://github.com/hifzhil/Carla-setup/assets/73360005/0e87e568-4b04-452a-a357-ff3e1dffef7e)


Get your cup of coffe while waiting the extrack process :)



Ok, now make a test 
this is my command to run a carla : 

```
./CarlaUE4.sh -quality-level=Low -ResX=360 -ResY=240
```

- quality-level: set the CARLA's graphic quality
- ResX: CARLA's window resolution (x-axis)
- ResY: CARLA's window resolution (y-axis)

Additionally, you can add this args also :
- benchmak (set carla to benchmark mode, so it will measure and reporting performance metrics)
- fps = X (we can control the FPS, replace X for the FPS you need)

