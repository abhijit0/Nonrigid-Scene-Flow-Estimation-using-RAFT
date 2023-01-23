# Nonrigid-Scene-Flow-Estimation

Project Overview:
- Motivation: RAFT is State of the art for optical flow estimation. Why not
apply for scene flow ?

- Goal : Scene Flow Estimation using Raft by training on Flyingthigs3d dataset
and later fine tuning on Kitti to evaluate against Kitti scene flow benchmark

- Scene Flow is more robust representation of change in scene as it also
incorporates depth information where optical flow does not.

- Non rigid scene flow because we cannot model all the motion as rigidly
moving objects e.g human movements.
