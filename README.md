# FullStack
Core Knowledge

## 流程

```
webmirror.js    
  - enforceCurrentURL()
  -  eventBus.addListener('loadURL')
  - 开始建立websocket
  -发送第一个消息：onFirstConnect
windowManager
  - openWindow()
          - 异步动态获取配置
  - doCreateWindow
windowCache
  - get
windowManager
  - 添加事件监听
  - loadurl


// attribute , prop
- app.js
  - mainframe.js
  - server.star
mainchannel
  - connect
 frameTracker
   - loadUrl
   - attachDom
DomTracker   // html 变化
frame.js // 对象属性的变化（不是attribute）

处理监听结果
domChangeSink


# client
route
domfactory

---------------------------------------
domevent - 抓取所有事件
domeventdisplay
domeventdispatcher


```