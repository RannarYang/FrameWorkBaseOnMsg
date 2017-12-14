# 基于消息机制的开发框架
### 框架说明
1. MsgCenter：消息分发中心
2. Manager：管理类
3. Base: 封装各模块基本操作及框架基本功能（绑定事件，触发事件），此处代码存在冗余，待优化
4. EventCode: 定义各类事件的操作码
### 技术实现
1. 引擎：白鹭Egret，EUI
2. 观察者模式、单例模式
3. SoundManager, PopUpManager等管理类
### 例子实现的功能
点击DemoView1中的按钮，触发事件， DemoView2 监听此事件并响应
### 使用注意事项
UI离开界面时事件监听的释放等