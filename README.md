# Virtual-Assembly-Based-on-Precedence-Constraints-
受到优先约束的虚拟装配/拆卸，基于区块序列结构实现

# 介绍
## 视频演示

https://pan.baidu.com/s/12RYCDc1Xhi6dO8R2avOiWQ

链接内容为本人在“中国制造2025智能制造专项”中负责开发的一款面向Unity3D引擎的SDK的演示视频。该SDK使用C#语言编写，提供参数输入界面，采用的技术和原理为本人已发表的两篇论文：

（1）Li Z, Wang J, Anwar M S, et al. An efficient method for generating assembly prece-dence constraints on 3D models based on a block sequence structure[J]. Computer-Aided Design, 2020, 118: 102773.

（2）Li Z, Wang J, Yan Z, et al. An Interactive Virtual Training System for Assembly and Disassembly Based on Precedence Constraints[C]//Computer Graphics International Con-ference. Springer, Cham, 2019: 81-93.

该SDK的用途是辅助开发者为3D模型生成可交互装配优先约束（装配/拆卸顺序）。同时该视频也演示了将该SDK应用于本人负责开发的一款基于优先约束的虚拟装配/拆卸软件，该软件提供桌面交互界面与虚拟现实交互界面。

## Demo程序

| 设备按键  | 使用方式  | 功能 |
| :------------ |:---------------:| -----:|
| 鼠标左键       | 点击对象         | 选定对象 |
| col 2 is      | 点击空白处        |   取消已选中对象 |
| zebra stripes | are neat        |    $1 |
| zebra stripes | are neat        |    $1 |
| zebra stripes | are neat        |    $1 |
| zebra stripes | are neat        |    $1 |
| zebra stripes | are neat        |    $1 |
| zebra stripes | are neat        |    $1 |


键盘左Shift+鼠标左键	点击并拖拽对象	移动选定对象
键盘左Alt+鼠标左键	点击并拖拽对象	转动选定对象
鼠标右键	点击并拖拽空白处	转动视角
鼠标滚轮	点击并拖拽空白处	横向/纵向移动视角
	前后滑动滚轮	前后移动视角
鼠标右键+键盘W	按住	前移观察视角
鼠标右键+键盘A	按住	左移观察视角
鼠标右键+键盘S	按住	后移观察视角
鼠标右键+键盘D	按住	右移观察视角
键盘W	按住	选定对象沿自身坐标系Z轴负向移动
	自动对齐后按住	选定对象沿装配位置平动
键盘A	按住	选定对象沿自身坐标系X轴正向移动
键盘S	按住	选定对象沿自身坐标系Z轴正向移动
键盘D	按住	选定对象沿自身坐标系X轴负向移动
键盘Q	按住	选定对象沿自身坐标系Y轴正向移动
键盘E	按住	选定对象沿自身坐标系Y轴负向移动
