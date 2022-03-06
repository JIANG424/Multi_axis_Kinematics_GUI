# Multi_axis_Kinematics_GUI
本说明文档详细介绍了多轴数控加工机床通用运动学求解软件(HFUTCIMS)的设计原理，实现方法及实现效果。 多轴数控加工机床通用运动学求解软件(HFUT-CIMS)分为刀位文件处理模块与多轴运动学求解模块，刀位信息处理模块主要完成刀具位姿（刀位）数据的提取与显示、 刀位点的导入、刀位轨迹绘制； 多轴运动学求解模块主要完成运动学模型构建、 正运动学问题求解、 逆运动学问题求解、结果显示功能。刀位文件处理模块对CAM 软件生成的刀位文件(CL 文件)进行操作，生成的刀位数据导入多轴运动学求解模块中， 求解逆运动学问题， 可生成对应的多轴数控机床加工G代码，控制多轴数控机床的加工运动。 反之， 将多轴数控机床加工 G 代码导入到多轴运动学求解模块中，求解正运动学问题， 可显示相应的刀位数据，并绘制出其在工件坐标系下的刀具运动轨迹。

#使用说明
下载P-code中全部文档，在Matlab软件中运行Multi_axis_Kinematics_GUI.p即可！

#若有任何使用问题，欢迎留言！
