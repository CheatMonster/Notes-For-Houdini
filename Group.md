# Group

分组可以由点、顶点、线、面来分组

## 属性

组名相同情况下![image-20210518095736192](C:\Users\QZ\AppData\Roaming\Typora\typora-user-images\image-20210518095736192.png)选择组的合成方式

区域选组![image-20210518095918818](C:\Users\QZ\AppData\Roaming\Typora\typora-user-images\image-20210518095918818.png)

根据法线和一条方向向量的夹角选组![image-20210518100434229](C:\Users\QZ\AppData\Roaming\Typora\typora-user-images\image-20210518100434229.png)

- Facet

重新计算法线![image-20210518100333827](C:\Users\QZ\AppData\Roaming\Typora\typora-user-images\image-20210518100333827.png)

一个物体的不可视面分组![image-20210518100910784](C:\Users\QZ\AppData\Roaming\Typora\typora-user-images\image-20210518100910784.png)（一般用于摄像机)

根据线（角度/长度）来分组![image-20210518101124086](C:\Users\QZ\AppData\Roaming\Typora\typora-user-images\image-20210518101124086.png)

边缘线分组（闭合模型没有边缘线)![image-20210518101301842](C:\Users\QZ\AppData\Roaming\Typora\typora-user-images\image-20210518101301842.png)

根据连接深度进行分组（如路径算法）![image-20210518101417374](C:\Users\QZ\AppData\Roaming\Typora\typora-user-images\image-20210518101417374.png)



## 其他分组方式

### ①视图分组

选中需要分组的内容后，在视图界面Tab搜索group

在视图界面框选

### ②Vex分组

使用attribwrangle节点，添加vex代码

![image-20210516194923975](C:\Users\QZ\AppData\Roaming\Typora\typora-user-images\image-20210516194923975.png)

### ③模型交界处

多个模型交界处可以生成组

![image-20210517100316439](C:\Users\QZ\AppData\Roaming\Typora\typora-user-images\image-20210517100316439.png)



## 组的操作

### 显示

blast节点，可以控制显示/隐藏哪些组

#### group delete 

选择分组类型（点/线/面）在选择具体的分组

#### Subdivide

分组细分，使模型分组更加复杂

#### grouppromote

转换分组类型

#### group expand

节点扩张，在此节点上创建动画帧，可以控制动画过渡速度

### 删除

#### blast

Delete Non Selected 反选删除