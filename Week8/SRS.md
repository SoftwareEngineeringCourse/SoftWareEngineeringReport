# 软件需求规格说明书 (SRS)
###  1 引言	

#### 1.1 目的
* 为了用户能够更加深入的了解《OnHisWay》这款跑酷游戏
#### 1.2 范围
* PC端，Win10操作系统
#### 1.3 定义、简写和缩略语
#### 1.4 引用文件
* AdvancedLocomotionV4
* Character_Appearance_Dissolve
* HatsPack1
* sA_PickupSet_1
* 以上文件均来源于虚幻商城。

### 2 总体描述
* 《OnHisWay》是一款简约风跑酷类的独立游戏，适合闲暇时间进行游玩；
#### 2.1 产品描述
##### 2.1.1 系统接口
* Directx11
##### 2.1.2 用户界面
* 全屏，开始界面有按钮和操作引导
##### 2.1.3 硬件接口
* 最低配置
	* 操作系统：Windows 7
	* CPU：Intel i5 Quad-Core
	* 内存：1GB RAM
	* 显卡：Intel HD 4000 
	* 存储空间：需要3GB可用空间
##### 2.1.4 软件接口
* Win10操作系统，Directx11
##### 2.1.5 通信接口
* 无
##### 2.1.6 内存约束
* 无
##### 2.1.7 操作
* 键鼠操作
* 有存档和读取存档的按钮
##### 2.1.8 现场适应性需求
* 大部分PC都能够使用
#### 2.2 产品功能
* 用游戏的有趣风格和关卡设计吸引玩家，引导玩家挑战更高的分数。
#### 2.3 用户特点
* 面向玩家的群体为喜欢几何简约风格的玩家，跑酷玩家，3D游戏爱好者；适合所有年龄段的玩家
#### 2.4 约束
* 约束：不能传播项目源码，除了项目组长每个程序员不能修改自己文件夹以外的代码
#### 2.5 需求分配
* 未来的版本需要增设关卡。
### 3 具体需求
#### 3.1 功能
* 系统应能够检查相关插件并自动安装。
#### 3.2 性能要求
* 支持终端数量为一。
* 支持同时运行的用户数量为一。
#### 3.3 软件系统属性
##### 3.3.1 可靠性
* 可连续正常运行10个小时
##### 3.3.2 可用性
* 一小时之内99%的时间都可以正常运行
##### 3.3.3 安全保密性
* 不存在恶意访问，使用，修改和破坏内部数据的情况
##### 3.3.4 可维护性
* 游戏底层逻辑高度模块化，可维护性高
##### 3.3.5 可移植性
* 如有需要，可以把游戏移植到其他操作系统环境中

