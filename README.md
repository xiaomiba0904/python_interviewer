# python_interviewer


Python 基础数据结构

1. List 如何排序，sorted和sort的区别  # sort()与sorted()的不同在于，sort是在原位重新排列列表，而sorted()是产生一个新的列表。
2. Sort内部实现机制是什么？时间复杂度是都是？# https://github.com/python/cpython/blob/main/Objects/listsort.txt
3. List 和 tuple 的区别？# 可变和不可变
4. Tuple 是不可变的，为什么可以包含可变的list？
5. List 去重的几种方法？# 循环、set、库等
6. set 是如何实现去重的？# 哈希表
7. set，dict 底层都是哈希表，具体如何实现的？
8. Python的哈希表实现是用什么方法来解决哈希冲突的？# 开放寻址法
9. 还有别的解决方法吗，他们各自的优缺点是什么？# https://zhuanlan.zhihu.com/p/33496977 

Python 特性
1. 迭代器和生成器的区别？#  https://www.zhihu.com/question/20829330/answer/133606850
2. 在业务中常用的生成器的场景？
3. __new__ 和 __init__ 的区别？# https://github.com/taizilongxu/interview_python#15-__new__%E5%92%8C__init__%E7%9A%84%E5%8C%BA%E5%88%AB
4. __new__ 在业务的使用的场景？
5. 业务中还使用了其它哪些魔法方法, 优点是什么?
6. GIL 锁的影响
7. 线程在哪几种情况下会释放GIL锁？
8. 如何对Python程序加速？
9. 如何减少Python的内存占用？
10. Python垃圾回收机制 # https://github.com/taizilongxu/interview_python#24-python%E5%9E%83%E5%9C%BE%E5%9B%9E%E6%94%B6%E6%9C%BA%E5%88%B6
11. 还有那几种内存回收机制， 各自的优缺点？ # https://mp.weixin.qq.com/s?__biz=MzUzMjk0ODI0OA==&mid=2247483727&idx=1&sn=abe1e6896cb398bde2517b469d07afa0&chksm=faaa3538cdddbc2e81e146f74fd7050a6ac9a89a13b024717c9d56888de4a19cb0973f6bbe94&mpshare=1&scene=24&srcid=04105l1DG5QXbS4dfUB6aWeX&key=fb1dd35c5489928a678ed39df498f0d7f7ce5ef29135addb7c0573a4d19220f05d9c2522d44eb6315eaa9b6590d1f3afaaf06a3e96a1abeb1fb22d2870f9185f446a1e704aa2b16bd0775cd7be370a43&ascene=14&uin=Mjg4MTE5ODIzMA%3D%3D&devicetype=Windows+10&version=62060739&lang=zh_CN&pass_ticket=bqbjocTiytbymxqE%2FkEqbcTWuMs1uh6W%2BK2eHz3sKwLI%2BWRx6of4k%2BmAlALLk8iH


常用库


数据库、缓存
1. 事务的特性？
2. MySQL是如何实现这些特性的？
3. 索引的数据结构是？
4. B-Tree 和B+Tree 的区别？http://blog.codinglabs.org/articles/theory-of-mysql-index.html
5. InnoDB为什么使用B+Tree？
6. MySql 主从同步是如何实现的？
7. 分库分表的如何分，各自的优缺点？
8. redis的优缺点、使用场景？
9. redis扩展（未完成）
10. redis6.0更新了什么？解决的什么问题？

操作系统
1. 进程和线程的区别？
    
网络
1. 浏览器打开一个网页的全过程？dns、tcp、http、https

分布式
1. redis集群方案
2. 数据分片算法
3. 选举算法

开放性问题

1. 你阅读过哪些库的源码（第三方库或标准库等）？他们的解决了哪些问题？适应场景或范围是什么？
2. 你觉得其中最优秀的设计或实现是什么？
3. 你的业务中使用了哪些库？在使用中是否碰到了问题？
4. 你是如何定位、解决这些问题的？是否还有更优解？
5. 如果是bug，如何避免同样的问题再次出现？

