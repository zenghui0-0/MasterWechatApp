# 开发

## 简易教程

### [简易教程](https://mp.weixin.qq.com/debug/wxadoc/dev/)

- 获取微信小程序的 AppID
- 创建项目
- 编写代码
  - 创建小程序实例
  - 创建页面
- 手机预览

### [体验小程序](https://mp.weixin.qq.com/debug/wxadoc/dev/demo.html)

### [更新日志](https://mp.weixin.qq.com/debug/wxadoc/dev/new.html)

----

## [框架](https://mp.weixin.qq.com/debug/wxadoc/dev/framework/MINA.html)

### [文件结构](https://mp.weixin.qq.com/debug/wxadoc/dev/framework/structure.html)

### [配置](https://mp.weixin.qq.com/debug/wxadoc/dev/framework/config.html)

- `app.json` 配置项列表
  - `pages`
  - `window`
  - `tabBar`
  - `networkTimeout`
  - `debug`
- `page.json`

### [逻辑层(App Service)](https://mp.weixin.qq.com/debug/wxadoc/dev/framework/app-service/)

#### [注册程序 App](https://mp.weixin.qq.com/debug/wxadoc/dev/framework/app-service/app.html)

- `App()`
- `getApp()`

#### [注册页面 Page](https://mp.weixin.qq.com/debug/wxadoc/dev/framework/app-service/page.html)

- `Page()`
- 初始化数据
- 生命周期函数
- 页面相关事件处理函数
- 事件处理函数
- `Page.prototype.setData()`
- `setData()` 参数格式
- `getCurrentPages()`
- 页面栈
- 生命周期
- 页面的路由

#### [模块化](https://mp.weixin.qq.com/debug/wxadoc/dev/framework/app-service/module.html)

- 文件作用域
- 模块化
- ES6 语法以及 API 支持

### [视图层](https://mp.weixin.qq.com/debug/wxadoc/dev/framework/view/)

#### [WXML](https://mp.weixin.qq.com/debug/wxadoc/dev/framework/view/wxml/)

- [数据绑定](https://mp.weixin.qq.com/debug/wxadoc/dev/framework/view/wxml/data.html)
  - 简单绑定
  - 运算
  - 组合
- [条件渲染](https://mp.weixin.qq.com/debug/wxadoc/dev/framework/view/wxml/conditional.html)
  - `wx:if`
  - `block wx:if`
  - `wx:if` vs `hidden`
- [列表渲染](https://mp.weixin.qq.com/debug/wxadoc/dev/framework/view/wxml/list.html)
  - `wx:for`
  - `block wx:for`
  - `wx:key`
- [模板](https://mp.weixin.qq.com/debug/wxadoc/dev/framework/view/wxml/template.html)
  - 定义模板
  - 使用模板
  - 模板的作用域
- [事件](https://mp.weixin.qq.com/debug/wxadoc/dev/framework/view/wxml/event.html)
  - 什么是事件
  - 事件的使用方式
  - 事件详解
      <!--- 事件分类
      - 事件绑定
      - 事件对象
      - `type` `timeStamp`
      - `target` `currentTarget`
      - `touches` `changedTouches`
      - `detail`-->
- [引用](https://mp.weixin.qq.com/debug/wxadoc/dev/framework/view/wxml/import.html)
  - `import`
  - `include`

#### [WXSS](https://mp.weixin.qq.com/debug/wxadoc/dev/framework/view/wxss.html)

- 尺寸单位
- 样式导入
- 内联样式
- 选择器
- 全局样式与局部样式

----

## [组件](https://mp.weixin.qq.com/debug/wxadoc/dev/component/)

### 视图容器

- [view](https://mp.weixin.qq.com/debug/wxadoc/dev/component/view.html)
- [scroll-view](https://mp.weixin.qq.com/debug/wxadoc/dev/component/scroll-view.html)
- [swiper](https://mp.weixin.qq.com/debug/wxadoc/dev/component/swiper.html)

### 基础内容

- [icon](https://mp.weixin.qq.com/debug/wxadoc/dev/component/icon.html)
- [text](https://mp.weixin.qq.com/debug/wxadoc/dev/component/text.html)
- [progress](https://mp.weixin.qq.com/debug/wxadoc/dev/component/progress.html)

### 表单组件

- [button](https://mp.weixin.qq.com/debug/wxadoc/dev/component/button.html)
- [checkbox](https://mp.weixin.qq.com/debug/wxadoc/dev/component/checkbox.html)
- [form](https://mp.weixin.qq.com/debug/wxadoc/dev/component/form.html)
- [input](https://mp.weixin.qq.com/debug/wxadoc/dev/component/input.html)
- [label](https://mp.weixin.qq.com/debug/wxadoc/dev/component/label.html)
- [picker](https://mp.weixin.qq.com/debug/wxadoc/dev/component/picker.html)
- [radio](https://mp.weixin.qq.com/debug/wxadoc/dev/component/radio.html)
- [slider](https://mp.weixin.qq.com/debug/wxadoc/dev/component/slider.html)
- [switch](https://mp.weixin.qq.com/debug/wxadoc/dev/component/switch.html)
- [textarea](https://mp.weixin.qq.com/debug/wxadoc/dev/component/textarea.html)

### 导航

- [navigator](https://mp.weixin.qq.com/debug/wxadoc/dev/component/navigator.html)

### 媒体组件

- [audio](https://mp.weixin.qq.com/debug/wxadoc/dev/component/audio.html)
- [image](https://mp.weixin.qq.com/debug/wxadoc/dev/component/image.html)
- [video](https://mp.weixin.qq.com/debug/wxadoc/dev/component/video.html)

### 地图

- [map](hhttps://mp.weixin.qq.com/debug/wxadoc/dev/component/map.html%20#map)

### 画布

- [canvas](https://mp.weixin.qq.com/debug/wxadoc/dev/component/canvas.html)

### 客服会话

- [contact-button](https://mp.weixin.qq.com/debug/wxadoc/dev/component/contact-button.html)

----

## [API](https://mp.weixin.qq.com/debug/wxadoc/dev/api/)

### [网络](https://mp.weixin.qq.com/debug/wxadoc/dev/api/api-network.html)

#### [发起请求](https://mp.weixin.qq.com/debug/wxadoc/dev/api/network-request.html)

- `wx.request`   `wx.request` 发起的是 HTTPS 请求

#### [上传、下载](https://mp.weixin.qq.com/debug/wxadoc/dev/api/network-file.html)

- `wx.uploadFile`   将本地资源上传到开发者服务器
- `wx.downloadFile` 下载文件资源到本地

#### [WebSocket](https://mp.weixin.qq.com/debug/wxadoc/dev/api/network-socket.html)

- `wx.connectSocket`  创建一个 WebSocket 连接
- `wx.onSocketOpen`   监听WebSocket连接打开事件
- `wx.onSocketError`  监听WebSocket错误
- `wx.sendSocketMessage`  通过 WebSocket 连接发送数据
- `wx.onSocketMessage`  监听WebSocket接受到服务器的消息事件
- `wx.closeSocket`    关闭WebSocket连接
- `wx.onSocketClose`  监听WebSocket关闭

### [媒体](https://mp.weixin.qq.com/debug/wxadoc/dev/api/media-picture.html)

#### [图片](https://mp.weixin.qq.com/debug/wxadoc/dev/api/media-picture.html)

- `wx.chooseImage`  从本地相册选择图片或使用相机拍照
- `wx.previewImage` 预览图片
- `wx.getImageInfo` 获取图片信息

#### [录音](https://mp.weixin.qq.com/debug/wxadoc/dev/api/media-record.html)

- `wx.startRecord`  开始录音
- `wx.stopRecord`   主动调用停止录音

#### [音频播放控制](https://mp.weixin.qq.com/debug/wxadoc/dev/api/media-voice.html)

- `wx.playVoice`    开始播放语音
- `wx.pauseVoice`   暂停正在播放的语音
- `wx.stopVoice`    结束播放语音

#### [音乐播放控制](https://mp.weixin.qq.com/debug/wxadoc/dev/api/media-background-audio.html)

- `wx.getBackgroundAudioPlayerState`  获取音乐播放状态
- `wx.playBackgroundAudio`  播放音乐，同时只能有一首音乐正在播放
- `wx.pauseBackgroundAudio` 暂停播放音乐
- `wx.seekBackgroundAudio`  控制音乐播放进度
- `wx.stopBackgroundAudio`  停止播放音乐
- `wx.onBackgroundAudioPlay`  监听音乐播放
- `wx.onBackgroundAudioPause` 监听音乐暂停
- `wx.onBackgroundAudioStop`  监听音乐停止

#### [音频组件控制](https://mp.weixin.qq.com/debug/wxadoc/dev/api/network-socket.html)

- `wx.createAudioContext` 创建并返回 audio 上下文 `audioContext` 对象

#### [视频](https://mp.weixin.qq.com/debug/wxadoc/dev/api/network-socket.html)

- `wx.chooseVideo`  拍摄视频或从手机相册中选视频，返回视频的临时文件路径

#### [视频组件控制](https://mp.weixin.qq.com/debug/wxadoc/dev/api/network-socket.html)

- `wx.createVideoContext`  创建并返回 video 上下文 `videoContext` 对象

### [文件](https://mp.weixin.qq.com/debug/wxadoc/dev/api/network-socket.html)

- `wx.saveFile` 保存文件到本地
- `wx.getSavedFileList` 获取本地已保存的文件列表
- `wx.getSavedFileInfo` 获取本地文件的文件信息
- `wx.removeSavedFile` 删除本地存储的文件
- `wx.openDocument` 新开页面打开文档，支持格式：doc, xls, ppt, pdf, docx, xlsx, pptx

### [数据缓存](https://mp.weixin.qq.com/debug/wxadoc/dev/api/data.html)

- `wx.setStorage`   将数据存储在本地缓存中指定的 key 中，会覆盖掉原来该 key 对应的内容，这是一个异步接口
- `wx.setStorageSync` 将 data 存储在本地缓存中指定的 key 中，会覆盖掉原来该 key 对应的内容，这是一个同步接口
- `wx.getStorage`  从本地缓存中异步获取指定 key 对应的内容
- `wx.getStorageSync` 从本地缓存中同步获取指定 key 对应的内容
- `wx.getStorageInfo` 异步获取当前storage的相关信息
- `wx.getStorageInfoSync` 同步获取当前storage的相关信息
- `wx.removeStorage`  从本地缓存中异步移除指定 key
- `wx.removeStorageSync`  从本地缓存中同步移除指定 key
- `wx.clearStorage` 清理本地数据缓存
- `wx.clearStorageSync` 同步清理本地数据缓存

### [位置](https://mp.weixin.qq.com/debug/wxadoc/dev/api/location.html)

#### 获取位置

- `wx.getLocation` 获取当前的地理位置、速度
- `wx.chooseLocation` 打开地图选择位置

#### 查看位置

- `wx.openLocation` 使用微信内置地图查看位置

#### [地图组件控制](https://mp.weixin.qq.com/debug/wxadoc/dev/api/api-map.html)

- `wx.createMapContext` 创建并返回 map 上下文 mapContext 对象

### [设备](https://mp.weixin.qq.com/debug/wxadoc/dev/api/device.html)

#### [系统信息](https://mp.weixin.qq.com/debug/wxadoc/dev/api/systeminfo.html)

- `wx.getSystemInfo` 获取系统信息
- `wx.getSystemInfoSync` 获取系统信息同步接口

#### [网络状态](https://mp.weixin.qq.com/debug/wxadoc/dev/api/device.html)

- `wx.getNetworkType` 获取网络类型

#### [重力感应](https://mp.weixin.qq.com/debug/wxadoc/dev/api/accelerometer.html)

- `wx.onAccelerometerChange`  监听重力感应数据，频率：5次/秒

#### [罗盘](https://mp.weixin.qq.com/debug/wxadoc/dev/api/campass.html)

- `wx.onCompassChange`  监听罗盘数据，频率：5次/秒

#### [拨打电话](https://mp.weixin.qq.com/debug/wxadoc/dev/api/phonecall.html)

- `wx.makePhoneCall`  拨打电话

#### [扫码](https://mp.weixin.qq.com/debug/wxadoc/dev/api/scancode.html)

- `wx.scanCode` 调起客户端扫码界面，扫码成功后返回对应的结果

### [界面](https://mp.weixin.qq.com/debug/wxadoc/dev/api/api-react.html)

#### [交互反馈](https://mp.weixin.qq.com/debug/wxadoc/dev/api/api-react.html)

- `wx.showToast` 显示消息提示框
- `wx.hideToast` 隐藏消息提示框
- `wx.showModal` ​显示模态弹窗
- `wx.showActionSheet` 显示操作菜单

#### [设置导航条](https://mp.weixin.qq.com/debug/wxadoc/dev/api/ui.html)

- `wx.setNavigationBarTitle` 动态设置当前页面的标题
- `wx.showNavigationBarLoading` 在当前页面显示导航条加载动画
- `wx.hideNavigationBarLoading` 隐藏导航条加载动画

#### [导航](https://mp.weixin.qq.com/debug/wxadoc/dev/api/ui-navigate.html)

- `wx.navigateTo`  保留当前页面，跳转到应用内的某个页面，使用 `wx.navigateBack` 可以返回到原页面
- `wx.redirectTo` 关闭当前页面，跳转到应用内的某个页面
- `wx.switchTab`  跳转到 `tabBar` 页面，并关闭其他所有非 `tabBar` 页面
- `wx.navigateBack`  关闭当前页面，返回上一页面或多级页面。可通过 `getCurrentPages()` 获取当前的页面栈，决定需要返回几层

#### [动画](https://mp.weixin.qq.com/debug/wxadoc/dev/api/api-animation.html)

- `wx.createAnimation`  创建一个动画实例 `animation`。调用实例的方法来描述动画。最后通过动画实例的`export` 方法导出动画数据传递给组件的 `animation` 属性。
- animation
- 动画队列

#### [绘图](https://mp.weixin.qq.com/debug/wxadoc/dev/api/canvas/intro.html)

- [简介 intro](https://mp.weixin.qq.com/debug/wxadoc/dev/api/canvas/intro.html)
- [Canvas 坐标系](https://mp.weixin.qq.com/debug/wxadoc/dev/api/canvas/coordinates.html)
- [渐变](https://mp.weixin.qq.com/debug/wxadoc/dev/api/canvas/gradient.html)
- [API 接口索引](https://mp.weixin.qq.com/debug/wxadoc/dev/api/canvas/reference.html)
- [wx.createCanvasContext](https://mp.weixin.qq.com/debug/wxadoc/dev/api/canvas/create-canvas-context.html) 创建 canvas 绘图上下文（指定 canvasId）
- [wx.canvasToTempFilePath](https://mp.weixin.qq.com/debug/wxadoc/dev/api/canvas/reference.html) 把当前画布的内容导出生成图片，并返回文件路径

#### [下拉刷新](https://mp.weixin.qq.com/debug/wxadoc/dev/api/pulldown.html)

- `Page.onPullDownRefresh` 在 `Page` 中定义 `onPullDownRefresh` 处理函数，监听该页面用户下拉刷新事件
- `wx.stopPullDownRefresh` 停止当前页面下拉刷新

### [开放接口](https://mp.weixin.qq.com/debug/wxadoc/dev/api/api-login.html)

#### [登录](https://mp.weixin.qq.com/debug/wxadoc/dev/api/api-login.html)

- `wx.login` 调用接口获取登录凭证（code）进而换取用户登录态信息
- `code` 换取 `session_key`
- 登录态维护
  - 登录时序图
  - `wx.checkSession` 检查登陆态是否过期
- [用户数据的签名验证和加解密](https://mp.weixin.qq.com/debug/wxadoc/dev/api/signature.html)
  - 数据签名校验
  - 加密数据解密算法

#### [用户信息](https://mp.weixin.qq.com/debug/wxadoc/dev/api/open.html)

- `wx.getUserInfo` 获取用户信息，需要先调用 `wx.login` 接口说明
- `UnionID` 机制说明

#### [微信支付](https://mp.weixin.qq.com/debug/wxadoc/dev/api/api-login.html)

- `wx.requestPayment` 发起微信支付

#### [模板消息](https://mp.weixin.qq.com/debug/wxadoc/dev/api/notice.html)

- 使用说明
- 接口说明
  - 获取 access_token
  - 发送模板消息
  - 下发条件说明
  - 审核说明
  - 违规说明
  - 处罚说明

#### 客服消息

- [接收消息和事件](https://mp.weixin.qq.com/debug/wxadoc/dev/api/custommsg/receive.html)
  - 文本消息
  - 图片消息
  - 进入会话事件
- [发送客服消息](https://mp.weixin.qq.com/debug/wxadoc/dev/api/custommsg/conversation.html)
- [临时素材接口](https://mp.weixin.qq.com/debug/wxadoc/dev/api/custommsg/material.html)
  - 获取临时素材
  - 新增临时素材
- [接入指引](https://mp.weixin.qq.com/debug/wxadoc/dev/api/custommsg/callback_help.html)

#### [分享](https://mp.weixin.qq.com/debug/wxadoc/dev/api/share.html)

- Page.onShareAppMessage

----

## [工具](https://mp.weixin.qq.com/debug/wxadoc/dev/devtools/devtools.html)

### [概览](https://mp.weixin.qq.com/debug/wxadoc/dev/devtools/devtools.html)

### [程序调试](https://mp.weixin.qq.com/debug/wxadoc/dev/devtools/debug.html)

- 模拟器
- 调试工具
  - Wxml panel
  - Sources panel
  - Network panel
  - Appdata panel
  - Storage panel
  - Console panel
- 小程序操作区

### [代码编辑](https://mp.weixin.qq.com/debug/wxadoc/dev/devtools/edit.html)

- 文件支持
- 实时预览
- 自动保存
- 自动补全
- 常用快捷键
  - 格式调整
  - 光标相关
  - 界面相关

### [项目预览](https://mp.weixin.qq.com/debug/wxadoc/dev/devtools/project.html)

- 显示当前项目细节
- 提交预览和提交上传
- 项目配置
  - ES6 转 ES5
  - 监听文件变化，自动刷新开发者工具
  - 压缩代码
  - 样式补全
  - 不校验请求域名及 TLS 版本

### [下载](https://mp.weixin.qq.com/debug/wxadoc/dev/devtools/download.html)

### [细节点](https://mp.weixin.qq.com/debug/wxadoc/dev/devtools/details.html)

### [历史更新日志](https://mp.weixin.qq.com/debug/wxadoc/dev/devtools/uplog.html)

----

## [QA](https://mp.weixin.qq.com/debug/wxadoc/dev/qa/qa.html)

### [Q&A](https://mp.weixin.qq.com/debug/wxadoc/dev/qa/qa.html)

- 怎么获取用户输入
- 为什么脚本内不能使用`window`等对象
- 为什么 `zepto/jquery` 无法使用
- `wx.navigateTo` 无法打开页面
- 样式表不支持级联选择器
- 本地资源无法通过 `css` 获取
- 如何修改窗口的背景色
- 为什么上传不成功
- `HTTPS` 请求不成功
- 网络请求的 `referer`

### [联系我们](https://mp.weixin.qq.com/debug/wxadoc/dev/qa/contact.html)