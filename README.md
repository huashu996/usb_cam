# 1.建立工作空间拷贝代码
mkdir catkin_ws/src   
cd catkin_ws/src   
git clone git@github.com:huashu996/usb_cam.git   
# 2.编译运行
cd ..  
catkin_make   
source devel/setup.bash  
roslaunch usb_cam usb_cam-test.launch  
# 3.说明
usb_cam-multi.launch 一次启动多个相机  
usb_cam-test.launch 启动一个可见光相机  
usb_cam-test2.launch 启动一个红外相机  
