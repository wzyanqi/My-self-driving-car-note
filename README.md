这是一个我根据Udacity课程以及网络上的其他资源，结合我自己在学习中的心得体会所构成的笔记。希望能够给一些希望转行自动驾驶的朋友们一点点帮助。由于时间有限与工作繁忙，一次无法更新太多，请大家见谅~

### 关于本人
我是一个刚刚入职的汽车软件程序猿，因为机缘巧合，加入了汽车电子这个大行业。目前在上海某合资企业工作。研究生毕业于华中科技大学，研究的方向是发动机电子控制。平时喜欢写作，也爱分享，无奈平时工作太忙，只能偶尔更新。

这是我的微信公众号，我会在这里分享关于在工作中遇到的汽车ECU的方方面面，感兴趣的朋友关注一波！如果你想和我直接交流，在公众号内可以找到我的联系方式。也可以通过以下两者方式：

- 知乎账号：[吃完饭后不刷牙](https://www.zhihu.com/people/tie-xiao-tie-93/activities)（每天）
- 知乎公众号：[汽车控制器](https://zhuanlan.zhihu.com/c_65033682)
- 邮箱地址：little_iron@foxmail.com（每天）
- 个人博客：[一个汽车程序猿](http://iron.applinzi.com)（比较少上）
- 微信公众号：汽车ECU设计（每天）

![](https://i.imgur.com/pTA2EU6.jpg)

### 先修知识
> - c语言和C++（基本要求）
> - Linux操作（很多设备，都是基于linux开发的）
> - python（使用人工智能库）
> - 车辆动力学（无人车层面的车辆模型，自行车模型就够了）
> - 线性代数（矩阵运算）
> - 高等数学（如泰勒级数，泰勒展开，噪声分布，统计，概率，加减乘除等）


### 笔记架构
#### 1. 计算机视觉与深度学习
1.1 深度学习
#### 2.传感器融合，定位，控制
2.1 卡尔曼滤波  

- [什么是卡尔曼滤波](https://github.com/wzyanqi/My-self-driving-car-note/blob/master/Sensor-Fusion/what-is-kalman-filter.md)

2.2 定位  
2.3 PID控制
#### 3.路径规划与ROS开发
3.1 路径规划  

- A*路径算法

3.2 ROS开发  
3.3 系统集成  


### 学习资料
#### 无人驾驶
1. MIT 课程录像(腾讯有中文翻译版)
> 有资深老司机给学生们普及无人车相关知识。没有任何背景也可以愉快的观看涉及的内容相当宽。从感知到决策到最后控制都有涉猎[MIT 6.S094: Deep Learning for Self-Driving Cars](https://selfdrivingcars.mit.edu)
> 

2. [Baidu Apollo](https://github.com/ApolloAuto/apollo)  
百度开发apollo自动驾驶框架，目前已经很国内的数十家整车厂签订了协同开发合作。而且最棒的是，它是完全开源的！  
> 很多代码都是可以在apollo的代码库里找到的。代码藏得很深，不多基本都在src文件夹里面。根据大神们编好的代码，我们可以快速的学习如何构建代码。里面涉及的语言有linux，c++，c，python。

3. Udacity 无人驾驶课程三部曲  
[无人驾驶第一课：从 Apollo 起步](https://cn.udacity.com/course/self-driving-car-fundamentals-featuring-apollo--ud0419)（免费）  
[无人驾驶入门](https://cn.udacity.com/course/intro-to-self-driving-cars--nd113-cn)（付费）  
[无人驾驶工程师](https://cn.udacity.com/course/intro-to-self-driving-cars--nd113-cn)（付费）

4. **[Red Blob Games](https://www.redblobgames.com)**  
一个用数学和计算机科学来教你开发游戏的博客，但里面的路径规划、地图构建的知识都是相同的。非常推荐！

#### 无人驾驶书籍
- [第一本无人驾驶技术书](https://pan.baidu.com/s/1c3472FI)，作者：刘少山等

#### ROS书籍
- [Learning ROS for_Robotics Programming](https://github.com/AaronMR/Learning_ROS_for_Robotics_Programming_2nd_edition) ROS电子书
- [视觉slam十四讲](https://github.com/gaoxiang12/slambook) ROS书籍代码
- 概率机器人，作者：Sebastian THRUN
