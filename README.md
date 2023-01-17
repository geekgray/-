- 如何双向绑定、v-model、组件传值方式

- vue-router都支持哪些模式，这些模式有什么区别？

- 多维数组如何扁平化flatten

- 如何将Ajax Promise化，或者延迟函数sleep如何写？

- v-show、v-if区别，分别作用在组件上是否会触发声明周期函数

- v-for和key值作用，vue如何知道数组发生了变化

- 接口做了并发限制，限制为1，提供一些待处理的数据放到数组中。需要实现一个队列请求，让请求排队发送。

- nextTick在什么场景下使用

#### Promise

- Promise 解决了什么问题？
- Promise 常用的方法有哪些？他们分别的作用是什么？
- Promise 实现原理?
- Promise 在事件循环中的执行过程是怎么样的

### 优化

- 大量数据的计算或渲染被卡住，如何优化


### node
- Node全局对象
```
Class:Buffer 可以处理二进制以及非Unicode编码的数据
process 进程对象，提供有关当前过程的信息和控制
console、clearInterval、setInterval、clearTimeout、setTimeout
global 全局命名空间对象，process、console、setTimeout等都有放到global中
```
- Node事件循环机制


### 跨域
 - 什么是跨域
 ```
首先说一下同源策略
同源策略：是浏览器的一种安全机制，即协议、域名、端口一致即为同源。 
跨域也就是违反了浏览器的同源策略。
 ```
 - 常见的跨域方式有哪些？
```
1.JSONP
2.CORS 跨域资源共享 ie9+
3.window.postMessage 主流浏览器 ie8+
```
