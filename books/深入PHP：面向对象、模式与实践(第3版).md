# 深入PHP：面向对象、模式与实践(第3版)

## 目录

```
第一部分 介绍
　第1章　PHP：设计与管理　
　  1.1　问题　
　  1.2　PHP 和其他语言　
　  1.3　关于本书　
　    1.3.1　对象　
　    1.3.2　模式　
　    1.3.3　实践　
　    1.3.4　第3版新增内容　
　  1.4　小结　
第二部分　对象
　第2章　PHP与对象　
　  2.1　PHP对象的偶然成功　
　    2.1.1　最初：PHP/FI　
　    2.1.2　语法糖：PHP 3　
　    2.1.3　一场静悄悄的革命：PHP 4　
　    2.1.4　拥抱改变：PHP 5　
　  2.2　走向未来：PHP 6　
　  2.3　拥护和疑虑：关于对象的争辩　
　  2.4　小结　
　第3章　对象基础　
　  3.1　类和对象　
　    3.1.1　编写第一个类　
　    3.1.2　第一个对象（或两个）　
　  3.2　设置类中的属性　
　  3.3　使用方法　
　  3.4　参数和类型　
　    3.4.1　基本类型　
　    3.4.2　获得提示：对象类型　
　  3.5　继承　
　    3.5.1　继承问题　
　    3.5.2　使用继承　
　    3.5.3　public、private、protected：管理类的访问　
　  3.6　小结　
　第4章　高级特性　
　  4.1　静态方法和属性　
　  4.2　常量属性　
　  4.3　抽象类　
　  4.4　接口　
　  4.5　延迟静态绑定：static关键字　
　  4.6　错误处理　
　  4.7　Final 类和方法　
　  4.8　使用拦截器　
　  4.9　析构方法　
　  4.10　使用__clone（）复制对象　
　  4.11　定义对象的字符串值　
　  4.12　回调、匿名函数和闭包　
　  4.13　小结　
　第5章　对象工具　
　  5.1　PHP和包　
　    5.1.1　PHP包和命名空间　
　    5.1.2　自动加载　
　  5.2　类函数和对象函数　
　    5.2.1　查找类　
　    5.2.2　了解对象或类　
　    5.2.3　了解类中的方法　
　    5.2.4　了解类属性　
　    5.2.5　了解继承　
　    5.2.6　方法调用　
　  5.3　反射API　
　    5.3.1　入门　
　    5.3.2　开始行动　
　    5.3.3　检查类　
　    5.3.4　检查方法　
　    5.3.5　检查方法参数　
　    5.3.6　使用反射API　
　  5.4　小结　
　第6章　对象与设计　
　  6.1　代码设计的定义　
　  6.2　面向对象设计和过程式编程　
　    6.2.1　职责　
　    6.2.2　内聚　
　    6.2.3　耦合　
　    6.2.4　正交　
　  6.3　选择类　
　  6.4　多态　
　  6.5　封装　
　  6.6　忘记细节　
　  6.7  4个方向标　
　    6.7.1　代码重复　
　    6.7.2　类知道的太多　
　    6.7.3　万能的类　
　    6.7.4　条件语句　
　  6.8　UML　
　    6.8.1　类图　
　    6.8.2　时序图　
　  6.9　小结　
第三部分　模式
　第7章　什么是设计模式？为何使用它们　
　  7.1　什么是设计模式　
　  7.2　设计模式概览　
　    7.2.1　命名　
　    7.2.2　问题　
　    7.2.3　解决方案　
　    7.2.4　效果　
　  7.3　《设计模式》格式　
　  7.4　为什么使用设计模式　
　    7.4.1　一个设计模式定义了一个问题　
　    7.4.2　一个设计模式定义了一个解决方案　
　    7.4.3　设计模式是语言无关的　
　    7.4.4　模式定义了一组词汇　
　    7.4.5　模式是经过测试的　
　    7.4.6　模式是为协作而设计的　
　    7.4.7　设计模式促进良好设计　
　  7.5　PHP与设计模式　
　  7.6　小结　
　第8章　模式原则　
　  8.1　模式的启示　
　  8.2　组合与继承　
　    8.2.1　问题　
　    8.2.2　使用组合　
　  8.3　解耦　
　    8.3.1　问题　
　    8.3.2　降低耦合　
　  8.4　针对接口编程，而不是针对实现编程　
　  8.5　变化的概念　
　  8.6　父子关系　
　  8.7　模式　
　    8.7.1　用于生成对象的模式　
　    8.7.2　用于组织对象和类的模式　
　    8.7.3　面向任务的模式　
　    8.7.4　企业模式　
　    8.7.5　数据库模式　
　  8.8　小结　
　第9章　生成对象　
　  9.1　生成对象的问题和解决方法　
　  9.2　单例模式　
　    9.2.1　问题　
　    9.2.2　实现　
　    9.2.3　结果　
　  9.3　工厂方法模式　
　    9.3.1　问题　
　    9.3.2　实现　
　    9.3.3　结果　
　  9.4　抽象工厂模式　
　    9.4.1　问题　
　    9.4.2　实现　
　    9.4.3　结果　
　    9.4.4　原型模式　
　    9.4.5　问题　
　    9.4.6　实现　
　  9.5　某些模式的骗术　
　  9.6　小结　
　第10章　让面向对象编程更加灵活的模式　
　  10.1　构造可灵活创建对象的类　
　  10.2　组合模式　
　    10.2.1　问题　
　    10.2.2　实现　
　    10.2.3　效果　
　    10.2.4　组合模式小结　
　  10.3　装饰模式　
　    10.3.1　问题　
　    10.3.2　实现　
　    10.3.3　效果　
　  10.4　外观模式　
　    10.4.1　问题　
　    10.4.2　实现　
　    10.4.3　效果　
　  10.5　小结　
　第11章　执行及描述任务　
　  11.1　解释器模式　
　    11.1.1　问题　
　    11.1.2　实现　
　    11.1.3　解释器的问题　
　  11.2　策略模式　
　    11.2.1　问题　
　    11.2.2　实现　
　  11.3　观察者模式　
　  11.4　访问者模式　
　    11.4.1　问题　
　    11.4.2　实现　
　    11.4.3　访问者模式的问题　
　  11.5　命令模式　
　    11.5.1　问题　
　    11.5.2　实现　
　  11.6　小结　
　第12章　企业模式　
　  12.1　架构概述　
　    12.1.1　模式　
　    12.1.2　应用程序和层　
　  12.2　企业架构之外的基础模式　
　    12.2.1　注册表　
　    12.2.2　实现　
　  12.3　表现层　
　    12.3.1　前端控制器　
　    12.3.2　应用控制器　
　    12.3.3　页面控制器　
　    12.3.4　模板视图和视图助手　
　  12.4　业务逻辑层　
　    12.4.1　事务脚本　
　    12.4.2　领域模型　
　  12.5　小结　
　第13章　数据库模式　
　  13.1　数据层　
　  13.2　数据映射器　
　    13.2.1　问题　
　    13.2.2　实现　
　    13.2.3　效果　
　  13.3　标识映射　
　    13.3.1　问题　
　    13.3.2　实现　
　    13.3.3　效果　
　  13.4　工作单元　
　    13.4.1　问题　
　    13.4.2　实现　
　    13.4.3　效果　
　    13.4.4　延迟加载　
　    13.4.5　问题　
　    13.4.6　实现　
　    13.4.7　效果　
　  13.5　领域对象工厂　
　    13.5.1　问题　
　    13.5.2　实现　
　    13.5.3　效果　
　  13.6　标识对象　
　    13.6.1　问题　
　    13.6.2　实现　
　    13.6.3　效果　
　  13.7　选择工厂和更新工厂模式　
　    13.7.1　问题　
　    13.7.2　实现　
　    13.7.3　效果　
　  13.8　数据映射器中剩下些什么　
　  13.9　小结　
第四部分　实践
　第14章　良好和糟糕的实践　
　  14.1　超越代码　
　  14.2　借一个轮子　
　  14.3　合作愉快　
　  14.4　为你的代码插上双翼　
　  14.5　文档　
　  14.6　测试　
　  14.7　持续集成　
　  14.8　小结　
　第15章　PEAR和Pyrus　
　  15.1　什么是PEAR　
　  15.2　了解Pyrus　
　  15.3　安装PEAR包　
　  15.4　使用PEAR包　
　  15.5　创建自己的PEAR包　
　    15.5.1　package.xml　
　    15.5.2　package.xml的组成　
　    15.5.3　contents元素　
　    15.5.4　依赖　
　    15.5.5　使用phprelease进行灵活的自定义安装　
　    15.5.6　准备发布包　
　    15.5.7　创建自己的PEAR频道　
　  15.6　小结　
　第16章 用phpDocumentor生成文档　
　  16.1　为什么要使用文档　
　  16.2　安装　
　  16.3　生成文档　
　  16.4　DocBlock注释　
　  16.5　类的文档　
　  16.6　文件的文档　
　  16.7　属性的文档　
　  16.8　方法的文档　
　  16.9　在文档中创建链接　
　  16.10　小结　
　第17章　使用Subversion进行版本控制　
　  17.1　为什么要使用版本控制　
　  17.2　获得Subversion　
　  17.3　配置Subversion代码库　
　  17.4　开始项目　
　  17.5　更新和提交　
　  17.6　增加和删除文件及目录　
　    17.6.1　添加文件　
　    17.6.2　删除文件　
　    17.6.3　添加目录　
　    17.6.4　删除目录　
　  17.7　标记和导出项目　
　    17.7.1　标记项目　
　    17.7.2　导出项目　
　  17.8　创建项目分支　
　  17.9　小结　
　第18章　使用PHPUnit进行测试　
　  18.1　功能测试与单元测试　
　  18.2　手工测试　
　  18.3　引入PHPUnit　
　    18.3.1　创建测试用例　
　    18.3.2　断言方法　
　    18.3.3　 测试异常　
　    18.3.4　运行测试套件　
　    18.3.5　约束　
　    18.3.6　模拟与桩　
　    18.3.7　失败是成功之母　
　  18.4　编写Web测试　
　    18.4.1　为测试重构Web应用　
　    18.4.2　简单的Web测试　
　    18.4.3　Selenium　
　  18.5　警告　
　  18.6　小结　
　第19章　用Phing实现项目的自动构建　
　  19.1　什么是Phing　
　  19.2　获取和安装Phing　
　  19.3　编写build文档　
　    19.3.1　目标　
　    19.3.2　属性　
　    19.3.3　类型　
　    19.3.4　任务　
　  19.4　小结　
第五部分　结论
　第20章　持续集成　
　  20.1　什么是持续集成　
　  20.2　CruiseControl和phpUnderControl　
　    20.2.1　安装CruiseControl　
　    20.2.2　安装phpUnderControl　
　    20.2.3　安装项目　
　  20.3　小结　
　第21章　对象、模式与实践　
　  21.1　对象　
　    21.1.1　选择　
　    21.1.2　封装和委托　
　    21.1.3　解耦　
　    21.1.4　复用性　
　    21.1.5　美学　
　  21.2　模式　
　    21.2.1　模式给我们带来了什么　
　    21.2.2　模式和设计原则　
　  21.3　实践　
　    21.3.1　测试　
　    21.3.2　文档　
　    21.3.3　版本控制　
　    21.3.4　自动构建　
　    21.3.5　持续集成　
　    21.3.6　我们还遗漏了什么　
　  21.4　小结　
第六部分　附录
　附录A　参考文献　
　附录B　简单的解析器
```