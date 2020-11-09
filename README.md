# IELTS_English
Words you must remember for passing IELTS.
    <!-- 设置GUI参数，显示关节控制插件 -->
    <param name="use_gui" value="true"/>

    <!-- 运行joint_state_publisher节点，发布机器人的关节状态  -->
    <node name="joint_state_publisher" pkg="joint_state_publisher" type="joint_state_publisher" />
    
    <!-- 运行robot_state_publisher节点，发布tf  -->
    <node name="robot_state_publisher" pkg="robot_state_publisher" type="state_publisher" />

    <!-- 运行rviz可视化界面 -->
    <node name="rviz" pkg="rviz" type="rviz" args="-d $(find probot_description)/urdf.rviz" required="true" />
</launch>
