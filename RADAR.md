# RADAR

## SLAM Papers

Papers who present complete SLAM solutions based on (but not exclusively) radar sensors.

### [Real Time RADAR SLAM](https://www.uni-das.de/images/pdf/veroeffentlichungen/2017/01.pdf) by Markus Schoen, Markus Horn, Markus Hahn, Juergen Dickmann (2017)

A SLAM algorithm using an odometer and radar sensor (x4, in total 360degree coverage) with a particle based localization algorithm combined with 2D occupancy grid mapping.

### Precise Ego-Motion Estimation with Millimeter-Wave Radar under Diverse and Challenging Conditions by Sarah H. Cen and Paul Newman (2018)

Main contributions of this paper are a novel method to extract landmarks from a FMCW radar returns. Furthermore, relative motion is estimated using scan matching by greedily adding point correspondences based on unary descriptors and pairwise compatibility scores. The association is based not only on unary descriptors, but also based on the relationship with other landmarks. The greater the number of points, the less likely it is for an individual point to have the same set of pairwise distance to its neighbors as another.

### Real-Time Pose Graph SLAM based on RADAR by Martin Holder, Sven Hellwig and Hermann Winner (2019)

SLAM algorithm to construct a map from Radar detections using the ICP method to match consecutive scans obtained from a single, front-facing Radar sensor. An important contribution of this paper is that the radar detections are not immediately matched with ICP but are first merged with consecutive Radar scans based on the odometry pose estimates creating "submaps" of the environment.

### PhaRaO: Direct Radar Odometry using Phase Correlation by Yeong Sang Park, Young-Sik Shin and Ayoung Kim (2020)

Main contribution of this paper is to use a direct method to estimate the odometry based on a Radar Sensor. Instead of using a feature-based method to estimate the odometry from the radar sensor. Specifically, they apply the Fourier Mellin transform (FMT) for Cartesian and log-polar radar images (phase correlation).

### RadarSLAM: Radar based Large-Scale SLAM in All Weathers by Ziyang Hong, Yvan Petillot and Sen Wang (2020)

Radar SLAM by pose tracking using visual SLAM techniques. Keypoint features are extracted using SURF and matched using their feature descriptors.  Relative transformation is then obtained via SVD. 
Local mapping is done by performing local bundle adjustment on the poses of keyframes and the locations of map points with the Levenberg-Marquardt method.
In order to do loop closure, radar images are converted to point clouds with a novel method and then M2DP is used to describe it (M2DP is an rotation invariant global descriptor for 3D point clouds)

## Radar Occupancy Grids

### Dual Inverse Sensor Model for Radar Occupancy Grids by Michael Slutsky and Daniel Dobkin (2019)

A novel Inverse Sensor Model for radar sensors. The model includes a "positive" component describing occupancy probabilities induced by radar detections and a "negative" component handling lack of detections in a given direction. The paper assumes a network of imaging radars that produce 3D detections/targets.

## Contributors
Important contributors to the RADAR field.
