# Errors I got when getting Spot_driver to work
- ***12/18/2025***:
[INFO] [launch]: All log files can be found below /root/.ros/log/2025-12-19-05-17-21-542102-SpotCORE-15506
[INFO] [launch]: Default logging verbosity is set to INFO
[INFO] [controller_server-1]: process started with pid [15507]
[INFO] [smoother_server-2]: process started with pid [15509]
[INFO] [planner_server-3]: process started with pid [15511]
[INFO] [behavior_server-4]: process started with pid [15513]
[INFO] [bt_navigator-5]: process started with pid [15515]
[INFO] [waypoint_follower-6]: process started with pid [15517]
[INFO] [velocity_smoother-7]: process started with pid [15519]
[INFO] [lifecycle_manager-8]: process started with pid [15521]
[lifecycle_manager-8] [INFO] [1766121441.756484297] [lifecycle_manager_navigation]: Creating
[waypoint_follower-6] [INFO] [1766121441.758913630] [waypoint_follower]:
[waypoint_follower-6]   waypoint_follower lifecycle node launched.
[waypoint_follower-6]   Waiting on external lifecycle transitions to activate
[waypoint_follower-6]   See https://design.ros2.org/articles/node_lifecycle.html for more information.
[lifecycle_manager-8] [INFO] [1766121441.764575692] [lifecycle_manager_navigation]: Creating and initializing lifecycle service clients
[waypoint_follower-6] [INFO] [1766121441.766304711] [waypoint_follower]: Creating
[planner_server-3] [INFO] [1766121441.766397714] [planner_server]:
[planner_server-3]      planner_server lifecycle node launched.
[planner_server-3]      Waiting on external lifecycle transitions to activate
[planner_server-3]      See https://design.ros2.org/articles/node_lifecycle.html for more information.
[planner_server-3] [INFO] [1766121441.773260811] [planner_server]: Creating
[behavior_server-4] [INFO] [1766121441.774432215] [behavior_server]:
[behavior_server-4]     behavior_server lifecycle node launched.
[behavior_server-4]     Waiting on external lifecycle transitions to activate
[behavior_server-4]     See https://design.ros2.org/articles/node_lifecycle.html for more information.
[velocity_smoother-7] [INFO] [1766121441.778257019] [velocity_smoother]:
[velocity_smoother-7]   velocity_smoother lifecycle node launched.
[velocity_smoother-7]   Waiting on external lifecycle transitions to activate
[velocity_smoother-7]   See https://design.ros2.org/articles/node_lifecycle.html for more information.
[planner_server-3] [INFO] [1766121441.787011898] [global_costmap.global_costmap]:
[planner_server-3]      global_costmap lifecycle node launched.
[planner_server-3]      Waiting on external lifecycle transitions to activate
[planner_server-3]      See https://design.ros2.org/articles/node_lifecycle.html for more information.
[smoother_server-2] [INFO] [1766121441.788121442] [smoother_server]:
[smoother_server-2]     smoother_server lifecycle node launched.
[smoother_server-2]     Waiting on external lifecycle transitions to activate
[smoother_server-2]     See https://design.ros2.org/articles/node_lifecycle.html for more information.
[controller_server-1] [INFO] [1766121441.790168985] [controller_server]:
[controller_server-1]   controller_server lifecycle node launched.
[controller_server-1]   Waiting on external lifecycle transitions to activate
[controller_server-1]   See https://design.ros2.org/articles/node_lifecycle.html for more information.
[smoother_server-2] [INFO] [1766121441.796098557] [smoother_server]: Creating smoother server
[planner_server-3] [INFO] [1766121441.799756808] [global_costmap.global_costmap]: Creating Costmap
[controller_server-1] [INFO] [1766121441.803254102] [controller_server]: Creating controller server
[controller_server-1] [INFO] [1766121441.818056340] [local_costmap.local_costmap]:
[controller_server-1]   local_costmap lifecycle node launched.
[controller_server-1]   Waiting on external lifecycle transitions to activate
[controller_server-1]   See https://design.ros2.org/articles/node_lifecycle.html for more information.
[controller_server-1] [INFO] [1766121441.818886625] [local_costmap.local_costmap]: Creating Costmap
[bt_navigator-5] [INFO] [1766121441.822973786] [bt_navigator]:
[bt_navigator-5]        bt_navigator lifecycle node launched.
[bt_navigator-5]        Waiting on external lifecycle transitions to activate
[bt_navigator-5]        See https://design.ros2.org/articles/node_lifecycle.html for more information.
[bt_navigator-5] [INFO] [1766121441.823107514] [bt_navigator]: Creating
[lifecycle_manager-8] [INFO] [1766121442.018963137] [lifecycle_manager_navigation]: Starting managed nodes bringup...
[lifecycle_manager-8] [INFO] [1766121442.019241230] [lifecycle_manager_navigation]: Configuring controller_server
[controller_server-1] [INFO] [1766121442.020290717] [controller_server]: Configuring controller interface
[controller_server-1] [INFO] [1766121442.020988509] [controller_server]: getting goal checker plugins..
[controller_server-1] [INFO] [1766121442.021447341] [controller_server]: Controller frequency set to 20.0000Hz
[controller_server-1] [INFO] [1766121442.021661741] [local_costmap.local_costmap]: Configuring
[controller_server-1] [INFO] [1766121442.041809235] [local_costmap.local_costmap]: Using plugin "voxel_layer"
[controller_server-1] [INFO] [1766121442.068535698] [local_costmap.local_costmap]: Subscribed to Topics: scan
[controller_server-1] [INFO] [1766121442.095834193] [local_costmap.local_costmap]: Initialized plugin "voxel_layer"
[controller_server-1] [INFO] [1766121442.096008883] [local_costmap.local_costmap]: Using plugin "inflation_layer"
[controller_server-1] [INFO] [1766121442.099938885] [local_costmap.local_costmap]: Initialized plugin "inflation_layer"
[controller_server-1] [INFO] [1766121442.128554378] [controller_server]: Created progress_checker : progress_checker of type nav2_controller::SimpleProgressChecker
[controller_server-1] [INFO] [1766121442.133749239] [controller_server]: Created goal checker : general_goal_checker of type nav2_controller::SimpleGoalChecker
[controller_server-1] [INFO] [1766121442.135156757] [controller_server]: Controller Server has general_goal_checker  goal checkers available.
[controller_server-1] [INFO] [1766121442.145125482] [controller_server]: Created controller : FollowPath of type dwb_core::DWBLocalPlanner
[controller_server-1] [INFO] [1766121442.148243961] [controller_server]: Setting transform_tolerance to 0.200000
[controller_server-1] [INFO] [1766121442.170906700] [controller_server]: Using critic "RotateToGoal" (dwb_critics::RotateToGoalCritic)
[controller_server-1] [INFO] [1766121442.171990408] [controller_server]: Critic plugin initialized
[controller_server-1] [INFO] [1766121442.172318414] [controller_server]: Using critic "Oscillation" (dwb_critics::OscillationCritic)
[controller_server-1] [INFO] [1766121442.173495910] [controller_server]: Critic plugin initialized
[controller_server-1] [INFO] [1766121442.173786819] [controller_server]: Using critic "BaseObstacle" (dwb_critics::BaseObstacleCritic)
[controller_server-1] [INFO] [1766121442.174250855] [controller_server]: Critic plugin initialized
[controller_server-1] [INFO] [1766121442.174533894] [controller_server]: Using critic "GoalAlign" (dwb_critics::GoalAlignCritic)
[controller_server-1] [INFO] [1766121442.175324068] [controller_server]: Critic plugin initialized
[controller_server-1] [INFO] [1766121442.175627406] [controller_server]: Using critic "PathAlign" (dwb_critics::PathAlignCritic)
[controller_server-1] [INFO] [1766121442.176355835] [controller_server]: Critic plugin initialized
[controller_server-1] [INFO] [1766121442.176657407] [controller_server]: Using critic "PathDist" (dwb_critics::PathDistCritic)
[controller_server-1] [INFO] [1766121442.177124144] [controller_server]: Critic plugin initialized
[controller_server-1] [INFO] [1766121442.177366809] [controller_server]: Using critic "GoalDist" (dwb_critics::GoalDistCritic)
[controller_server-1] [INFO] [1766121442.177679571] [controller_server]: Critic plugin initialized
[controller_server-1] [INFO] [1766121442.177717208] [controller_server]: Controller Server has FollowPath  controllers available.
[lifecycle_manager-8] [INFO] [1766121442.183823486] [lifecycle_manager_navigation]: Configuring smoother_server
[smoother_server-2] [INFO] [1766121442.184054215] [smoother_server]: Configuring smoother server
[smoother_server-2] [INFO] [1766121442.191935805] [smoother_server]: Created smoother : simple_smoother of type nav2_smoother::SimpleSmoother
[smoother_server-2] [INFO] [1766121442.193004744] [smoother_server]: Smoother Server has simple_smoother  smoothers available.
[lifecycle_manager-8] [INFO] [1766121442.197241186] [lifecycle_manager_navigation]: Configuring planner_server
[planner_server-3] [INFO] [1766121442.197427194] [planner_server]: Configuring
[planner_server-3] [INFO] [1766121442.197473480] [global_costmap.global_costmap]: Configuring
[planner_server-3] [INFO] [1766121442.200957596] [global_costmap.global_costmap]: Using plugin "static_layer"
[planner_server-3] [INFO] [1766121442.205016920] [global_costmap.global_costmap]: Subscribing to the map topic (/map) with transient local durability
[planner_server-3] [INFO] [1766121442.205673903] [global_costmap.global_costmap]: Initialized plugin "static_layer"
[planner_server-3] [INFO] [1766121442.205719881] [global_costmap.global_costmap]: Using plugin "obstacle_layer"
[planner_server-3] [INFO] [1766121442.206675892] [global_costmap.global_costmap]: Subscribed to Topics: scan
[planner_server-3] [INFO] [1766121442.210062439] [global_costmap.global_costmap]: Initialized plugin "obstacle_layer"
[planner_server-3] [INFO] [1766121442.210109329] [global_costmap.global_costmap]: Using plugin "inflation_layer"
[planner_server-3] [INFO] [1766121442.211309471] [global_costmap.global_costmap]: Initialized plugin "inflation_layer"
[planner_server-3] [INFO] [1766121442.216294200] [global_costmap.global_costmap]: StaticLayer: Resizing costmap to 322 X 209 at 0.050000 m/pix
[planner_server-3] [INFO] [1766121442.217615388] [planner_server]: Created global planner plugin GridBased of type nav2_navfn_planner/NavfnPlanner
[planner_server-3] [INFO] [1766121442.217661422] [planner_server]: Configuring plugin GridBased of type NavfnPlanner
[planner_server-3] [INFO] [1766121442.218189050] [planner_server]: Planner Server has GridBased  planners available.
[lifecycle_manager-8] [INFO] [1766121442.224409704] [lifecycle_manager_navigation]: Configuring behavior_server
[behavior_server-4] [INFO] [1766121442.224611991] [behavior_server]: Configuring
[behavior_server-4] [INFO] [1766121442.229490273] [behavior_server]: Creating behavior plugin spin of type nav2_behaviors/Spin
[behavior_server-4] [INFO] [1766121442.231968206] [behavior_server]: Configuring spin
[behavior_server-4] [INFO] [1766121442.237065876] [behavior_server]: Creating behavior plugin backup of type nav2_behaviors/BackUp
[behavior_server-4] [INFO] [1766121442.239614834] [behavior_server]: Configuring backup
[behavior_server-4] [INFO] [1766121442.243941231] [behavior_server]: Creating behavior plugin drive_on_heading of type nav2_behaviors/DriveOnHeading
[behavior_server-4] [INFO] [1766121442.246118124] [behavior_server]: Configuring drive_on_heading
[behavior_server-4] [INFO] [1766121442.250204935] [behavior_server]: Creating behavior plugin assisted_teleop of type nav2_behaviors/AssistedTeleop
[behavior_server-4] [INFO] [1766121442.254519583] [behavior_server]: Configuring assisted_teleop
[behavior_server-4] [INFO] [1766121442.260145707] [behavior_server]: Creating behavior plugin wait of type nav2_behaviors/Wait
[behavior_server-4] [INFO] [1766121442.262188500] [behavior_server]: Configuring wait
[lifecycle_manager-8] [INFO] [1766121442.265848037] [lifecycle_manager_navigation]: Configuring bt_navigator
[bt_navigator-5] [INFO] [1766121442.266097563] [bt_navigator]: Configuring
[lifecycle_manager-8] [INFO] [1766121442.372315036] [lifecycle_manager_navigation]: Configuring waypoint_follower
[waypoint_follower-6] [INFO] [1766121442.372524634] [waypoint_follower]: Configuring
[waypoint_follower-6] [INFO] [1766121442.379953864] [waypoint_follower]: Created waypoint_task_executor : wait_at_waypoint of type nav2_waypoint_follower::WaitAtWaypoint
[lifecycle_manager-8] [INFO] [1766121442.380736931] [lifecycle_manager_navigation]: Configuring velocity_smoother
[velocity_smoother-7] [INFO] [1766121442.380950968] [velocity_smoother]: Configuring velocity smoother
[lifecycle_manager-8] [INFO] [1766121442.383386835] [lifecycle_manager_navigation]: Activating controller_server
[controller_server-1] [INFO] [1766121442.383558871] [controller_server]: Activating
[controller_server-1] [INFO] [1766121442.383596763] [local_costmap.local_costmap]: Activating
[controller_server-1] [INFO] [1766121442.383613000] [local_costmap.local_costmap]: Checking transform
[controller_server-1] [INFO] [1766121442.383686473] [local_costmap.local_costmap]: start
[controller_server-1] [WARN] [1766121442.585352663] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
[controller_server-1] [INFO] [1766121442.634331217] [controller_server]: Creating bond (controller_server) to lifecycle manager.
[lifecycle_manager-8] [INFO] [1766121442.745403286] [lifecycle_manager_navigation]: Server controller_server connected with bond.
[lifecycle_manager-8] [INFO] [1766121442.745633749] [lifecycle_manager_navigation]: Activating smoother_server
[smoother_server-2] [INFO] [1766121442.746994838] [smoother_server]: Activating
[smoother_server-2] [INFO] [1766121442.747268815] [smoother_server]: Creating bond (smoother_server) to lifecycle manager.
[controller_server-1] [WARN] [1766121442.784246804] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
[lifecycle_manager-8] [INFO] [1766121442.864918721] [lifecycle_manager_navigation]: Server smoother_server connected with bond.
[lifecycle_manager-8] [INFO] [1766121442.865005298] [lifecycle_manager_navigation]: Activating planner_server
[planner_server-3] [INFO] [1766121442.865480486] [planner_server]: Activating
[planner_server-3] [INFO] [1766121442.865563241] [global_costmap.global_costmap]: Activating
[planner_server-3] [INFO] [1766121442.865594421] [global_costmap.global_costmap]: Checking transform
[planner_server-3] [INFO] [1766121442.865762027] [global_costmap.global_costmap]: start
[controller_server-1] [WARN] [1766121442.984165086] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
[controller_server-1] [WARN] [1766121443.184113115] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
[controller_server-1] [WARN] [1766121443.384107946] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
[controller_server-1] [WARN] [1766121443.584228724] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
[controller_server-1] [WARN] [1766121443.784143687] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
[planner_server-3] [INFO] [1766121443.916849216] [planner_server]: Activating plugin GridBased of type NavfnPlanner
[planner_server-3] [INFO] [1766121443.921203529] [planner_server]: Creating bond (planner_server) to lifecycle manager.
[controller_server-1] [WARN] [1766121443.984360273] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
[lifecycle_manager-8] [INFO] [1766121444.039478380] [lifecycle_manager_navigation]: Server planner_server connected with bond.
[lifecycle_manager-8] [INFO] [1766121444.039754805] [lifecycle_manager_navigation]: Activating behavior_server
[behavior_server-4] [INFO] [1766121444.041203610] [behavior_server]: Activating
[behavior_server-4] [INFO] [1766121444.041348557] [behavior_server]: Activating spin
[behavior_server-4] [INFO] [1766121444.041424458] [behavior_server]: Activating backup
[behavior_server-4] [INFO] [1766121444.041486939] [behavior_server]: Activating drive_on_heading
[behavior_server-4] [INFO] [1766121444.041572437] [behavior_server]: Activating assisted_teleop
[behavior_server-4] [INFO] [1766121444.041651553] [behavior_server]: Activating wait
[behavior_server-4] [INFO] [1766121444.041754120] [behavior_server]: Creating bond (behavior_server) to lifecycle manager.
[lifecycle_manager-8] [INFO] [1766121444.153950026] [lifecycle_manager_navigation]: Server behavior_server connected with bond.
[lifecycle_manager-8] [INFO] [1766121444.154191401] [lifecycle_manager_navigation]: Activating bt_navigator
[bt_navigator-5] [INFO] [1766121444.155318335] [bt_navigator]: Activating
[controller_server-1] [WARN] [1766121444.184149671] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
[bt_navigator-5] [INFO] [1766121444.274232190] [bt_navigator]: Creating bond (bt_navigator) to lifecycle manager.
[lifecycle_manager-8] [INFO] [1766121444.376891302] [lifecycle_manager_navigation]: Server bt_navigator connected with bond.
[lifecycle_manager-8] [INFO] [1766121444.377076485] [lifecycle_manager_navigation]: Activating waypoint_follower
[waypoint_follower-6] [INFO] [1766121444.378147784] [waypoint_follower]: Activating
[waypoint_follower-6] [INFO] [1766121444.378323536] [waypoint_follower]: Creating bond (waypoint_follower) to lifecycle manager.
[controller_server-1] [WARN] [1766121444.384157604] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
[lifecycle_manager-8] [INFO] [1766121444.486576136] [lifecycle_manager_navigation]: Server waypoint_follower connected with bond.
[lifecycle_manager-8] [INFO] [1766121444.486839501] [lifecycle_manager_navigation]: Activating velocity_smoother
[velocity_smoother-7] [INFO] [1766121444.488340815] [velocity_smoother]: Activating
[velocity_smoother-7] [INFO] [1766121444.488725366] [velocity_smoother]: Creating bond (velocity_smoother) to lifecycle manager.
[controller_server-1] [WARN] [1766121444.584746918] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
[lifecycle_manager-8] [INFO] [1766121444.596582695] [lifecycle_manager_navigation]: Server velocity_smoother connected with bond.
[lifecycle_manager-8] [INFO] [1766121444.596791213] [lifecycle_manager_navigation]: Managed nodes are active
[lifecycle_manager-8] [INFO] [1766121444.596926716] [lifecycle_manager_navigation]: Creating bond timer...
[controller_server-1] [WARN] [1766121444.783850531] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
[controller_server-1] [WARN] [1766121444.984147059] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
[controller_server-1] [WARN] [1766121445.184151861] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
[controller_server-1] [WARN] [1766121445.384199268] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
[controller_server-1] [WARN] [1766121445.585308843] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
[controller_server-1] [WARN] [1766121445.784156654] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
[controller_server-1] [WARN] [1766121445.984261689] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
[controller_server-1] [WARN] [1766121446.184177407] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
[controller_server-1] [WARN] [1766121446.384167161] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
[controller_server-1] [WARN] [1766121446.584161159] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
[controller_server-1] [WARN] [1766121446.784169037] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
[controller_server-1] [WARN] [1766121446.984249998] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
[controller_server-1] [WARN] [1766121447.184347882] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
[controller_server-1] [WARN] [1766121447.384159486] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
[controller_server-1] [WARN] [1766121447.584325511] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
[controller_server-1] [WARN] [1766121447.784533905] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
[controller_server-1] [WARN] [1766121447.984274763] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
[controller_server-1] [WARN] [1766121448.184048062] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
[controller_server-1] [WARN] [1766121448.384277438] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
[controller_server-1] [WARN] [1766121448.584170551] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
[controller_server-1] [WARN] [1766121448.784144713] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
[controller_server-1] [WARN] [1766121448.984202995] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
[controller_server-1] [WARN] [1766121449.184589744] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
[controller_server-1] [WARN] [1766121449.384157269] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
[controller_server-1] [WARN] [1766121449.583830617] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
[controller_server-1] [WARN] [1766121449.784339766] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
[controller_server-1] [WARN] [1766121449.984148388] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
[controller_server-1] [WARN] [1766121450.184228012] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
[controller_server-1] [WARN] [1766121450.384157323] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
[controller_server-1] [WARN] [1766121450.584179029] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
[controller_server-1] [WARN] [1766121450.784377295] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
[controller_server-1] [WARN] [1766121450.984144158] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
[controller_server-1] [WARN] [1766121451.184185337] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
[controller_server-1] [WARN] [1766121451.384191302] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
[controller_server-1] [WARN] [1766121451.584143907] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
[controller_server-1] [WARN] [1766121451.784244514] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
[controller_server-1] [WARN] [1766121451.984137300] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
[controller_server-1] [WARN] [1766121452.184086748] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
[controller_server-1] [WARN] [1766121452.384150176] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
[controller_server-1] [WARN] [1766121452.584193547] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
[controller_server-1] [WARN] [1766121452.784386112] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
[controller_server-1] [WARN] [1766121452.984227708] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
[controller_server-1] [WARN] [1766121453.184162128] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
[controller_server-1] [WARN] [1766121453.384145221] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
[controller_server-1] [WARN] [1766121453.583994510] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
[controller_server-1] [WARN] [1766121453.784102643] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
[controller_server-1] [WARN] [1766121453.984202376] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
[controller_server-1] [WARN] [1766121454.184190276] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
[controller_server-1] [WARN] [1766121454.384112554] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
[controller_server-1] [WARN] [1766121454.584139078] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
[controller_server-1] [WARN] [1766121454.784192936] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
[controller_server-1] [WARN] [1766121454.984170581] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
[controller_server-1] [WARN] [1766121455.184145253] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
[controller_server-1] [WARN] [1766121455.384186994] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
[controller_server-1] [WARN] [1766121455.584150834] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
[controller_server-1] [WARN] [1766121455.784146598] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
[controller_server-1] [WARN] [1766121455.984745761] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
[controller_server-1] [WARN] [1766121456.184216297] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
[controller_server-1] [WARN] [1766121456.384299611] [local_costmap.local_costmap]: Sensor origin at (0.14, 0.34 1.75) is out of map bounds (-1.40, -1.35, 0.00) to (1.57, 1.62, 0.78). T
^C[WARNING] [launch]: user interrupted with ctrl-c (SIGINT)
[lifecycle_manager-8] [INFO] [1766121456.549617544] [rclcpp]: signal_handler(signum=2)
[lifecycle_manager-8] [INFO] [1766121456.550069561] [lifecycle_manager_navigation]: Running Nav2 LifecycleManager rcl preshutdown (lifecycle_manager_navigation)
[lifecycle_manager-8] [INFO] [1766121456.550334002] [lifecycle_manager_navigation]: Terminating bond timer...
[velocity_smoother-7] [INFO] [1766121456.549632985] [rclcpp]: signal_handler(signum=2)
[velocity_smoother-7] [INFO] [1766121456.550045187] [velocity_smoother]: Running Nav2 LifecycleNode rcl preshutdown (velocity_smoother)
[velocity_smoother-7] [INFO] [1766121456.550476652] [velocity_smoother]: Deactivating
[bt_navigator-5] [INFO] [1766121456.549652054] [rclcpp]: signal_handler(signum=2)
[smoother_server-2] [INFO] [1766121456.549693207] [rclcpp]: signal_handler(signum=2)
[smoother_server-2] [INFO] [1766121456.550140966] [smoother_server]: Running Nav2 LifecycleNode rcl preshutdown (smoother_server)
[controller_server-1] [INFO] [1766121456.549715514] [rclcpp]: signal_handler(signum=2)
[controller_server-1] [INFO] [1766121456.552418827] [controller_server]: Running Nav2 LifecycleNode rcl preshutdown (controller_server)
[controller_server-1] [INFO] [1766121456.552812072] [controller_server]: Deactivating
[planner_server-3] [INFO] [1766121456.549714532] [rclcpp]: signal_handler(signum=2)
[planner_server-3] [INFO] [1766121456.550716880] [planner_server]: Running Nav2 LifecycleNode rcl preshutdown (planner_server)
[planner_server-3] [INFO] [1766121456.551165863] [planner_server]: Deactivating
[planner_server-3] [INFO] [1766121456.552018587] [global_costmap.global_costmap]: Deactivating
[velocity_smoother-7] [INFO] [1766121456.550669378] [velocity_smoother]: Destroying bond (velocity_smoother) to lifecycle manager.
[velocity_smoother-7] [INFO] [1766121456.562233641] [velocity_smoother]: Cleaning up
[velocity_smoother-7] [INFO] [1766121456.566661624] [velocity_smoother]: Destroying bond (velocity_smoother) to lifecycle manager.
[bt_navigator-5] [INFO] [1766121456.550862774] [bt_navigator]: Running Nav2 LifecycleNode rcl preshutdown (bt_navigator)
[bt_navigator-5] [INFO] [1766121456.551338090] [bt_navigator]: Deactivating
[bt_navigator-5] [INFO] [1766121456.551517113] [bt_navigator]: Destroying bond (bt_navigator) to lifecycle manager.
[bt_navigator-5] [INFO] [1766121456.583795480] [bt_navigator]: Cleaning up
[smoother_server-2] [INFO] [1766121456.550605725] [smoother_server]: Deactivating
[smoother_server-2] [INFO] [1766121456.550784784] [smoother_server]: Destroying bond (smoother_server) to lifecycle manager.
[smoother_server-2] [INFO] [1766121456.582229385] [smoother_server]: Cleaning up
[smoother_server-2] [INFO] [1766121456.638053764] [smoother_server]: Destroying bond (smoother_server) to lifecycle manager.
[behavior_server-4] [INFO] [1766121456.553016137] [rclcpp]: signal_handler(signum=2)
[behavior_server-4] [INFO] [1766121456.554370379] [behavior_server]: Running Nav2 LifecycleNode rcl preshutdown (behavior_server)
[behavior_server-4] [INFO] [1766121456.554771716] [behavior_server]: Deactivating
[behavior_server-4] [INFO] [1766121456.554988861] [behavior_server]: Destroying bond (behavior_server) to lifecycle manager.
[behavior_server-4] [INFO] [1766121456.636555533] [behavior_server]: Cleaning up
[controller_server-1] [INFO] [1766121456.553086471] [local_costmap.local_costmap]: Deactivating
[controller_server-1] [INFO] [1766121456.584489243] [controller_server]: Destroying bond (controller_server) to lifecycle manager.
[controller_server-1] [INFO] [1766121456.625726332] [controller_server]: Cleaning up
[controller_server-1] [INFO] [1766121456.626044465] [local_costmap.local_costmap]: Cleaning up
[waypoint_follower-6] [INFO] [1766121456.555832032] [rclcpp]: signal_handler(signum=2)
[waypoint_follower-6] [INFO] [1766121456.558413535] [waypoint_follower]: Running Nav2 LifecycleNode rcl preshutdown (waypoint_follower)
[waypoint_follower-6] [INFO] [1766121456.558868414] [waypoint_follower]: Deactivating
[waypoint_follower-6] [INFO] [1766121456.559101314] [waypoint_follower]: Destroying bond (waypoint_follower) to lifecycle manager.
[waypoint_follower-6] [INFO] [1766121456.611676731] [waypoint_follower]: Cleaning up
[waypoint_follower-6] [INFO] [1766121456.627504047] [waypoint_follower]: Destroying bond (waypoint_follower) to lifecycle manager.
[behavior_server-4] [INFO] [1766121456.649714094] [behavior_server]: Destroying bond (behavior_server) to lifecycle manager.
[controller_server-1] [INFO] [1766121456.663025920] [controller_server]: Destroying bond (controller_server) to lifecycle manager.
[smoother_server-2] [INFO] [1766121456.664712164] [smoother_server]: Destroying
[velocity_smoother-7] [INFO] [1766121456.697820855] [velocity_smoother]: Destroying
[controller_server-1] [INFO] [1766121456.746524387] [local_costmap.local_costmap]: Destroying
[behavior_server-4] [INFO] [1766121456.758483162] [behavior_server]: Destroying
[bt_navigator-5] [INFO] [1766121456.761080311] [bt_navigator]: Completed Cleaning up
[bt_navigator-5] [INFO] [1766121456.761141545] [bt_navigator]: Destroying bond (bt_navigator) to lifecycle manager.
[controller_server-1] [INFO] [1766121456.773903826] [controller_server]: Destroying
[bt_navigator-5] [INFO] [1766121456.780763741] [bt_navigator]: Destroying
[waypoint_follower-6] [INFO] [1766121456.786190160] [waypoint_follower]: Destroying
[planner_server-3] [INFO] [1766121456.865931466] [planner_server]: Deactivating plugin GridBased of type NavfnPlanner
[planner_server-3] [INFO] [1766121456.865980911] [planner_server]: Destroying bond (planner_server) to lifecycle manager.
[INFO] [velocity_smoother-7]: process has finished cleanly [pid 15519]
[planner_server-3] [INFO] [1766121456.876151252] [planner_server]: Cleaning up
[lifecycle_manager-8] [INFO] [1766121456.879487144] [lifecycle_manager_navigation]: Destroying lifecycle_manager_navigation
[planner_server-3] [INFO] [1766121456.891321006] [global_costmap.global_costmap]: Cleaning up
[planner_server-3] [INFO] [1766121456.898916599] [planner_server]: Cleaning up plugin GridBased of type NavfnPlanner
[INFO] [smoother_server-2]: process has finished cleanly [pid 15509]
[planner_server-3] [INFO] [1766121456.899684995] [planner_server]: Destroying plugin GridBased of type NavfnPlanner
[planner_server-3] [INFO] [1766121456.913491424] [planner_server]: Destroying bond (planner_server) to lifecycle manager.
[planner_server-3] [INFO] [1766121456.919832037] [global_costmap.global_costmap]: Destroying
[planner_server-3] [INFO] [1766121456.939867982] [planner_server]: Destroying
[INFO] [behavior_server-4]: process has finished cleanly [pid 15513]
[INFO] [bt_navigator-5]: process has finished cleanly [pid 15515]
[INFO] [controller_server-1]: process has finished cleanly [pid 15507]
[INFO] [waypoint_follower-6]: process has finished cleanly [pid 15517]
[INFO] [lifecycle_manager-8]: process has finished cleanly [pid 15521]
[INFO] [planner_server-3]: process has finished cleanly [pid 15511]