<div class="github-widget" data-repo="fkromer/awesome-ros2"></div>
## Awesome Robot Operating System 2 (ROS 2) [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[<img src="https://raw.githubusercontent.com/fkromer/awesome-ros2/master/ros_logo.svg?sanitize=true" align="right" width="86">](https://raw.githubusercontent.com/ros2/ros2/wiki)

&gt; 精选的机器人操作系统 2.0 版 (ROS 2) 资源和库列表.

机器人操作系统 2 (ROS 2) 是一组软件库和工具，可帮助您构建机器人应用程序. 从驱动程序到最先进的算法，再到强大的开发人员工具，ROS 2 拥有您下一个机器人项目所需的一切. 而且都是开源的.



## Packages

### Data collection
- [ros2_data_collection](https://github.com/Minipada/ros2_data_collection) - 从 ROS 2 可靠地收集、验证和发送数据，以创建 API 和仪表板. ![ros2_data_collection](https://img.shields.io/github/stars/minipada/ros2_data_collection.svg)

### Demonstrations

- [adlink_ddsbot](https://github.com/Adlink-ROS/adlink_ddsbot) - 基于 ROS 2.0/1.0 的机器人群架构 (opensplice DDS). ![adlink_ddsbot](https://img.shields.io/github/stars/Adlink-ROS/adlink_ddsbot.svg)
- [adlink_neuronbot](https://github.com/Adlink-ROS/adlink_neuronbot) - 用于人类跟随和集群的 ROS2/DDS 机器人包. ![adlink_neuronbot](https://img.shields.io/github/stars/Adlink-ROS/adlink_neuronbot.svg)
- [turtlebot3](https://github.com/ROBOTIS-GIT/turtlebot3/tree/ros2) - 基于 ROS2 的 TurtleBot3 演示，包括 Bringup、Teleop 和 Cartographer. ![turtlebot3](https://img.shields.io/github/stars/ROBOTIS-GIT/turtlebot3.svg)

### Examples

- [turtlebot2_demo](https://github.com/ros2/turtlebot2_demo) - 使用 ROS 2 的 TurtleBot 2 演示. ![turtlebot2_demo](https://img.shields.io/github/stars/ros2/turtlebot2_demo.svg)
- [examples/rclcpp](https://github.com/ros2/examples/tree/master/rclcpp) - C++ 示例. ![ros2/examples](https://img.shields.io/github/stars/ros2/examples.svg)
- [examples/rclpy](https://github.com/ros2/examples/tree/master/rclpy) - Python 示例. ![ros2/examples](https://img.shields.io/github/stars/ros2/examples.svg)
- [rcljava_examples](https://github.com/esteve/ros2_java_examples/tree/master/rcljava_examples) - 包含如何使用 rcljava API 示例的包. ![ros2_java_examples](https://img.shields.io/github/stars/esteve/ros2_java_examples.svg)
- [ros2_talker_android, ros2_listener_android](https://github.com/esteve/ros2_android_examples) - ROS2 Java 绑定的示例 Android 应用程序. ![ros2_android_examples](https://img.shields.io/github/stars/esteve/ros2_android_examples.svg)  
- [zed-ros2-examples](https://github.com/stereolabs/zed-ros2-examples) - 示例和教程使用 ROS2 中的 ZED 相机. ![zed_ros2_example](https://img.shields.io/github/stars/stereolabs/zed-ros2-examples.svg)  
- [realsense-ros:ros2-branch](https://github.com/IntelRealSense/realsense-ros/tree/ros2) - 用于英特尔® 实感™ 设备的 ROS2 包装器 ![realsense-ros](https://img.shields.io/github/stars/IntelRealSense/realsense-ros.svg)  

### Benchmarking

- [ros2_benchmarking](https://github.com/piappl/ros2_benchmarking)  - ROS2 基准测试框架.  ROS2 通信特性可以在多个轴上快速、自动地进行评估. ![ros2_benchmarking](https://img.shields.io/github/stars/piappl/ros2_benchmarking.svg)
- [performance_test](https://github.com/ApexAI/performance_test) - 测试各种通信方式的性能和延迟，如 ROS 2、FastRTPS 和 Connext DDS Micro. ![performance_test](https://img.shields.io/github/stars/ApexAI/performance_test.svg)

### Containerization

- [docker-ros2-ospl-ce](https://github.com/Adlink-ROS/docker-ros2-ospl-ce) - 用于构建 ROS2 + OpenSplice CE 容器的 dockerfile. ![docker-ros2-ospl-ce](https://img.shields.io/github/stars/Adlink-ROS/docker-ros2-ospl-ce.svg)
- [ros2_java_docker](https://github.com/esteve/ros2_java_docker) - 用于使用 OpenJDK 和 Android 构建 ros2_java 的 Dockerfiles. ![ros2_java_docker](https://img.shields.io/github/stars/esteve/ros2_java_docker.svg)
- [micro-ROS/docker](https://github.com/micro-ROS/docker) - 与 Docker 相关的材料，用于使用微型 ROS 硬件进行设置、配置和开发.
- [ros-tooling/cross_compile](https://github.com/ros-tooling/cross_compile) - 将 ROS 和 ROS 2 工作区交叉编译到非原生架构并生成相应的 Docker 镜像.
- [ros2-docker](https://husarnet.com/blog/ros2-docker) - 通过互联网连接在 Docker 容器中运行的 ROS 2 节点.
- [osrf/docker_images](https://github.com/osrf/docker_images) - 的 Dockerfiles [Official Library on Docker Hub](https://hub.docker.com/_/ros) 和 [OSRF Organization on Docker Hub](https://hub.docker.com/r/osrf/ros). ![osrf/ros](https://img.shields.io/github/stars/osrf/docker_images.svg)
- [docker-ros2-desktop-vnc](https://github.com/Tiryoh/docker-ros2-desktop-vnc) - Dockerfiles 提供 HTML5 VNC 接口来访问 Ubuntu LXDE + ROS2. ![docker-ros2-desktop-vnc](https://img.shields.io/github/stars/Tiryoh/docker-ros2-desktop-vnc.svg)
- [ros2-lxd](https://ubuntu.com/blog/install-ros-2-humble-in-ubuntu-20-04-or-18-04-using-lxd-containers) - 使用 LXD 容器在 Ubuntu 20.04 或 18.04 中安装 ROS 2 Humble.

### Networking

- [Husarnet VPN](https://github.com/husarnet/husarnet) - 专用于 ROS 和 ROS 2 的 P2P 安全网络层. ![husarnet](https://img.shields.io/github/stars/husarnet/husarnet.svg)

### Ecosystem

- [Link ROS](https://www.freedomrobotics.ai/blog/link-ros-cloud-logging-for-ros) - ROS 1 和 ROS 2 的云日志记录.
- [rosbag2](https://github.com/ros2/rosbag2) - ROS2 原生 rosbag. ![rosbag2](https://img.shields.io/github/stars/ros2/rosbag2.svg)
- [rviz](https://github.com/ros2/rviz) - 3D 机器人展示台. ![rviz](https://img.shields.io/github/stars/ros2/rviz.svg)
- [urdfdom](https://github.com/ros/urdfdom) - URDF（U-Robot 描述格式）库，提供核心数据结构和简单的 XML 解析器 ![urdfdom](https://img.shields.io/github/stars/ros/urdfdom.svg)
- [urdfdom_headers](https://github.com/ros/urdfdom_headers) - URDF 解析器的标头. ![urdfdom_headers](https://img.shields.io/github/stars/ros/urdfdom_headers.svg)
- [ros2cli](https://github.com/ros2/ros2cli) - ROS 2 命令行工具. ![ros2cli](https://img.shields.io/github/stars/ros2/ros2cli.svg)
- [orocos_kinematics_dynamics](https://github.com/ros2/orocos_kinematics_dynamics) - Orocos 运动学和动力学 C++ 库. ![orocos_kinematics_dynamics](https://img.shields.io/github/stars/ros2/orocos_kinematics_dynamics.svg)
- [pydds](https://github.com/atolab/pydds) - 用于 Vortex Lite 和 OpenSplice 的简单 DDS Python API. ![pydds](https://img.shields.io/github/stars/atolab/pydds.svg)
- [Webots](https://cyberbotics.com) - ROS 2 的机器人模拟器. ![webots](https://img.shields.io/github/stars/cyberbotics/webots.svg)
- [LGSVL](https://www.lgsvlsimulator.com/) - 加速安全自动驾驶汽车开发的仿真软件.
- [Unity Robotics Hub](https://github.com/Unity-Technologies/Unity-Robotics-Hub) - 这是 Unity 机器人仿真工具、教程、资源和文档的中央存储库.
- [Foxglove Studio](https://github.com/foxglove/studio) - 用于机器人技术的集成可视化和诊断工具. ![foxglove studio](https://img.shields.io/github/stars/foxglove/studio.svg)
- [ROS2 For Unity](https://github.com/RobotecAI/ros2-for-unity) - 一个资产包，可在 Unity3D 模拟和 ROS2 生态系统之间实现高性能通信. ![ros2-for-unity](https://img.shields.io/github/stars/RobotecAI/ros2-for-unity.svg)

### Interactivity

- [Jupyter ROS2](https://github.com/zmk5/jupyter-ros2) - ROS2 的 Jupyter 小部件助手.

### Penetration testing

- [aztarna](https://github.com/aliasrobotics/aztarna) - 机器人足迹工具.
- [ros2_fuzzer](https://github.com/aliasrobotics/ros2_fuzzer) - ROS2 主题和服务模糊器.

### Application layer

- [Apex.Autonomy](https://www.apex.ai/apex-autonomy) - Apex.Autonomy 将自治算法作为单独的构建块提供，并与 Autoware.Auto 兼容.
- [Autoware.Auto](https://www.autoware.auto/) - Autoware.Auto 为自动驾驶技术提供基于 ROS 2 的开源软件堆栈.
- [ros2_control](https://github.com/ros-controls/ros2_control) - `ros2_control` 是关于如何在机器人控制 (`ros2_controllers`) 的上下文中阐述和使用 ROS 2 中的新功能的概念证明. ![ros2_control](https://img.shields.io/github/stars/ros-controls/ros2_control.svg)
- [ros2_controllers](https://github.com/ros-controls/ros2_controllers) - ros_controllers 的描述. ![ros2_controllers](https://img.shields.io/github/stars/ros-controls/ros2_controllers.svg)
- [geometry2](https://github.com/ros2/geometry2) - 一组用于跟踪坐标变换的 ROS 包. ![geometry2](https://img.shields.io/github/stars/ros2/geometry2.svg)
- [ros2-ORB_SLAM2](https://github.com/alsora/ros2-ORB_SLAM2) - 包装 ORB_SLAM2 库的 ROS2 节点. ![ros2-ORB_SLAM2](https://img.shields.io/github/stars/alsora/ros2-ORB_SLAM2.svg)
- [basalt_ros2](https://github.com/berndpfrommer/basalt_ros2) - Basalt VIO 的 ROS2 包装器. ![basalt_ros2](https://img.shields.io/github/stars/berndpfrommer/basalt_ros2.svg)
- [cartographer](https://github.com/ros2/cartographer) - 跨多个平台和传感器配置的 2D 和 3D 实时同时定位和映射 (SLAM). ![cartographer](https://img.shields.io/github/stars/ros2/cartographer.svg)
- [slam_gmapping](https://github.com/Project-MANAS/slam_gmapping) - ROS2 的大满贯 Gmapping. ![slam_gmapping](https://img.shields.io/github/stars/Project-MANAS/slam_gmapping.svg)
- [slam_toolbox](https://github.com/SteveMacenski/slam_toolbox) - Slam 工具箱，用于使用 ROS 在潜在的大型地图中进行终身映射和定位. ![slam_toolbox](https://img.shields.io/github/stars/SteveMacenski/slam_toolbox.svg)
- [lidarslam_ros2](https://github.com/rsasaki0109/lidarslam_ros2) - 使用 ndt/gicp 注册和姿势优化的 3D 激光雷达 slam 的 ROS2 包. ![lidarslam_ros2](https://img.shields.io/github/stars/rsasaki0109/lidarslam_ros2.svg)
- [li_slam_ros2](https://github.com/rsasaki0109/li_slam_ros2) - 从 LIO-SAM 引用的紧耦合激光雷达惯性 ndt/gicp slam 的 ROS2 包. ![li_slam_ros2](https://img.shields.io/github/stars/rsasaki0109/li_slam_ros2.svg)
- [octomap_server2](https://github.com/iKrishneel/octomap_server2)  - 用于使用 OctoMap 进行映射的 ROS2 堆栈.  ROS1的端口 [octomap_mapping](https://github.com/OctoMap/octomap_mapping) 包裹. ![octomap_server2](https://img.shields.io/github/stars/iKrishneel/octomap_server2.svg)
- [vision_opencv](https://github.com/ros-perception/vision_opencv/tree/ros2) - 用于将 ROS2 与 OpenCV 连接的软件包. ![vision_opencv](https://img.shields.io/github/stars/ros-perception/vision_opencv.svg)
- [teleop_twist_keyboard](https://github.com/ros2/teleop_twist_keyboard) - ROS2 的通用键盘 Teleop. ![teleop_twist_keyboard](https://img.shields.io/github/stars/ros2/teleop_twist_keyboard.svg)
- [teleop_twist_joy](https://github.com/ros2/teleop_twist_joy) - 用于扭曲机器人的简单操纵杆遥控. ![teleop_twist_joy](https://img.shields.io/github/stars/ros2/teleop_twist_joy.svg)
- [navigation](https://github.com/ros-planning/navigation2/) - ROS2 导航堆栈. ![navigation](https://img.shields.io/github/stars/ros-planning/navigation2.svg)
- [diagnostics](https://github.com/bponsler/diagnostics/tree/ros2-devel) - 用于 ROS 2 的原始 ROS1 诊断的分叉版本（目前仅限 diagnostics_updater）. ![diagnostics](https://img.shields.io/github/stars/bponsler/diagnostics.svg)
- [robot_state_publisher](https://github.com/bponsler/robot_state_publisher/tree/publish-robot-model) - 原始 ROS Robot State Publisher 的分叉版本，包含所有修改以在 ROS2 生态系统中编译. ![robot_state_publisher](https://img.shields.io/github/stars/bponsler/robot_state_publisher.svg)
- [common_interfaces](https://github.com/ros2/common_interfaces) - 一组包含通用接口文件（.msg 和 .srv）的包. ![common_interfaces](https://img.shields.io/github/stars/ros2/common_interfaces.svg)
- [ros2_object_map](https://github.com/intel/ros2_object_map) - “SLAM 时在地图上标记对象”. ![ros2_object_map](https://img.shields.io/github/stars/intel/ros2_object_map.svg)
- [ros2_object_analytics](https://github.com/intel/ros2_object_analytics) - 对象分析 (OA) 是用于实时对象检测、定位和跟踪的 ROS2 包装器. ![ros2_object_analytics](https://img.shields.io/github/stars/intel/ros2_object_analytics.svg)
- [ros2_intel_movidius_ncs](https://github.com/intel/ros2_intel_movidius_ncs) - 用于 Movidius™ 神经计算棒 (NCS) 神经元计算 API 的 ROS2 包装器. ![ros2_intel_movidius_ncs](https://img.shields.io/github/stars/intel/ros2_intel_movidius_ncs.svg)
- [ros2_moving_object](https://github.com/intel/ros2_moving_object) - 根据对象分析 `ros2_object_analytics` 生成的消息处理移动对象. ![ros2_moving_object](https://img.shields.io/github/stars/intel/ros2_moving_object.svg)
- [ros2_openvino_toolkit](https://github.com/intel/ros2_openvino_toolkit) - 用于 OpenVINO™（人类视觉仿真）的 CV API 的 ROS2 包装器. ![ros2_openvino_toolkit](https://img.shields.io/github/stars/intel/ros2_openvino_toolkit.svg)
- [ros2_grasp_library](https://github.com/intel/ros2_grasp_library) - 可能是一个抓取库 :). ![ros2_grasp_library](https://img.shields.io/github/stars/intel/ros2_grasp_library.svg)
- [apriltag_ros](https://github.com/christianrauch/apriltag_ros) - 用于 AprilTag 检测的 ROS2 节点. ![apriltag_ros](https://img.shields.io/github/stars/christianrauch/apriltag_ros.svg)
- [rosbridge_suite](https://github.com/RobotWebTools/rosbridge_suite) - 将您的浏览器桥接到 ROS 2.0. ![rosbridge_suite](https://img.shields.io/github/stars/RobotWebTools/rosbridge_suite.svg)
- [ros2_message_filters](https://github.com/intel/ros2_message_filters) - ros2_message_filters 根据过滤器需要满足的条件混合各种消息，并派生自 ROS message_filters 的 ROS2 移植. ![ros2_message_filters](https://img.shields.io/github/stars/intel/ros2_message_filters.svg)
- [ros2-tensorflow](https://github.com/alsora/ros2-tensorflow) - Tensorflow 中用于计算机视觉任务的 ROS2 节点. ![ros2-tensorflow](https://img.shields.io/github/stars/alsora/ros2-tensorflow.svg)
- [ros2_pytorch](https://github.com/klintan/ros2_pytorch) - PyTorch 中用于计算机视觉任务的 ROS2 节点 ![ros2_pytorch](https://img.shields.io/github/stars/klintan/ros2_pytorch.svg).
- [ros2_pytorch_cuda](https://github.com/slabban/ros2_pytorch_cuda) - 的扩展 [ros2_pytorch](https://github.com/klintan/ros2_pytorch) 适用于容器化的 CUDA 设备.
- [pid](https://github.com/UTNuclearRoboticsPublic/pid) - ROS2 的 PID 控制器. ![pid](https://img.shields.io/github/stars/UTNuclearRoboticsPublic/pid.svg)
- [system-modes](https://github.com/micro-ROS/system_modes) - ROS 2 和 micro-ROS 的系统模式.
- [darknet_ros](https://github.com/leggedrobotics/darknet_ros/tree/ros2) - 用于部署 Darknet 的 YOLO 计算机视觉模型的 ROS2 包装器.
- [easy_perception_deployment](https://github.com/ros-industrial/easy_perception_deployment) - 加速行业计算机视觉模型培训和部署的软件包. ![easy_perception_deployment](https://img.shields.io/github/stars/ros-industrial/easy_perception_deployment.svg)
- [easy_manipulation_deployment](https://github.com/ros-industrial/easy_manipulation_deployment) - 集成感知元素以建立端到端拾取和放置任务的包. ![easy_manipulation_deployment](https://img.shields.io/github/stars/ros-industrial/easy_manipulation_deployment.svg)
- [ros2_pid_library](https://github.com/dottantgal/ros2_pid_library) - 一个 ROS2 Humble 完全可配置的 PID 库 ![ros2_pid_library](https://img.shields.io/github/stars/dottantgal/ros2_pid_library.svg)
- [wayp_plan_tools](https://github.com/jkk-research/wayp_plan_tools) - 用于 ROS 2 的航路点和规划器工具，具有最小的依赖性和可选的 Gazebo Fortress 模拟. ![wayp_plan_tools](https://img.shields.io/github/stars/jkk-research/wayp_plan_tools.svg)

### Middleware

- [Micro XRCE-DDS Agent](https://github.com/eProsima/Micro-XRCE-DDS-Agent) - 微型 XRCE-DDS 代理充当 DDS 网络和微型 XRCE-DDS 客户端之间的服务器.
- [Micro XRCE-DDS Agent docker](https://hub.docker.com/r/eprosima/micro-xrce-dds-agent/) - 包含 Micro XRCE-DDS Agent 的 Docker 镜像.
- [Micro XRCE-DDS Client](https://github.com/eProsima/Micro-XRCE-DDS-Client) - Micro XRCE-DDS 实现客户端-服务器协议，使资源受限的设备（客户端）能够参与 DDS 通信.
- [micro-ROS-Agent](https://github.com/micro-ROS/micro-ROS-Agent) - 使用 Micro XRCE-DDS 代理的 ROS 2 包.
- [Eclipse Zenoh](https://github.com/eclipse-zenoh/zenoh) - [Zenoh](https://zenoh.io) 是一种可扩展且性能极佳的协议，可以透明地用于与 [ROS2 applications](https://zenoh.io/blog/2021-04-28-ros2-integration/) 以及对于 [R2X communication](https://zenoh.io/blog/2021-03-23-discovery/). (https://img.shields.io/github/stars/eclipse-zenoh/zenoh)
- [Eclipse Zenoh-Plugin-DDS](https://github.com/eclipse-zenoh/zenoh-plugin-dds) - 这是一个 [zenoh](https://zenoh.io) 允许通过 zenoh 透明地路由 ROS2/DDS 数据的插件. 这通常用于 [R2X communication](https://zenoh.io/blog/2021-03-23-discovery/) 通过无线网络或互联网.  (https://img.shields.io/github/stars/eclipse-zenoh/zenoh-plugin-dds)

### "System" bindings

- [rclandroid](https://github.com/esteve/ros2_android/tree/master/rclandroid) - 用于 ROS2 的安卓 API. ![rclandroid](https://img.shields.io/github/stars/esteve/ros2_android.svg)
- [rclnodejs](https://github.com/RobotWebTools/rclnodejs) - Node.js 版本的 ROS2.0 客户端. ![rclnodejs](https://img.shields.io/github/stars/RobotWebTools/rclnodejs.svg)
- [riot-ros2](https://github.com/astralien3000/riot-ros2) - 该项目使 ROS2 能够使用 RIOT 操作系统在微控制器上运行. ![riot-ros2](https://img.shields.io/github/stars/astralien3000/riot-ros2.svg)
- [ROS2-Integration-Service](https://github.com/eProsima/ROS2-Integration-Service) - ROS2 集成和路由，它提供了一个完整的工具，可以轻松地将其他技术与 ROS2 集成，并在 WAN/Internet 上启用 ROS2.
- [soss](https://github.com/osrf/soss) - System Of Systems Synthesizer 用于通过 ROS2-Integration-Service 将 ROS2 与其他（通信）系统集成.
- [micro_ros_arduino](https://github.com/micro-ROS/micro_ros_arduino) - 将微型 ROS 集成到 Arduino 软件平台项目中.
- [micro_ros_zephyr_module](https://github.com/micro-ROS/micro_ros_zephyr_module) - 在基于 Zeyphr OS 的项目中集成 micro-ROS.

### Driver layer

- [Autoware.IO](https://www.autoware.io/) - Autoware.IO 提供异构硬件参考平台，并支持将成员公司的解决方案集成到支持 Autoware.Auto 和 Autoware.AI 软件堆栈的平台上.
- [ros2_xmlrpc_interface](https://github.com/aarushsesto/ros2_xmlrpc_interface) - 带有 xmlrpc 的 ros2 接口包，使用 Sesto API 与 Sesto 服务器通信. ![ros2_xmlrpc](https://img.shields.io/github/stars/aarushsesto/ros2_xmlrpc_interface.svg)
- [cozmo_driver_ros2](https://github.com/FurqanHabibi/cozmo_driver_ros2) - ROS2 的非官方 Anki Cozmo 节点. ![cozmo_driver_ros2](https://img.shields.io/github/stars/FurqanHabibi/cozmo_driver_ros2.svg)
- [sphero_ros2](https://github.com/athackst/sphero_ros2) - ROS2 sphero 驱动程序. ![sphero_ros2](https://img.shields.io/github/stars/athackst/sphero_ros2.svg)
- [flock2](https://github.com/clydemcqueen/flock2) - DJI Tello 无人机的 ROS2 驱动程序. ![flock2](https://img.shields.io/github/stars/clydemcqueen/flock2.svg)
- [ros2_raspicam_node](https://github.com/Misterblue/ros2_raspicam_node) - Raspberry Pi 相机的 ROS2 节点. ![ros2_raspicam_node](https://img.shields.io/github/stars/Misterblue/ros2_raspicam_node.svg)
- [joystick_drivers](https://github.com/ros2/joystick_drivers) - 用于操纵杆的 ROS2 驱动程序. ![joystick_drivers](https://img.shields.io/github/stars/ros2/joystick_drivers.svg)
- [joystick_drivers_from_scratch](https://github.com/ros2/joystick_drivers_from_scratch) - ROS 2 的操纵杆驱动程序包. ![joystick_drivers_from_scratch](https://img.shields.io/github/stars/ros2/joystick_drivers_from_scratch.svg)
- [joystick_ros2](https://github.com/FurqanHabibi/joystick_ros2) - ROS2 的操纵杆驱动程序，支持所有平台：Linux、macOS、Windows. ![joystick_ros2](https://img.shields.io/github/stars/FurqanHabibi/joystick_ros2.svg)
- [ros2_teleop_keyboard](https://github.com/rohbotics/ros2_teleop_keyboard) - 适用于 ROS2 的 Teleop Twist 键盘. ![ros2_teleop_keyboard](https://img.shields.io/github/stars/rohbotics/ros2_teleop_keyboard.svg)
- [ros_astra_camera](https://github.com/ros2/ros_astra_camera) - 用于 Astra 相机的 ROS2 包装器. ![ros_astra_camera](https://img.shields.io/github/stars/ros2/ros_astra_camera.svg)
- [ros2_usb_camera](https://github.com/klintan/ros2_usb_camera) - ROS2 通用 USB 摄像头驱动程序. ![ros_astra_camera](https://img.shields.io/github/stars/klintan/ros2_usb_camera.svg)
- [ros2_android_drivers](https://github.com/esteve/ros2_android_drivers) - 多个 Android 传感器的 ROS2 驱动程序集合. ![ros2_android_drivers](https://img.shields.io/github/stars/esteve/ros2_android_drivers.svg)
- [ros2_intel_realsense](https://github.com/intel/ros2_intel_realsense) - 用于英特尔® 实感™ 设备的 ROS2 包装器. ![ros2_intel_realsense](https://img.shields.io/github/stars/intel/ros2_intel_realsense.svg)
- [raspicam2_node](https://github.com/christianrauch/raspicam2_node) - ROS2 node for camera module of Raspberry Pi. ![raspicam2_node](https://img.shields.io/github/stars/christianrauch/raspicam2_node.svg)
- [ros2_track_imu](https://github.com/klintan/ros2_track_imu) - 用于 TrackIMU IMU 传感器的 ROS2 节点![ros2_track_imu](https://img.shields.io/github/stars/klintan/ros2_track_imu.svg).
- [HRIM](https://github.com/AcutronicRobotics/HRIM) - 机器人模块的标准接口.
- [FIROS2](https://github.com/eProsima/FIROS2) - ROS2 可集成工具，专注于 ROS2 和 FIWARE 之间的相互通信. ![FIROS2](https://img.shields.io/github/stars/eProsima/FIROS2.svg)
- [lino2_upper](https://github.com/linorobot2/lino2_upper) - ROS2 上的 Linorobot. ![lino2_upper](https://img.shields.io/github/stars/linorobot2/lino2_upper.svg)
- [RysROS2](https://github.com/GroupOfRobots/RysROS2) - 用于 MiniRys 机器人的 ROS2 软件堆栈. ![RysROS2](https://img.shields.io/github/stars/GroupOfRobots/RysROS2.svg)
- [px4_to_ros](https://github.com/eProsima/px4_to_ros) - 用于将 PX4 与 ROS 通信的 ROS2/ROS 包. ![px4_to_ros](https://img.shields.io/github/stars/eProsima/px4_to_ros.svg)
- [multiwii_ros2](https://github.com/christianrauch/multiwii_ros2) - 用于 MultiWii 和 Cleanflight 飞行控制器的 ROS2 节点. ![multiwii_ros2](https://img.shields.io/github/stars/christianrauch/multiwii_ros2.svg)
- [ydlidar_ros2](https://github.com/Adlink-ROS/ydlidar_ros2) - ydlidar 的 ROS2 包装器. ![ydlidar_ros2](https://img.shields.io/github/stars/Adlink-ROS/ydlidar_ros2.svg)
- [zed-ros2-wrapper](https://github.com/stereolabs/zed-ros2-wrapper) - ZED SDK 的 ROS 2 包装测试版.
- [ros2_denso_radar](https://github.com/klintan/ros2_denso_radar) - 用于 ROS2 的 Toyota/Lexus 2015-2017 Denso 雷达驱动程序.
- [sick_scan2](https://github.com/SICKAG/sick_scan2) - 用于 SICK TiM 系列激光扫描仪 (TiM551/TiM561/TiM571) 的 ROS2 驱动程序.
- [ros2_ouster_drivers](https://github.com/SteveMacenski/ros2_ouster_drivers) - Ouster OS-1 激光雷达的 ROS2 驱动程序. ![ros2_ouster_drivers](https://img.shields.io/github/stars/SteveMacenski/ros2_ouster_drivers)
- [micro-ROS/hardware](https://github.com/micro-ROS/hardware) - 有关微型 ROS 项目中使用和支持的硬件平台的信息和文档.
- [Blickfeld Cube 1 & Cube Range](https://docs.blickfeld.com/cube/latest/external/ros/driver-v2/README.html) - 用于 Blickfeld Cube 1 和 Cube Range 的 ROS2 驱动程序.
- [Universal Robots](https://github.com/UniversalRobots/Universal_Robots_ROS2_Driver) - 适用于 UR CB3 和 e 系列的 ROS2 驱动程序.
- [odrive_ros2_control](https://github.com/Factor-Robotics/odrive_ros2_control) - ros2_control 的 ODrive 驱动程序.
- [duro_gps_driver](https://github.com/szenergy/duro_gps_driver) - 用于 SwiftNav Duro 惯性 GPS / GNSS 接收器的 ROS/ROS2 驱动程序 ![duro_gps_driver](https://img.shields.io/github/stars/szenergy/duro_gps_driver.svg)

### Client libraries

- [rclada](https://github.com/ada-ros/rclada) - Ada 的 ROS 客户端库. ![rclada](https://img.shields.io/github/stars/ada-ros/rclada.svg)
- [rclcpp](https://github.com/ros2/rclcpp) - C++ 的 ROS 客户端库. ![rclcpp](https://img.shields.io/github/stars/ros2/rclcpp.svg)
- [rclgo](https://github.com/juaruipav/rclgo) - 用于 Go 的 ROS 客户端库. ![rclgo](https://img.shields.io/github/stars/juaruipav/rclgo.svg)
- [rclpy](https://github.com/ros2/rclpy) - Python 的 ROS 客户端库. ![rclpy](https://img.shields.io/github/stars/ros2/rclpy.svg)
- [rcljava](https://github.com/esteve/ros2_java/tree/master/rcljava) - 用于 Java 的 ROS 客户端库. ![rcljava](https://img.shields.io/github/stars/esteve/ros2_java.svg)
- [rclnodejs](https://github.com/RobotWebTools/rclnodejs) - 用于 Node.js 的 ROS 客户端库. ![rclnodejs](https://img.shields.io/github/stars/RobotWebTools/rclnodejs.svg)
- [rclobjc](https://github.com/esteve/ros2_objc) - 用于 Objective C 的 ROS 客户端库（适用于 iOS）. ![rclobjc](https://img.shields.io/github/stars/esteve/ros2_objc.svg)
- [rclc](https://github.com/ros2/rclc) - C 的 ROS 客户端库. ![rclc](https://img.shields.io/github/stars/ros2/rclc.svg)
- [ros2_rust](https://github.com/ros2-rust/ros2_rust) - ROS2 的 Rust 绑定. ![ros2_rust](https://img.shields.io/github/stars/esteve/ros2_rust.svg)
- [ros2_dotnet](https://github.com/esteve/ros2_dotnet) - ROS2 的 .NET 绑定. ![ros2_dotnet](https://img.shields.io/github/stars/esteve/ros2_dotnet.svg)
- [ros2cs](https://github.com/RobotecAI/ros2cs) - an alternative to ros2_dotnet, a ROS2 C# interface supporting full range of messages and modern ROS2. ![ros2cs](https://img.shields.io/github/stars/RobotecAI/ros2cs.svg)

### Client libraries common

- [rcl](https://github.com/ros2/rcl) - 支持特定语言 ROS 客户端库的实现的库. ![rcl](https://img.shields.io/github/stars/ros2/rcl.svg)
- [system_tests](https://github.com/ros2/system_tests) - 测试 rclcpp 和 rclpy. ![system_tests](https://img.shields.io/github/stars/ros2/system_tests.svg)
- [rcl_interfaces](https://github.com/ros2/rcl_interfaces) - ROS 客户端库使用的消息和服务存储库. ![rcl_interfaces](https://img.shields.io/github/stars/ros2/rcl_interfaces.svg)

### IDL generators

- [rosidl_generator_java](https://github.com/esteve/ros2_java/tree/master/rosidl_generator_java) - 用 Ja​​va 生成 ROS 接口. ![ros2_java](https://img.shields.io/github/stars/esteve/ros2_java.svg)
- [rosidl_generator_objc](https://github.com/esteve/ros2_objc/tree/master/rosidl_generator_objc) - 在 Objective C 中生成 ROS 接口. ![ros2_objc](https://img.shields.io/github/stars/esteve/ros2_objc.svg)
- [rosidl_generator_cpp](https://github.com/ros2/rosidl/tree/master/rosidl_generator_cpp) - 在 C++ 中生成 ROS 接口. ![rosidl](https://img.shields.io/github/stars/ros2/rosidl.svg)
- [rosidl_generator_c](https://github.com/ros2/rosidl/tree/master/rosidl_generator_c) - 在 C 中生成 ROS 接口. ![rosidl](https://img.shields.io/github/stars/ros2/rosidl.svg)
- [rosidl](https://github.com/ros2/rosidl) - 提供 ROS IDL (.msg) 定义和代码生成的包. ![rosidl](https://img.shields.io/github/stars/ros2/rosidl.svg)
- [rosidl_dds](https://github.com/ros2/rosidl_dds) - 为 ROS 接口生成 DDS 接口. ![rosidl_dds](https://img.shields.io/github/stars/ros2/rosidl_dds.svg)

### RMW (ROS middleware)

- [rmw](https://github.com/ros2/rmw/tree/master/rmw) - 包含 ROS 中间件 API. ![rmw](https://img.shields.io/github/stars/ros2/rmw.svg)
- [rmw_connext_cpp](https://github.com/ros2/rmw_connext/tree/master/rmw_connext_cpp) - 使用 C++ 中的 RTI Connext 静态代码生成实现 ROS 中间件接口. ![rmw_connext_cpp](https://img.shields.io/github/stars/ros2/rmw_connext.svg)
- [rmw_fastrtps_cpp](https://github.com/ros2/rmw_fastrtps/tree/master/rmw_fastrtps_cpp) - 使用 C++ 中的 eProsima FastRTPS 静态代码生成实现 ROS 中间件接口. ![rmw_fastrtps_cpp](https://img.shields.io/github/stars/ros2/rmw_fastrtps.svg)
- [rmw_dps](https://github.com/ros2/rmw_dps) - 使用英特尔的分布式发布和订阅实现 ROS 中间件 (rmw) 接口. ![rmw_dps](https://img.shields.io/github/stars/ros2/rmw_dps.svg)
- [rmw_opensplice_cpp](https://github.com/ros2/rmw_opensplice/tree/master/rmw_opensplice_cpp) - 使用 C++ 中的 PrismTech OpenSplice 静态代码生成实现 ROS 中间件接口. ![rmw_opensplice_cpp](https://img.shields.io/github/stars/ros2/rmw_opensplice.svg)
- [rmw_coredx](https://github.com/tocinc/rmw_coredx) - ROS2 的 CoreDX DDS 集成层. ![tocinc/rmw_coredx](https://img.shields.io/github/stars/tocinc/rmw_coredx.svg)
- [rmw_freertps](https://github.com/ros2/rmw_freertps) - 使用 freertps 的 RMW 实现. ![tocinc/rmw_coredx](https://img.shields.io/github/stars/ros2/rmw_freertps.svg)
- [rmw_zenoh](https://github.com/atolab/rmw_zenoh) - 使用 Eclipse zenoh 的 RMW 实现：零开销发布/订阅、存储/查询和计算. ![atolab/rmw_zenoh](https://img.shields.io/github/stars/atolab/rmw_zenoh.svg)
- [rcutils](https://github.com/ros2/rcutils) - ROS 2 中使用的常用 C 函数和数据结构. ![rmw](https://img.shields.io/github/stars/ros2/rcutils.svg)
- [freertps](https://github.com/ros2/freertps) - 一个免费的、便携的、极简主义的、正在进行中的 RTPS 实现. ![rmw](https://img.shields.io/github/stars/ros2/freertps.svg)
- [rmw_cyclonedds](https://github.com/atolab/rmw_cyclonedds) - 用于 Eclipse Cyclone DDS 的 ROS2 RMW 层. ![rmw_cyclonedds](https://img.shields.io/github/stars/atolab/rmw_cyclonedds.svg)
- [rmw_zenoh](https://github.com/atolab/rmw_zenoh) - ROS2 RMW 层 [zenoh](https://zenoh.io).
- [rmw_iceoryx](https://github.com/ros2/rmw_iceoryx) - 启用进程间通信中间件的使用 [Eclipse iceoryx](https://iceoryx.io).

### DDS communication mechanism implementations

- [Connext DDS](https://www.rti.com/products/connext-dds-professional)  - 用于开发和集成 IIoT 系统的连接软件.  :heavy_dollar_sign:
- [Fast-RTPS](https://github.com/eProsima/Fast-RTPS) - RTPS 标准的实施（RTPS 是 DDS 的有线互操作性协议）. ![Fast-RTPS](https://img.shields.io/github/stars/eProsima/Fast-RTPS.svg)
- [OpenSplice](https://github.com/ADLINK-IST/opensplice) - 实施 OMG DDS 标准. ![opensplice](https://img.shields.io/github/stars/ADLINK-IST/opensplice.svg) :heavy_dollar_sign:
- [CoreDX DDS](http://www.twinoakscomputing.com/coredx) - Twin Oaks Computing, Inc. 的实施：heavy_dollar_sign：
- [freertps](https://github.com/ros2/freertps) - 一个免费的、可移植的、极简主义的、正在进行中的 RTPS 实现. ![freertps](https://img.shields.io/github/stars/ros2/freertps.svg)
- [cdds](https://github.com/atolab/cdds) - Cyclone DDS 完全开放开发，正在接受成为 Eclipse IoT 一部分的过程. ![cdds](https://img.shields.io/github/stars/atolab/cdds.svg)
- [Micro-XRCE-DDS)](https://github.com/eProsima/Micro-XRCE-DDS) - XRCE DDS 实现（由 microROS 支持）. ![Micro-XRCE-DDS](https://img.shields.io/github/stars/eProsima/Micro-XRCE-DDS.svg)

### Build system (Linux)

- [meta-ros2](https://github.com/erlerobot/meta-ros2) - 用于 OpenEmbedded Linux 的 ROS 2 层. ![meta-ros2](https://img.shields.io/github/stars/erlerobot/meta-ros2.svg)

### Build system (ROS2)

- [ci](https://github.com/ros2/ci) - ROS 2 CI 基础设施. ![ci](https://img.shields.io/github/stars/ros2/ci.svg)
- [ament_cmake_export_jars](https://github.com/esteve/ros2_java/tree/master/ament_cmake_export_jars) - 能够将 Java 存档导出到 CMake 中的 ament 构建系统中的下游包. ![ros2_java](https://img.shields.io/github/stars/esteve/ros2_java.svg)
- [rmw_implementation_cmake](https://github.com/ros2/rmw/tree/master/rmw_implementation_cmake) - 可以发现和枚举可用实现的 CMake 函数. ![rmw](https://img.shields.io/github/stars/ros2/rmw.svg)
- [rmw_implementation](https://github.com/ros2/rmw_implementation) - 用于 rmw 实现的 CMake 基础设施和依赖项. ![rmw](https://img.shields.io/github/stars/ros2/rmw_implementation.svg)

## Operating systems

- [NuttX](https://github.com/micro-ROS/NuttX) - 用于微型 ROS 的官方 NuttX 分支.
- [RIOT](https://github.com/RIOT-OS/RIOT) - RIOT 是一个实时多线程操作系统（...，）实时功能，内存占用小，（...）API 提供部分 POSIX 合规性.
- [eMCOS](https://www.esol.com/embedded/emcos.html) - 符合 POSIX 标准的实时操作系统，适用于未来有望支持 AUTOSAR 的多核处理器.
- [PYNQ](http://www.pynq.io/) - 在 XILINX FPGA 上运行的高性能 ML 应用程序的基于 Python 的快速原型设计.
- [ReconROS](https://github.com/Lien182/ReconROS)  - 基于 ROS2 FPGA 的硬件加速框架. 基于 [ReconOS](https://github.com/reconos/reconos). ![ReconROS](https://img.shields.io/github/stars/Lien182/ReconROS.svg)
- [Ubuntu Core](https://ubuntu.com/core) - 使用 Ubuntu Core 构建安全的物联网设备.
- [Ubuntu Server](https://ubuntu.com/server)
- [VxWorks](https://github.com/Wind-River/vxworks7-ros2-build) - 用于关键基础设施的安全、安全、可靠和可认证的实时操作系统
- [Zephyr](https://www.zephyrproject.org/) - 旨在确保安全的 Linux 基金会项目 RTOS.

## Packaging

- [ros2-snap](https://snapcraft.io/docs/ros2-applications) - 为您的 ROS 2 应用程序创建快照.

## Forks

- [Apex.OS](https://www.apex.ai/apex-os) - Apex.OS 是 ROS 2 的一个分支，它已经变得非常强大和可靠，可以用于安全关键型应用程序.

## Documentation

- [ROS Index](https://index.ros.org/) - 未来进入 ROS2 文档（BETA）的单一入口点.
  - [Foxy packages](https://index.ros.org/packages/page/1/time/#foxy).
  - [Dashing packages](https://index.ros.org/packages/page/1/time/#dashing).
  - [Crystal packages](https://index.ros.org/packages/page/1/time/#crystal).
  - [Bouncy packages](https://index.ros.org/packages/page/1/time/#bouncy).
  - [Ardent packages](https://index.ros.org/packages/page/1/time/#ardent).
- [ROS 2 Design](http://design.ros2.org/) - 为 ROS 2.0 设计工作提供信息和指导的文章.
- [ROS 2 Docs (Overview)](http://docs.ros2.org/beta2/index.html#) - 有关 ROS 2 内部设计和组织的详细信息.
- [ROS 2 Tutorials](https://github.com/ros2/ros2/wiki/Tutorials) - 通过演示/示例研究 ROS2 概念、库、构建和开发.
- [ROS 2 Wiki](https://github.com/ros2/ros2/wiki) - 查找有关 ROS 2 的各种信息的入口点.
- [ROS 2 Distribution (rosdistro)](https://github.com/ros2/rosdistro) - 有关发行版和包含的软件包的信息.
- [ROS2 package status](http://repo.ros2.org/).
  - [Bouncy package status](http://repo.ros2.org/status_page/ros_bouncy_default.html) - ROS Bouncy 包的状态.
  - [Ardent package status](http://repo.ros2.org/status_page/ros_ardent_default.html) - ROS2 Ardent 软件包的状态.
- [ROS2 Buildfarm](http://build.ros2.org) - 构建信息（Jenkins 构建农场）.
- [ROS2 CLI cheats sheet](https://github.com/artivis/ros2_cheats_sheet/blob/master/cli/cli_cheats_sheet.pdf) - ROS 2 命令行界面备忘单.
- [ROS2 Quality Assurance Guidelines](https://github.com/ros-industrial/ros2_quality_assurance_guidelines) - 一系列用于提高包质量的指南和教程，遵循 REP-2004 质量标准并集成持续集成.


## Community

- [ROS Discourse](https://discourse.ros.org/c/ng-ros)
- [ROS Answers](https://answers.ros.org/questions/scope:all/sort:activity-desc/tags:ROS2/)
- [ROS News](http://www.ros.org/news/)
- [ROS Planet](http://planet.ros.org/)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/ros2)

## Books

- [A Concise Introduction to Robot Programming with ROS2](https://github.com/fmrico/book_ros2)

## Courses

- [ROS2 How To: Discover Next Generation ROS (Udemy)](https://www.udemy.com/ros2-how-to/)
- [ROS 2 New Features: Skill-up with the latest features of Robot Operating System 2  (Udemy)](https://www.udemy.com/course/ros-2-new-features/)
- [ROS 2 Basics in 5 Days (C++) - Learn how to start working with ROS 2 (The Construct)](http://www.theconstructsim.com/construct-learn-develop-robots-using-ros/robotigniteacademy_learnros/ros-courses-library/ros2-basics-course/)
- ROS2 Autoware课程
  - [Autoware Course Lecture 1: Development Environment](https://www.youtube.com/watch?v=XTmlhvlmcf8)
  - [Autoware Course Lecture 2: ROS2 101](https://www.youtube.com/watch?v=FTA4Ia2vLS8)
  - [Autoware Course Lecture 3: ROS 2 Tooling - Develop Like a Pro](https://www.youtube.com/watch?v=wcibIqiRb04)
  - [Autoware Course Lecture 4: Platform HW, RTOS and DDS](https://www.youtube.com/watch?v=IyycN6ldsIs)
  - [Autoware Course Lecture 5: Autonomous Driving Stacks](https://www.youtube.com/watch?v=nTI4fnn2tuU)
  - [Autoware Course Lecture 6: Autoware 101](https://www.youtube.com/watch?v=eSHHmJrqpMU)
  - [Autoware Course Lecture 7: Object Perception: LIDAR](https://www.youtube.com/watch?v=xSGCpb24dhI)
  - [Autoware Course Lecture 8: Object Perception: CAMERA](https://www.youtube.com/watch?v=OtjTa-meJ-E)
  - [Autoware Course Lecture 9: Object Perception: Radar](https://www.youtube.com/watch?v=PcVIO-xoNv8)
  - [Autoware Course Lecture 10: State Estimation for Localization](https://www.youtube.com/watch?v=g2YURb-d9vY)
  - [Autoware Course Lecture 11: LGSVL Simulator](https://www.youtube.com/watch?v=OcB6FUbjZXo)
  - [Autoware Course Lecture 12: Motion Control](https://www.youtube.com/watch?v=fQJpAVRQBrI)
- [ROS2-Industrial training material](https://github.com/ros-industrial/ros2_i_training)

## Presentations

### ROSCon 2022

[Program announcement](https://roscon.ros.org/2022/#program)（幻灯片+视频）
- 面板：ROS 2 开发者体验 [video](https://vimeo.com/showcase/9954564/video/767155188)
- 可穿戴 ROS：使用 ROS 2 开发可穿戴机器人系统 [video](https://vimeo.com/showcase/9954564/video/767140298) [slides](http://download.ros.org/downloads/roscon/2022/Wearable%20ROS%20Development%20of%20wearable%20robot%20system%20using%20ROS2.pdf)
- 使用 C++ 构建支持 ROS 2 的 Android 应用程序 [video](https://vimeo.com/showcase/9954564/video/767161955) [slides](http://download.ros.org/downloads/roscon/2022/Building%20ROS%202%20enabled%20Android%20apps%20with%20C++.pdf)
- 带有虚幻引擎的分布式机器人模拟器 [video](https://vimeo.com/showcase/9954564/video/767139975) [slides](http://download.ros.org/downloads/roscon/2022/Distributed%20Robotics%20Simulator%20with%20Unreal%20Engine.pdf)
- 提高 ROS 2 可认证性的工具和流程 [video](https://vimeo.com/showcase/9954564/video/767150613) [slides](http://download.ros.org/downloads/roscon/2022/Tools%20and%20processes%20for%20improving%20the%20certifiability%20of%20ROS%202.pdf)
- 故障转移 ROS 框架：基于共识的节点冗余 [video](https://vimeo.com/showcase/9954564/video/767156308) [slides](http://download.ros.org/downloads/roscon/2022/Failover%20ROS%20Framework%20Consensus-based%20node%20redundancy.pdf)
- ROS 2 和 Gazebo 集成最佳实践 [video](https://vimeo.com/showcase/9954564/video/767127300) [slides](http://download.ros.org/downloads/roscon/2022/ROS%202%20and%20Gazebo%20Integration%20Best%20Practices.pdf)
- 链感知 ROS 评估工具 (CARET) [video](https://vimeo.com/showcase/9954564/video/767150288) [slides](http://download.ros.org/downloads/roscon/2022/Chain-Aware%20ROS%20Evaluation%20Tool%20(CARET).pdf)
- ROS 2网络监控 [video](https://vimeo.com/showcase/9954564/video/767140681) [slides](http://download.ros.org/downloads/roscon/2022/ROS%202%20network%20monitoring.pdf)
- 如何在 Open-RMF 中定义、分配和执行自定义任务 [video](https://vimeo.com/showcase/9954564/video/767157210) [slides](http://download.ros.org/downloads/roscon/2022/How%20custom%20tasks%20are%20defined,%20assigned,%20and%20executed%20in%20Open-RMF.pdf)
- ros2_control 从业者指南 [video](https://vimeo.com/showcase/9954564/video/767139648) [slides](http://download.ros.org/downloads/roscon/2022/A%20practitioner_s%20guide%20to%20ros2_control.pdf)
- Zenoh：如何使 ROS 2 在任何规模下工作并与任何东西集成 [video](https://vimeo.com/769972405) [slides](http://download.ros.org/downloads/roscon/2022/Zenoh%20How%20to%20Make%20ROS2%20Work%20at%20any%20Scale%20and%20Integrate%20with%20Anything.pdf)
- 使用 MoveIt2 和 ros2_control 进行光学制造的案例研究 [video](https://vimeo.com/showcase/9954564/video/767140351) [slides](http://download.ros.org/downloads/roscon/2022/A%20case%20study%20in%20optics%20manufacturing%20with%20MoveIt2%20and%20ros2_control.pdf)
- 20/20 Robot Vision - 如何使用 camera_aravis 在 ROS 1 和 ROS 2 中设置相机 [video](https://vimeo.com/showcase/9954564/video/767140329) [slides](http://download.ros.org/downloads/roscon/2022/20%20-%2020%20Robot%20Vision%20-%20How%20to%20setup%20cameras%20in%20ROS%201%20&%20ROS%202%20using%20camera_aravis.pdf)
- 过滤您的 ROS 2 内容 [video](https://vimeo.com/767166447) [slides](http://download.ros.org/downloads/roscon/2022/Filter%20your%20ROS%202%20content.pdf)
- 随着时间的推移不断发展的消息类型和其他接口 [video](https://vimeo.com/showcase/9954564/video/767140015) [slides](http://download.ros.org/downloads/roscon/2022/Evolving%20Message%20Types,%20and%20Other%20Interfaces,%20Over%20Time.pdf)
- 从 ROS1 迁移到 ROS 2 - 选择正确的桥 [video](https://vimeo.com/showcase/9954564/video/767140113) [slides](http://download.ros.org/downloads/roscon/2022/Migrating%20from%20ROS1%20to%20ROS2%20-%20choosing%20the%20right%20bridge.pdf)
- 关于 Nav2 Smac Planners 的使用 [video](https://vimeo.com/showcase/9954564/video/767157646) [slides](http://download.ros.org/downloads/roscon/2022/On%20Use%20of%20Nav2%20Smac%20Planners.pdf)
- Bazel 和 ROS 2 – 构建大规模安全应用程序 [video](https://vimeo.com/showcase/9954564/video/767139879) [slides](http://download.ros.org/downloads/roscon/2022/Bazel%20and%20ROS%202%20%E2%80%93%20building%20large%20scale%20safety%20applications.pdf)
- ROS 2 的原生 Rust 组件 [video](https://vimeo.com/showcase/9954564/video/767140150) [slides](http://download.ros.org/downloads/roscon/2022/Native%20Rust%20components%20for%20ROS2.pdf)
- The ROS build farm and you：你发布的 ROS 包如何变成二进制包. [video](https://vimeo.com/showcase/9954564/video/767169376) [slides](http://download.ros.org/downloads/roscon/2022/The%20ROS%20build%20farm%20and%20you%20How%20ROS%20packages%20you%20release%20become%20binary%20packages.pdf)
- mROS 2：嵌入式设备上的另一个运行时环境 [video](https://vimeo.com/showcase/9954564/video/767150435) [slides](http://download.ros.org/downloads/roscon/2022/mROS%202%20yet%20another%20runtime%20environment%20onto%20embedded%20devices.pdf)
- ROS 2 和 Edge Impulse：机器人应用中的嵌入式 AI [video](https://vimeo.com/showcase/9954564/video/767140724) [slides](http://download.ros.org/downloads/roscon/2022/ROS2%20_%20Edge%20Impulse%20Embedded%20AI%20in%20robotics%20applications.pdf)
- 微型 ROS 走向汽车：支持基于 AUTOSAR 的微控制器 [video](https://vimeo.com/769963507) [slides](http://download.ros.org/downloads/roscon/2022/micro-ROS%20goes%20Automotive%20supporting%20AUTOSAR-based%20microcontrollers.pdf)
- ROS 2 中硬件加速的开放架构 [video](https://vimeo.com/769967795) [slides](http://download.ros.org/downloads/roscon/2022/An%20open%20architecture%20for%20Hardware%20Acceleration%20in%20ROS%202.pdf)
- ROS 2 和 Crazyflie：带有微型飞行机器人的空中蜂群和自治 [video](https://vimeo.com/showcase/9954564/video/767140197) [slides](http://download.ros.org/downloads/roscon/2022/ROS%202%20and%20the%20Crazyflie%20Aerial%20swarms%20and%20Autonomy%20with%20a%20tiny%20flying%20robot.pdf)
- 带有 ROS 2 + RT 和可定制图像生成器的 Raspberry Pi 图像 [video](https://vimeo.com/showcase/9954564/video/767139709) [slides](http://download.ros.org/downloads/roscon/2022/A%20Raspberry%20Pi%20image%20with%20ROS%202%20%2B%20RT%20and%20a%20customizable%20image%20builder.pdf)

### ROSCon 2021

[Program announcement](https://roscon.ros.org/world/2021/#program)（幻灯片+视频）

### ROSCon Jp 2021

[Program announcement](https://roscon.ros.org/jp/2021/#program)（幻灯片+视频）

### ROSCon 2020

[Program announcement](https://roscon.ros.org/world/2020/#program)（幻灯片+视频）

### ROSCon 2019

[Program announcement](https://roscon.ros.org/2019/#program)（幻灯片+视频）

### ROSCon Fr 2019

[Program announcement](https://roscon.fr/#program)（幻灯片+视频）

### ROS-I EU Spring 2019 Workshop

- ROS 2 实践功能概述的当前状态 [Slides](https://static1.squarespace.com/static/51df34b1e4b08840dcfd2841/t/5ce6c85ca4222fe0ccbd5309/1558628472094/2019-05-07_Current_Status_of_ROS_2.pdf)

### 2019

- 机器人模块化与 Xilinx 和 H-ROS (Xilinx Inc.) [Video](https://www.xilinx.com/video/events/robot-modularity-with-xilinx-and-h-ros.html)

### ROSCon JP 2018 (english slide presentations only)

 - ROS 的下一步是什么？  （从幻灯片 24 开始） [Slides](https://roscon.jp/2018/presentations/ROSCon_JP_2018_presentation_2.pdf) [Video](https://vimeo.com/292064161)

### ROSCon 2018

[program announcement](https://roscon.ros.org/2018/#program)

- 动手 ROS 2：演练
- 自动驾驶汽车上的 ROS 2
- RViz——迁移到 ROS 2.0 的故事
- 启动 ROS 2
- 参与 ROS 2 开发
- 计划到计划：插件一路向下
- 在 ROS2 中利用 DDS 安全性
- Arm DDS 安全库：为 ROS2 添加安全性
- ROS2：为 Jaguar4x4 增压
- 性能测试-通信中间件性能测量工具
- ROS2 for Android, iOS and Universal Windows Platform：展示ROS2的可移植性，以及跨平台和跨语言的能力
- 在基于嵌入式异构平台的混合关键机器人系统上集成 ROS 和 ROS2
- 迈向 ROS 2 微控制器元交叉编译
- 为 ROS 2.0 准备的 Node.js 客户端和网络桥
- RCLAda：ROS2 的 Ada 客户端库

### Embedded World Conference 2018

- ADLink Neuron：面向工业的基于 ROS2 的平台 [Slides](https://raw.githubusercontent.com/Adlink-ROS/adlink_neuronbot/master/document/ADLINK_NeuronBot_20180313.pdf) [Video](https://www.youtube.com/watch?v=RC6XvTvTs9Y&feature=youtu.be) [Video](https://www.youtube.com/watch?v=qA4_Hmnd_tM&feature=youtu.be)

### 2018

- ROS2 - 机器人操作系统版本 2（TNG Technology Consulting GmbH） [Slides](https://www.tngtech.com/fileadmin/Public/Images/BigTechday/BTD11/Folien/ROS2.pdf) [Video](https://www.youtube.com/watch?v=6Vzi0Grrlp8)

### ROS Industrial Conference 2017

- 微型机器人操作系统：用于高度资源受限设备的 ROS [Slides](https://static1.squarespace.com/static/51df34b1e4b08840dcfd2841/t/5a3bb6d524a6947d9d0cbc68/1513862873907/07_Losa.pdf)
- ROS2 - 它来了 [Slides](https://static1.squarespace.com/static/51df34b1e4b08840dcfd2841/t/5a3bb787e4966b606fe227d7/1513863070599/11_Thomas.pdf)

### ROSCon 2017

- 推动机器人技术发展未来的 ROS 2 愿景 [Slides](https://roscon.ros.org/2017/presentations/ROSCon%202017%20ROS2%20Vision.pdf) [Video](https://vimeo.com/236161417)
- ROS2微调 [Slides](https://roscon.ros.org/2017/presentations/ROSCon%202017%20ROS2%20Fine%20Tuning.pdf) [Video](https://vimeo.com/236168591)
- 使用 ROS2 在 Turtlebot2 上进行 SLAM [Slides](https://roscon.ros.org/2017/presentations/ROSCon%202017%20ROS2%20SLAM.pdf) [Video](https://vimeo.com/236172294)
- 使用 ROS2 对工业机器人进行基于视觉的操作 [Slides](https://roscon.ros.org/2017/presentations/ROSCon%202017%20ROS2%20Vision-Based%20Manipulation.pdf) [Video](https://vimeo.com/236182180)

### 2017

- HyphaROS ROS 2.0介绍 [slides](https://drive.google.com/file/d/1MW_w7MS1DNg1EzhprgbJKY2cqmxksPaw/view)

### ROS Industrial Conference 2016

- ROS 2.0 和 OPC UA：状态更新 [Slides](https://static1.squarespace.com/static/51df34b1e4b08840dcfd2841/t/58235f2eb8a79be587899891/1478713139775/ROS-I-Conf2016-day1-09-keinert.pdf)

### ROSCon 2016

- ROS 2 更新 [Slides](https://roscon.ros.org/2016/presentations/ROSCon%202016%20-%20ROS%202%20Update.pdf) [Video](https://vimeo.com/187696091)
- 评估 ROS2 通信层的弹性 [Slides](https://roscon.ros.org/2016/presentations/rafal.kozik-ros2evaluation.pdf) [Video](https://vimeo.com/187705229)

### ROSCon 2015

- “小型”嵌入式系统上的 ROS 2 [Slides](https://roscon.ros.org/2015/presentations/ros2_on_small_embedded_systems.pdf) [Video](https://vimeo.com/142150576)
- ROS 2 状态 - 演示和背后的技术 [Slides](https://roscon.ros.org/2015/presentations/state-of-ros2.pdf) [Video](https://vimeo.com/142151734)
- ROS 2 中的实时性能 [Slides](https://roscon.ros.org/2015/presentations/RealtimeROS2.pdf) [Video](https://vimeo.com/142621778)

## Papers

- [Distributed and Synchronized Setup towards Real-Time Robotic Control using ROS2 on Linux](https://www.semanticscholar.org/paper/Distributed-and-Synchronized-Setup-towards-Robotic-Puck-Keller/10c4eeef9da0c5aa87664037f18a0ab746853757)
- [Time Synchronization in modular collaborative robots](https://arxiv.org/pdf/1809.07295.pdf)
- [Open Problems in Robotic Anomaly Detection](https://arxiv.org/pdf/1809.03565.pdf)
- [Towards a distributed and real-time framework for robots: Evaluation of ROS 2.0 communications for real-time robotic applications](https://arxiv.org/pdf/1809.02595.pdf)
- [An information model for modular robots: the Hardware Robot Information Model (HRIM)](https://arxiv.org/pdf/1802.01459.pdf)
- [Introducting the Robot Security Framework (RSF), A standardized methodology to perform security assessments in robotics](https://arxiv.org/pdf/1806.04042.pdf)
- [Towards an open standard for assessing the severity of robot security vulnerabilities, The Robot Vulnerability Scoring System (RVSS)](https://arxiv.org/pdf/1807.10357.pdf)
- [Real-Time Characteristics of ROS 2.0 in Multiagent Robot Systems: An Empirical Study](https://www.semanticscholar.org/paper/Real-Time-Characteristics-of-ROS-2.0-in-Multiagent-Park-Delgado/8fa5b9443b33dd20c33be9a4259d92b238310a5c)
- [Response-Time Analysis of ROS 2 Processing Chains Under Reservation-Based Scheduling](https://www.semanticscholar.org/paper/Response-Time-Analysis-of-ROS-2-Processing-Chains-Casini-Bla%C3%9F/6fa472cc45f6de22f2a26114441d595534a80a92)
- [Robot Operating System 2 - The need for a holistic security approach to robotic architectures](http://journals.sagepub.com/doi/pdf/10.1177/1729881418770011) - Ubuntu 16.04、ROS 2 Beta 2/3 和 RTI 5.3 DDS
DDS 安全.
- [Maruyama, Yuya et al. “Exploring the performance of ROS2.” 2016 International Conference on Embedded Software (EMSOFT) (2016): 1-10.](https://www.semanticscholar.org/paper/Exploring-the-performance-of-ROS2-Maruyama-Kato/07b895f3b584dea4f64e91844f243de382026b20)

## Podcasts

- [ROS 2 and DDS for IoT devices with HaoChih Lin (from 5th minute onwards)](http://www.theconstructsim.com/rdp-017-ros-2-dds-iot-haochih/)
- [Everything about ROS 2 with Dirk Thomas (from 16th minute onwards)](http://www.theconstructsim.com/rdp-012-all-about-ros2-with-dirk-thomas/)

## Services

### Cloud robotics

- [robolaunch](https://www.robolaunch.io/)

### Robotics Capture the Flag (RCTF)

- [rctf-list](https://github.com/aliasrobotics/RCTF) - 机器人 CTF (RCTF) 场景列表.

## Companies

- [Acutronic Robotics](https://github.com/AcutronicRobotics)  - 不存在了. 硬件机器人信息模型（HRIM）、硬件机器人操作系统（H-ROS）的发起人，世界第一台模块化工业机械臂MARA的创造者.
- [ADLINK](https://www.adlinktech.com/en/index.aspx) - “前沿计算”.
- [Alias Robotics](https://aliasrobotics.com/) - 机器人网络安全背景下的产品和服务.
- [Amazon](https://github.com/aws-robotics) - Amazon Amazon Web Services (AWS) 的机器人团队.
- [Apex.AI](https://www.apex.ai/) - “用于自主移动的安全且经过认证的软件”.
- [AutonomouStuff](https://autonomoustuff.com) - “自治系统和解决方案的世界领导者”.
- [Bosch](https://github.com/boschresearch) - 博世研究机器人团队.
- [Canonical](https://canonical.com/) - Ubuntu背后的公司.
- [Eprosima](https://www.eprosima.com/) ——《中间件专家》.
- [Ericsson Research](https://discourse.ros.org/t/transport-priority-qos-policy-to-solve-ip-flow-ambiguity-while-requesting-5g-network-qos/15332) - 将 ROS2 应用程序连接到 5G 网络以进行 M2M 通信.
- [FARobot](https://www.farobottech.com/) - Swarm 机器人系统，一个基于 ROS 2/DDS 的车队管理系统.
- [Fraunhofer Institute for Manufacturing Engineering and Automation IPA](https://www.ipa.fraunhofer.de/en/expertise/robot-and-assistive-systems.html) - 机器人和辅助系统.
- [GESTALT ROBOTICS](https://www.gestalt-robotics.com/en/home) - 智能自动化服务提供商.
- [Husarnet](https://husarnet.com) - 专用于机器人的开源、P2P、低延迟 VPN.
- [iRobot](https://www.irobot.de/) - 吸尘和拖地机器人制造商.
- [Klepsydra Technologies](https://www.klepsydra.com/).
- [MathWorks](https://de.mathworks.com/help/ros/index.html) - ROS 工具箱.
- [Mission Robotics](https://missionrobotics.us/) - 面向海洋智能新时代的硬件和软件.
- [Roboception GmbH](https://roboception.com/en/) - 机器人的实时感知.
- [ROBOOX](https://roboox.co/) - 用于消费类机器人的开源软件生态系统.
- [Rover Robotics](https://roverrobotics.com/) - Rugged, industrial-grade robots.
- [Sony Corporation](https://www.sony.net/SonyInfo/technology/element/robotics/).
- [synapticon](https://www.synapticon.com/technology) - ROS兼容的运动控制和驱动产品，努力支持ROS2.
- [Wind River](https://labs.windriver.com/ros2-for-vxworks/) - VxWorks 的 ROS2.

## Organizations

- [U.S. Department of Transportation](https://discourse.ros.org/t/carma-migrating-to-ros-2-with-cyclonedds-and-zenoh/17541)

## Working Groups

- 边缘人工智能工作组
  - [Discourse threads tagged "wg-edgeai"](https://discourse.ros.org/tag/wg-edgeai)
- 嵌入式工作组
  - [Discourse threads tagged "wg-embedded"](https://discourse.ros.org/tags/wg-embedded)
- 硬件加速工作组
  - [Discourse threads tagged "wg-acceleration"](https://discourse.ros.org/tag/wg-acceleration)
- 导航工作组
  - [Discourse threads tagged "wg-navigation"](https://discourse.ros.org/tags/wg-navigation)
- 安全工作组
  - [Safety Working Group Landing Page](http://www.ros2.org/safety_working_group/)
  - [Safety Design Pattern Catalogue](http://www.ros2.org/safety_working_group/safety_patterns_catalogue.html)
- 安全工作组
  - [Discourse threads tagged "wg-security"](https://discourse.ros.org/tags/wg-security)
  - [ros-security/community](https://github.com/ros-security/community) - 概述了 ROS 2 安全工作组的治理.
- 技术指导委员会
  - [Discourse threads tagged "tsc"](https://discourse.ros.org/tags/tsc)
- Tooling Working Group
  - [Discourse threads tagged "wg-tooling"](https://discourse.ros.org/tags/wg-tooling)

## License

[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
