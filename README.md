# TyphoonGen4Wave
A python program to generate the right wind field data applied in typhoon wave simulation

台风风场生成工具

1 设计目的

本工具旨在便于海洋工程人员在处理气旋条件下海洋动力数学模型的大气边界条件时，能在不引入大气数值模式的前提下，利用地面台站、卫星高度计、台风路径集
及后报风场，基于不同资料源的相互校正、模式风场和背景风场的融合，生成最符合实测资料的风场结果，并附带提供相应的输出，包含：

（1）NetCDF或Dfs2形式的风场时序资料
（2）台风路径图及影响范围
（3）风场提取点风速、风向与实测台站、卫星高度计资料的对比
