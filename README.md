# This repository contains pedestrians and robot trajectory dataset recorded in UCL PAMELA lab.


Four scenarios are included:
S1: Pedestrians only
S2: Pedestrians and a wheelchair (low speed)
S3: Pedestrians and a wheelchair (high speed)
S4: Pedestrians and a Pepper humanoid robot (low speed)

Each scenarios have 5 runs and trajectories can be found in Sx/runx/traj.txt

traj.txt file includes the following information: 

ids = 28 (Total number of tracked objects in this run)
Robot id = -1 (-1 means no robot)
id, frame, x/m, y/m, z/m

The data is recorded at 12.5fps.

A screenshot of PAMELA is shown below.

![alt text](https://github.com/[username]/[reponame]/blob/[branch]/image.jpg?raw=true)
