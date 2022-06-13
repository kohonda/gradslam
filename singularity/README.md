## How to build container

```
singularity build --nv --fakeroot gradslam.sif gradslam.def 
```

## How to launch with the shell

```
singularity shell --nv gradslam.sif
```

## How to run

```
python3 examples/icpslam.py --dataset icl --dataset_path /home/honda/data/ICL --odometry gradicp
```