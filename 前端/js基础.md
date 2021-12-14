# settimeout和setinterval延时不准
因为js是单线程，这两个只是加入任务队列，要等队列前面代码执行完（正好前面也是settimeout）才能运行，web worker真正在多线程可以方便地解决
https://www.jianshu.com/p/55b4eb04b1d3

# 容器
- set:元素不可相同
- map
  
# cookie
https://juejin.cn/post/6974028771921756167
cookie是服务端生成的，浏览器存储在文件里,是字符文本，有失效时间

# 事件
- 事件捕获（event  capturing）：通俗的理解就是，当鼠标点击或者触发dom事件时，浏览器会从根节点开始由外到内进行事件传播，即点击了子元素，如果父元素通过事件捕获方式注册了对应的事件的话，会先触发父元素绑定的事件。

- 事件冒泡（dubbed  bubbling）：与事件捕获恰恰相反，事件冒泡顺序是由内到外进行事件传播，直到根节点。
————————————————
版权声明：本文为CSDN博主「壹加贰」的原创文章，遵循CC 4.0 BY-SA版权协议，转载请附上原文出处链接及本声明。
原文链接：https://blog.csdn.net/One_And_One/article/details/89307504