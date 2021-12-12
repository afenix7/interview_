# Binder
- 内部是mmap

# Linux IPC
https://www.cnblogs.com/luyimin/p/14313185.html
管道单向
  
# MMKV
mmap

# android中跨进程通讯的方式
https://www.cnblogs.com/kma-3/p/9879660.html
- intent action
- cp
- 广播
- binder

# 跨进程数据共享
- sp的MODE_MULTI_PROCESS，不推荐，非进程安全 https://www.jianshu.com/p/875d13458538
- cp
- sqllite
- MMKV 

#Messenger
https://github.com/JasonWu1111/Android-Review/blob/master/Docs/Android%E7%9F%A5%E8%AF%86%E7%82%B9%E6%B1%87%E6%80%BB.md#aidl-%E9%80%9A%E4%BF%A1
Messenger可以在不同进程中传递 Message 对象，在Message中放入我们需要传递的数据，就可以轻松地实现数据的进程间传递了。Messenger 是一种轻量级的 IPC 方案，底层实现是 AIDL。