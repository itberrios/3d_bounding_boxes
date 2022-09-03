# 3d_bounding_boxes

Associate Detected Objects with LiDAR clusters and draw 3D bounding boxes. Notebooks [3d_box_lidar_0.ipynb](https://github.com/blueeagle100/3d_bounding_boxes/blob/main/3d_box_lidar_0.ipynb) contain links to download data and can be ran in collab. The experimental notebooks are just experiments and will likely be removed.

The general pipeline is:
- Get Object detections on image.
- Obtain LiDAR point cloud and remove ground plane via RANSAC
- Cluster objects in LiDAR space
- Associate detected objects with clustered objects in image space
- Get 3D location of clustered objects in image/camera space
- Draw 3D bounding boxes on the image


<br>
<br>

![image](https://user-images.githubusercontent.com/60835780/188273796-91ea32a2-3ea7-47a0-9d51-e654263dea33.png)


<br>
<br>

Links to videos created:
- https://youtu.be/hnhzeK2a2kk
- https://youtu.be/3YE7z7RQjjU
