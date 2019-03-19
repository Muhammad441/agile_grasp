## 1) Instructions
- Run the single_camera.launch launch file:
  roslaunch agile_grasp single_camera_grasps.launch 

- Publish the pointcloud of the object you want to grasp using the following command:
  rosrun pcl_ros pcd_to_pointcloud /home/suhail/Downloads/004_sugar_box/clouds/outfilefile.pcd 0.1 _frame_id:=/camera_link



