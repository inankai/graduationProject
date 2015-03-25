


### [基础API库](http://docs.turbulenz.com/game_engine_overview.html#low-level-api) 

#### GraphicsDevice 
* 光影效果，
* **顶点缓存VertexBuffer和索引缓存IndexBuffer**是什么:question:
* 2D,3D支持和纹理支持
* 全屏 解图
* 适配音频

#### MathDevice
计算库 矩阵转换和位置变换
3D 空间变幻

#### SoundDevice
声音设备和3D音量变幻

#### NetworkDevice
网络通信库


#### InputDevice
输入设备
	Keyboard, Mouse, Xbox360 Pad, Joysticks, Wheels, Touch, Multi-touch

异步事件相应
	Events for keydown, keyup, mousedown, mouseup, mousewheel, mousemove, mouseover, mouseenter, mouseleave, paddown, padup, focus, blur, mouselocklost, touchstart, touchend, touchmove, touchmove, touchenter, touchleave, touchcancel

鼠标 锁定等


### [高级API库](http://docs.turbulenz.com/game_engine_overview.html#high-level-api)

#### Scene Graph
场景渲染，视觉相关

#### Animation
动画和纹理

#### Resource Manager
动态资源管理

#### Deferred Renderer；Forward Renderer；Default Renderer；Simple Renderer
各种渲染方式封装

#### 2D Rendering
* 2D 渲染库
* Draw2D 2D模型绘制
* Canvas2D 封装canvas2D API

#### Utilities
* 缓存索引管理
* API封装和回调
* "内存"管理
* 通信协议封装
* 调试和记录
* 网络模拟