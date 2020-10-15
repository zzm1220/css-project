## css-project
### 响应式网站
1. 什么是响应式网站
2. 媒体查询
### 响应式优点
1. 减少工作量
### 缺点
1. 兼容不好
### 浏览器
### 媒体查询
1.
```html
 @media all and (min-width:800px) and (max-width:1200px) {
	
}
```
2. and, or, not, only
3. width: 视口宽度；
   height：视口高度；
   device-width: 设备屏幕的宽带
   device-height: 设备屏幕的高度
   以上都可以添加前缀min/max
4. 视口veiwport定义：
 - 布局视口(layout viewport): 虚拟的视口(eg: 1280*720)
 - 可视视口(visual viewport)：用户缩放可以改变可视视口，但是布局视口是固定的
 - 理想视口(idea viewport)：布局视口在一个设备上的最佳尺寸，一般为手机优化
 ```
 	 <meta name="viewport" content="width=device-width,
 	 minimum-scale=1.0,
 	 maximum-scale=1.0,
 	 user-scalable=no" />
```
- 可视视口一般默认是设备屏幕的宽高
### 分析设计图
1. 沟通
2. 分析结构
3. 分析布局
4. 切图
### 响应式设计原则
1. 渐进增强
2. 优雅降级
### 如何组织项目目录
1. convention over configuration(约定优于配置)

