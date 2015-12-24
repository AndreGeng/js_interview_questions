* 你知道哪些css hack(浏览器兼容方面)
  * TBD
* js中有哪些数据类型，判断一个变量属于哪种类型有什么方法。（怎么判断一个对象是不是Array）
  * Object.prototype.toString.call(item) === '[object Array]'
  * Array.isArray(item)
  * item instanceof Array
  * a.constructor === Array       //fastest
* requestAnimationFrame vs setTimeout的区别
  * requestAnimationFrame会得到浏览器一些性能优化的支持（e.g. tab最小化的时候不运行动画，动画的时间间隔不会大于显示器的刷新频率）
* 对SEO有哪些了解
  * TBD
* px与em, rem是怎么换算的
  * em是相对与父元素的，rem是相对于html元素的
* 你经常逛的前端论坛有哪些?
  * TBD
* 谈一谈js性能优化（1. 优化查询scope chain的时间。2. 优化查询prototype chain的时间。3. DOM访问和修改）
  * 用局部变量存储本地范围之外的变量值，如果它们在函数中的使用多于一次。
  * 避免使用with表达式。
  * 不要滥用try-catch。
  * 少用/不用eval。（妨碍javascript引擎对代码的优化。）
