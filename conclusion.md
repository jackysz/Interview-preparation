## 近期考察知识点总结
> 记录一些最近被问到的一些问题，做为自己之后学习的一个方面，也是对这次面试经历的一次总结

### `css`
* `flex`布局（需要多列举一些对应的属性）
* `rem`布局
* 水平垂直居中（至少能说出5种）
  1. 要注意`flex`布局中的轴向和`justify-content`、`align-items`的关系，当`flex-direction`发生改变后，这里的`justify-content`并不一定代表着水平居中。
  2. 使用`line-height`的时候要考虑到对内部文字的一个影响
* `css`选择器优先级
* 清除浮动

### 原生`JavaScript`
* 事件传播机制： 比较好的例子(`Popover`组件)
* 事件委托：  
  1. 举例说明
  2. 优点是什么

* 一个只用到一次的函数还有必要写成一个函数吗？
* 前端工作流

### `React`
> 最近面试的时候基本都要求会使用`react`

* `redux`是如何将不同`action`通过与其对应的`reducer`来进行执行的
* 使用`redux-thunk`的场景，有没有了解过它的实现
* `react-redux`中`connect`的用法及源码实现

### `Vue`
> 感觉`vue`问的比较少，一般小公司可能会比较偏向于`vue`

* `vue`中可以通过`computed`来发起一个`ajax`请求吗
* `vuex`中如何使得组件可以通过`this.$store`来访问`vuex`中的属性和方法的，谈谈它的原理
* `vue`组件中的自定义属性如何进行获取（如自己在`data`下又定义了一个`data2`）
* 自己有没有写过类似于`vuex`或者`vue-router`的插件

### `Webpack`
* 手写一个`webpack`的基础配置
* 有哪些可以用来加快`webpack`打包速度的方法
* 有没有了解过`TreeShaking`

### 移动端

* `rem`是什么，如何进行计算
* 移动端白屏问题如何解决

### `Node`
> 大多数公司对`Node`的问题会问的比较少

* 使用`express`监听服务，并通过原生`Node`实现一个文件的读取和写入模块，并在监听的服务中使用

### 算法
* 数组去重(中小公司最常问)
* `fastEqual`：实现一个函数，来判断传入的2个元素（这2个元素可能是复杂数据类型的一个嵌套）是否每一项都相同。
* 字符串去重：实现一个函数，传入一个字符串，返回一个新的没有重复字符的字符串
* 进制转换

### `http`知识
* 状态码
* `CDN`的相关知识
* `http`缓存问题

### 开放性题目

* 最近自己有没有在写一些有趣的东西，可以讲讲吗
* 最近在关注的哪些新技术
* 如何应对前端这些层出不穷的新技术，真的要出一个学一个吗





