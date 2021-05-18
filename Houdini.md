[课程要求.md](C:\Users\QZ\Desktop\Houdini\笔记\课程要求.md)

# 一、节点

## 常用节点

### 节点操作

更改节点的颜色和形状![image-20210518090707240](C:\Users\QZ\AppData\Roaming\Typora\typora-user-images\image-20210518090707240.png)没啥用但是花里胡哨的功能

忽略/信息/锁定<img src="C:\Users\QZ\AppData\Roaming\Typora\typora-user-images\image-20210518090902970.png" alt="image-20210518090902970" style="zoom:50%;" />显示/模板显示

在节点界面按Tab创建节点，也可以鼠标右键

- 删除节点联系的方法

  按住Y，滑动线

  选中线后delete

  左右晃动节点

  

### geometry

- 相当于文件夹，控制其中的整体，一般在内部操作单独操作物体

### merge混合节点

- Shift+R切换合并位置

### Transform

优点：可以随时取消/复用效果

- transform order 控制旋转/移动/缩放的顺序，结果会不一样

- Pivot transform 中心点位置

### Group

[Group.md](C:\Users\QZ\Desktop\Houdini\笔记\Group.md)

### Facet

- 重新计算法线![image-20210518100333827](C:\Users\QZ\AppData\Roaming\Typora\typora-user-images\image-20210518100333827.png)

### Mountain

- 属性<img src="C:\Users\QZ\AppData\Roaming\Typora\typora-user-images\image-20210518113935995.png" alt="image-20210518113935995"  />

### Copytopoints

- 将左侧的物体的组复制到右侧物体组的各个点上

- 将每个点上的物体变成一个点![image-20210518115127402](C:\Users\QZ\AppData\Roaming\Typora\typora-user-images\image-20210518115127402.png)省性能但是不能编辑点
- 法线对齐选项![image-20210518115724723](C:\Users\QZ\AppData\Roaming\Typora\typora-user-images\image-20210518115724723.png)
- 老师的笔记![image-20210518115807780](C:\Users\QZ\AppData\Roaming\Typora\typora-user-images\image-20210518115807780.png)

### Color



### Unpack

- 打包过后可以用此节点拆包
- 

## 模块

[Module.md](C:\Users\QZ\Desktop\Houdini\笔记\Module.md)

# 二、视图属性

## 1.点

- 顶点Vertice和点Piont

  顶点不会重合，会分别计算，例如正方体的一个点会分成三个顶点，每条线各有一个

- polysoup合并顶点

  把顶点合并成一个

- add

  一个个创建点，也可以连接到物体下级，删除物体但保留点

- 

  

## 2.线

- curve 封闭曲线

## 3.面

- facet

  把面拆分成小面

# 三、快捷键

[HotKey.md](C:\Users\QZ\Desktop\Houdini\笔记\HotKey.md)

Ctrl+工具架中的物体 - 在视图中央创建物体

- #### 切换透明视图 - W

- #### 进入物体操作模式 - Enter

  ​	T - 仅移动

  ​	R - 仅旋转

  ​	E - 仅缩放

- #### 回到视图操作模式 - ESC

- #### 选择模式 - S 

- #### F2-F5 更换选择方式

- ##### 1-5 切换视图

  Shift扩选

  Ctrl减选

# 四、文件管理

&为相对路径，也可以显示绝对路径

*代表全部

^代表除了

# 五、摄像机

[Camera.md](C:\Users\QZ\Desktop\Houdini\笔记\Camera.md)

# 六、灯光

[Light.md](C:\Users\QZ\Desktop\Houdini\笔记\Light.md)

# 七、动画

[Animation.md](C:\Users\QZ\Desktop\Houdini\笔记\Animation.md)

# [Sop.md](C:\Users\QZ\Desktop\Houdini\笔记\Sop.md)

# [Vex.md](C:\Users\QZ\Desktop\Houdini\笔记\Vex.md)

# [动力学.md](C:\Users\QZ\Desktop\Houdini\笔记\动力学.md)



# [视频进度.md](C:\Users\QZ\Desktop\Houdini\笔记\视频进度.md)
