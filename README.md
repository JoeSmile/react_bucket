# some knowledge and urls about react redux and so on 


# react 
官网：
https://reactjs.org/docs/hello-world.html

creat-reate-app 快速构建react项目：
https://github.com/facebookincubator/create-react-app

### Props
When React sees an element representing a user-defined component, it passes JSX attributes to this component as a single object. We call this object “props”.
从外界传入，不会影响render

### State
State is similar to props, but it is private and fully controlled by the component.
改变后会重新render

## react lifecycle
![react lifecycle](https://segmentfault.com/img/bVrFki)

# redux
## store action reducer
官网：http://www.redux.org.cn/

https://github.com/JoeSmile/jest2react (测试redux的demo)

需要使用redux的场景：
* 用户的使用方式复杂
* 不同身份的用户有不同的使用方式（比如普通用户和管理员）
* 多个用户之间可以协作
* 与服务器大量交互，或者使用了WebSocket
* View要从多个来源获取数据
* 某个组件的状态，需要共享
* 某个状态需要在任何地方都可以拿到
* 一个组件需要改变全局状态
* 一个组件需要改变另一个组件的状态

![Redux](http://images2015.cnblogs.com/blog/593627/201604/593627-20160418100233882-504389266.png)


# mobx
## action observable autorun computed

https://github.com/JoeSmile/mobx_react_introduction

https://github.com/riskers/blog/issues/32
