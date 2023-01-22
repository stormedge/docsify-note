
1. docsify的模板工程
2. 集成了各种插件


## tab示例
<!-- tabs:start -->
#### **English**
Hello!
#### **French**
Bonjour!
<!-- tabs:end -->


## alerts示例
> [!TIP]
> An alert of type 'tip' using global style 'callout'.

> [!NOTE]
> An alert of type 'note' using global style 'callout'.

> [!WARNING]
> An alert of type 'warning' using global style 'callout'.

> [!ATTENTION]
> An alert of type 'attention' using global style 'callout'.


## plantuml示例
``` plantuml
@startuml
Alice -> Bob: Authentication Request
Bob --> Alice: Authentication Response

Alice -> Bob: Another authentication Request
Alice <-- Bob: Another authentication Response22
@enduml
```

```plantuml
@startmindmap
* Java基础
** Java发展历史
** 安装Java环境
** Hello World
**[#yellow] 基本语法
*** 变量
*** 数据类型
**** 基本数据类型
*****_ boolean
*****_ byte
*****_ short
*****_ char
*****_ int
*****_ long
*****_ float
*****_ double
**** 引用数据类型
*****_ class类
*****_ array[]数组
*****_ interface接口
**** 运算符
*****_ 四则运算符
*****_ 增量运算符
*****_ 四则运算符
*****_ 自增与自减运算符
*****_ 关系运算符
*****_ 逻辑运算符
*****_ 位运算符
*****_ 移位运算符
*****_ 三目运算符
*****_ 优先级
**** 循环
**** 条件和多分支
**** Java关键字
--[#green] 面向对象
--- 类和对象
--- 继承
--- 重载
--- 重写
--- 多态
--[#pink] 高级特性
--- 接口
--- 泛型
--- 异常处理
--- 注解
--- 反射
@endmindmap
```