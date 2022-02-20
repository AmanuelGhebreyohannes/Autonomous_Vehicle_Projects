# pcd_to_binary

This application will assist in changing point cloud data to binary data so that it could be integrated in Autoware.ai

First add the library packages for pcl following :https://pcl.readthedocs.io/projects/tutorials/en/latest/compiling_pcl_posix.html

Steps:
$cd /path/to/pcd_to_binary.cpp
$mkdir build
$cd build
$cmake ..
$make
$./pcd_to_binary PointXYZ/PointXYZI/PointXYZRGB pcd_source.pcd


Finally a binary file will be saved which is feasible with Autoware.ai in the current folder.
