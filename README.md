# some knowledge and urls about react redux and so on 


# react 
官网：
https://reactjs.org/docs/hello-world.html

creat-reate-app 快速构建react项目：
https://github.com/facebookincubator/create-react-app

建议安装谷歌浏览器插件react

### Props
When React sees an element representing a user-defined component, it passes JSX attributes to this component as a single object. We call this object “props”.
从外界传入，不会出发render

### State
State is similar to props, but it is private and fully controlled by the component.
改变后会重新render

## react lifecycle
![react lifecycle](https://segmentfault.com/img/bVrFki)

# redux
## store action reducer
官网：http://www.redux.org.cn/

demo：https://github.com/JoeSmile/jest2react (测试redux的demo)

官方demo： https://github.com/reactjs/redux    入门：todos, counter，shopping-cart
高级：real-world
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


三大原则：
* 单一数据源 -- 整个应用的 state 被储存在一棵 object tree 中，并且这个 object tree 只存在于唯一一个 store 中
* state是只读的 -- 惟一改变 state 的方法就是触发 action，action 是一个用于描述已发生事件的普通对象
* 使用纯函数来执行修改 -- 为了描述action如何改变state tree，你需要编写reducers

![Redux](http://images2015.cnblogs.com/blog/593627/201604/593627-20160418100233882-504389266.png)


一个非常有用的调试redux的谷歌插件（强烈建议安装并使用）：
https://github.com/zalmoxisus/redux-devtools-extension
![redux-devtools-extension](https://cloud.githubusercontent.com/assets/7957859/18002950/aacb82fc-6b93-11e6-9ae9-609862c18302.png)

# mobx
### observable 将类中属性转换成可观察的
### computed 可以根据现有的状态或其它计算值衍生出的值
### action  任何应用都有动作
### autorun 创建一个响应式函数

谷歌插件: mobx

demo：https://github.com/JoeSmile/mobx_react_introduction
开源demo：https://github.com/gothinkster/realworld

mobx资源链接：https://github.com/mobxjs/awesome-mobx/blob/master/README-CN.md



redux对比mobx：https://github.com/riskers/blog/issues/32