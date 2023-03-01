conda activate env
cd /d D:Research/code/NodeFormer

NodeFormer在正常划分下不佳

### 数据

feats有点奇怪

结构：![image-20230227155207046](C:\Users\Ononoki\AppData\Roaming\Typora\typora-user-images\image-20230227155207046.png)



### 模型

用了两阶邻居？

create_projection_matrix有一个乘常数不知道为了什么

计算某条边的att时序号反了过来

RF和论文中不一样
