# settimeout和setinterval延时不准
因为js是单线程，这两个只是加入任务队列，要等队列前面代码执行完（正好前面也是settimeout）才能运行，web worker真正在多线程可以方便地解决
https://www.jianshu.com/p/55b4eb04b1d3

# 容器
- set:元素不可相同
- map
  
# cookie
https://juejin.cn/post/6974028771921756167
cookie是服务端生成的，浏览器存储在文件里,是字符文本，有失效时间