# 模块

### Ch 数据通道



### img 合成

合成视图 Composite View

##### Image Network节点

File 导入节点

color 更改颜色节点

channelcopy 提取通道



###### Tab-Comps 各种合成方法

over 前后景重叠



### <strong style="color:#0070c0;">mat 材质构建</strong>

materialbuilder节点 自由创建材质

![image-20210516192510851](C:\Users\QZ\AppData\Roaming\Typora\typora-user-images\image-20210516192510851.png)

材质库中选中材质点击箭头，即可创建材质

#### 1.材质属性

Albedo Multiplier 材质颜色强度

IOR 高光

Roughness 光滑度

anisotropy 各向异性 （物体各个方向上的性能表现不一致）

Reflection 反射

Transparency 折射（透明度）

Subsurface Scattering 简称3S 次表面散射（用作皮肤树叶等）

Sheen 边缘光泽

Emission 发射光（荧光效果）

Opacity 透明度

Texture 添加UV贴图

Bump&Normals 凹凸贴图



#### 2.材质赋给物体

##### ①在obj中选择

细节面板-Render选择

![image-20210516192818610](C:\Users\QZ\AppData\Roaming\Typora\typora-user-images\image-20210516192818610.png)

可以分组选择，即一个物体上有多种材质



##### ②直接拖到物体上

选择创建好的材质直接拖到视图中的物体上

##### ③添加material节点

选择物体连接到material节点，再分组选择材质



### <strong style="color:#00b0f0;">obj 几何体</strong>

#### Geometry

#### 1.点

add-创建一个点

tribez-配合add节点使用，根据点来创建面 公式：((order+1)*order)/2

#### 2.线

line-创建一条线

curve-选中后在视图界面回车，即可自己画线

drawcurve-选中后在一个面上画线，如果想去掉面的网格，可以加一个null加点

#### 3.面

grid-创建一个面

#### 4.几何体

box-正方体

sphere-球体

circle-圆环

cube-本质也是box

**metaball-变形球（多个变形球会互相吸附）**

Platonic-柏拉图物体

torus-圆环

tube-管道

**trace-根据图片生成模型**

convert/unpack-取消模型打包状态，使每个点/线/面不再封装

#### 5.Houdini自带

TestXXX等



#### 5.L-System

用来制作植物



### out 渲染输出

#### mantra 自带渲染器

Valid Frame Range 调整渲染方式

<img src="C:\Users\QZ\AppData\Roaming\Typora\typora-user-images\image-20210517085958216.png" alt="image-20210517085958216" style="zoom: 50%;" />

逐帧渲染时可以Delete Channels以便自由调整渲染帧数

<img src="C:\Users\QZ\AppData\Roaming\Typora\typora-user-images\image-20210517090322644.png" alt="image-20210517090322644" style="zoom:50%;" />

渲染分层细节操作

![image-20210517090606899](C:\Users\QZ\AppData\Roaming\Typora\typora-user-images\image-20210517090606899.png)

Enable Depth of Field 是否渲染景深

Motion Blur 运动模糊

Sampling 采样

Object 选择渲染物体细节



#### 视图操作

在Render View中渲染

![image-20210517085334924](C:\Users\QZ\AppData\Roaming\Typora\typora-user-images\image-20210517085334924.png)

自动渲染，打开后发生变动就会进行渲染

#### <img src="C:\Users\QZ\AppData\Roaming\Typora\typora-user-images\image-20210517085611835.png" alt="image-20210517085611835" style="zoom:50%;" />

渲染完成后保存为快照，再次调整角度进行渲染，可以方便对不同角度进行对比



### shop 材质



### stage USD操作



### tasks Top工作流



