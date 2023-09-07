# ros-package-boilerplates
Scripts to generate boilerplates ros packages for multiple common purposes in robotics.

- [x] Minimal ROS package with node as ros component (2 versions: with/without callback group subscriptions)
- [ ] Minimal ROS package with regular node (2 versions: with/without callback group subscriptions)
- [ ] Minimal ROS package with generate parameter library from picknick robotics
- [ ] Minimal ROS package without generate parameter library from picknick robotics
- [ ] Minimal ROS package with rviz visual tools (you'll need to include tf2 and tf2_eigen for this)
- [ ] Minimal ROS package with common private member variables (like latest_odom_, frame_id_, etc.)
- [ ] Minimal ROS package with libraries like Eigen, Boost, pcl, your custom header-only library etc.
- [ ] Minimal launch file for a given configuration of a minimal ROS packages
- [ ] Minimal launch file for a group of a minimal ROS packages (or more accurately ROS components)
- [ ] Minimal launch file for a group of a minimal ROS packages (or more accurately ROS nodes)

Note: For every minimal package, have 2 subscribers, one with rclcpp::SensorDataQoS{}, and the other is QoS set as best coz it might not be sensor you know
