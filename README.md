# Monocular-Depth-Estimation
Monocular depth estimation - Trained on dataset created from ArgoAI's Argoverse LiDAR data - Range Upto 200m


[![Sample run on argo test set!](images/argo_test_depth_estimation_compressed_2.gif)]


Below are few sample depth estimation from the Argoverse trained Resnext101 BTS model. Click to watch the video on youtube.
## Depth estimation on Front Center Camera
[![Screenshot](images/vlcsnap-2020-07-20-15h53m17s829.png)](https://youtu.be/Fu7XHyHw1Gc)
## Depth estimation on Other Ring Cameras
[![Screenshot](images/vlcsnap-2020-07-21-14h43m47s958.png)](https://youtu.be/mjnpUREeBcM)

## Depth estimation on Ford AV dataset (Click to watch the whole video)
[![Sample run on ford av dataset!](images/depth_av.gif)](https://youtu.be/vGBkDh8BCQY)


# Argoverse-Monocular_depth-dataset-creation
Follow the instructions in [this](https://github.com/TilakD/Argoverse-Monocular_depth-dataset-creation/blob/main/argoverse_monocular_depth_map_tutorial.ipynb) notebook to generate depth maps from lidar ground truth points corresponding to the ring camera frames and use it for monocular depth estimation model training. 

NOTE: This notebook will be merged with Argoverse through [this](https://github.com/argoai/argoverse-api/pull/146) PR.

![Alt text](https://github.com/TilakD/Argoverse-Monocular_depth-dataset-creation/blob/main/depth_map.png "Sample")
*Depth map dilated for better visualization

Model trained on BTS arch - Check them out [here.](https://github.com/cogaplex-bts/bts)
