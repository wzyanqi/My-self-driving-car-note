这是一个我根据Udacity课程以及网络上的其他资源，结合我自己在学习中的心得体会所构成的笔记。希望能够给一些希望转行自动驾驶的朋友们一点点帮助。由于时间有限与工作繁忙，一次无法更新太多，请大家见谅~

### 先修知识
> - c语言和C++（基本要求）
> - Linux操作（很多设备，都是基于linux开发的）
> - python（使用人工智能库）
> - 车辆动力学（无人车层面的车辆模型，自行车模型就够了）
> - 线性代数
> - 高等数学（如泰勒级数，泰勒展开，噪声分布，统计，概率，加减乘除等）

### 笔记架构
#### 1. 计算机视觉与深度学习
1.1 深度学习
#### 2.传感器融合，定位，控制
2.1 卡尔曼滤波  
2.2 定位
2.3 PID控制
#### 3.路径规划与ROS开发
3.1 路径规划  
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

#### ROS书籍
- [Learning ROS for_Robotics Programming](https://github.com/AaronMR/Learning_ROS_for_Robotics_Programming_2nd_edition) ROS电子书
- [视觉slam十四讲](https://github.com/gaoxiang12/slambook) ROS书籍代码
