# data-collection
## 基于人体骨架运动信息的行为识别系统样本采集研究
本系统基于Windows.Form+Kinect v2.0开发的一套数据采集管理系统。主要是采集人体执行某一特定动作的骨骼数据将其用于人体行为识别训练样本。该系统主要功能包含：数据采集、数据可视化、数据回放、数据增强等
### index是系统功能索界面
### Program是程序启动界面
### PlayVideo是对采集的样本进行回放、包含选择文件、暂停/继续、倍速等功能
### posDataToSke是将采集数据时存入数据库的数据（三维坐标）转换为Kinect的Skeleton的Joint类型（骨骼点名+骨骼点三维坐标）的骨架数据并可视化显示出来
### processPosData 是对Skeleton数据进行加工处理
### sampleEnlarge是对已有的样本数据进行增强，包含数据可视化、样本选择、样本播放、暂停/继续
### SampleShow是对样本进行回放，回放采集时的原动作（rgb图片）
