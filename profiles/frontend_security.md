# 前端安全
## 阅读本文您将收获
* 前端攻击的类型


## xss攻击
* xss攻击又叫做跨站脚本攻击，主要是用户输入或通过其他方式，向我们的代码中注入了一下其他的js，而我们又没有做任何防范，去执行了这段js。

* 可能用户会写一个死循环，将我们的页面给弄崩了，但是也有可能通过这种方式，来获取我们的cookie，从而回去登陆态等信息

* xss攻击从来源可分为反射型和存储型