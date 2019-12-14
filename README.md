## design_pattern

设计模式案例（python语言实现）,博客上主要是java语言的实现

## 设计模式概述（Design pattern）：

**设计模式**：代表了最佳的实践，通常被有经验的面向对象的软件开发人员所采用。设计模式是软件开发人员在软件开发过程中面临的一般问题的解决方案。这些解决方案是众多软件开发人员经过相当长的一段时间的试验和错误总结出来的。

**设计模式是一套被反复使用的、多数人知晓的、经过分类编目的、代码设计经验的总结**。使用设计模式是为了重用代码、让代码更容易被他人理解、保证代码可靠性。 毫无疑问，设计模式于己于他人于系统都是多赢的，设计模式使代码编制真正工程化，设计模式是软件工程的基石，如同大厦的一块块砖石一样。项目中合理地运用设计模式可以完美地解决很多问题，每种模式在现实中都有相应的原理来与之对应，每种模式都描述了一个在我们周围不断重复发生的问题，以及该问题的核心解决方案，这也是设计模式能被广泛应用的原因。

**GOF介绍**:在 1994 年，由 Erich Gamma、Richard Helm、Ralph Johnson 和 John Vlissides 四人合著出版了一本名为 Design Patterns - Elements of Reusable Object-Oriented Software（中文译名：设计模式 - 可复用的面向对象软件元素） 的书，该书首次提到了软件开发中设计模式的概念。
四位作者合称 GOF（四人帮，全拼 Gang of Four）。他们所提出的设计模式主要是基于以下的面向对象设计原则。

 - 对接口编程而不是对实现编程。 
 - 优先使用对象组合而不是继承。

*总的来说设计模式分为3大类：*

• **创建型模式（Creational Patterns）**：（都是用来帮助我们创建对象的）这些设计模式提供了一种在创建对象的同时隐藏创建逻辑的方式，而不是使用 new 运算符直接实例化对象。这使得程序在判断针对某个给定实例需要创建哪些对象时更加灵活。主要包括：

 1. 单例模式（Singleton Pattern）:`保证一个类仅有一个对象，并提供一个访问它的全局访问点。(Ensure a class only has one instance,and provide a globe point of access to it.)`

     详细单例模式介绍可点此链接：[单例模式详解（附常见的7种单例模式源码）](https://blog.csdn.net/cui_yonghua/article/details/90513546)

	用Python实现单例模式：[用Python 实现单例模式 （Python经典编程案例）](https://blog.csdn.net/cui_yonghua/article/details/96433301)

 2. 工厂模式（Factory Pattern）：`定义一个用于创建对象的接口，让子类决定将哪一个类实例化，FactoryMethod使一个类的实例化延迟到其子类。（Define an interface for creating anobject, but let subclasses decide which class to instantiate. Factory methodlets a class defer instantiation to subclasses.）`

	 详细工厂模式介绍可点此链接：[工厂模式详解 (附java语言源码)](https://blog.csdn.net/cui_yonghua/article/details/90718052)

	Python实现工厂模式：[用python实现工厂设计模式（Python经典编程案例）](https://blog.csdn.net/cui_yonghua/article/details/96473836)

 3. 抽象工厂模式（Abstract Factory Pattern）：`提供一个创建一系列相关或相互依赖对象的接口，而无需指定它们的具体类。（Provide an interface for creating families of related or dependent object without specifying their concrete classes.）`

	详细抽象工厂模式介绍可点此链接：[抽象工厂模式详解 (附java语言源码)](https://blog.csdn.net/cui_yonghua/article/details/90722176)

 4. 建造者模式（Builder Pattern）：`将一个复杂对象的构建与它的表示分离，使得同样的构建过程可以创建不同的表示。（Separate the construction of a complex object from its representation so that the same construction process can create different representations.）`

	详细建造者模式介绍可点此链接：[建造者模式详解 (附java语言源码)](https://blog.csdn.net/cui_yonghua/article/details/90667226)

 5. 原型模式（Prototype Pattern）:`用原型实例指定创建对象的种类，并且通过拷贝这个原型来创建新的对象。(Specify the kinds of objects to create using a prototypical instance, and create new objects by copying the prototype.)`

	详细原型模式介绍可点此链接：[原型模式详解 (附java语言源码)](https://blog.csdn.net/cui_yonghua/article/details/90789695)

•**结构型模式（Structural Patterns）**：这些设计模式关注类和对象的组合。继承的概念被用来组合接口和定义组合对象获得新功能的方式。主要包括：
 1. 适配器模式（Adapter Pattern）：`将一个类的接口转换成客户希望的另一个接口。Adapter模式使得原本由于接口不兼容而不能一起工作的那些类可以一起工作。（Convert the interface of a class into another interface clients except. Adapter lets classes work together that couldn’t otherwise because of incompatible interfaces.）`

	详细适配器模式介绍可点此链接：[适配器模式详解 (附java语言源码)](https://blog.csdn.net/cui_yonghua/article/details/90910093)

 2. 桥接模式（Bridge Pattern）：`将抽象部分与它的实现部分分离，使他们都可以独立地变化。（Decouple an abstraction from its implementation so that the two can vary independently.）`

	详细桥接模式介绍可点此链接：[桥接模式详解 (附java语言源码)](https://blog.csdn.net/cui_yonghua/article/details/91411166)

 3. 装饰模式（Decorator Pattern）：`动态地给一个对象添加一些额外的职责。就扩展功能而言，Decorator模式比生成子类的方式更为灵活。（Attach additional responsibilities to an object dynamically. Decorators provides a flexible alternative to subclasses for extending functionality.）`

	详细装饰模式介绍可点此链接：[装饰模式详解 (附java语言源码)](https://blog.csdn.net/cui_yonghua/article/details/90694213)

 4. 组合模式（Composite Pattern）：`将对象组合成树形结构以表示“部分-整体”的层次结构。Composite 使得客户对单个对象和复合对象的使用具有一致性。（Compose object into tree structures torepresent part-whole hierarchy. Composite lets clients treat individual objectsand compositions of objects uniformly.）`

	详细组合模式介绍可点此链接：[组合模式详解 (附java语言源码)](https://blog.csdn.net/cui_yonghua/article/details/91438522)

 5. 外观模式（Facade Pattern）：`为子系统中的一组接口提供一个一致的接口。Façade模式定义了一个高层接口，这个接口使得这一子系统更加容易使用。（Provide a unified interface to a set of interfaces in a subsystem. Façade defines a higher-level interface that makes the subsystem easier to use.）`

	详细外观模式介绍可点此链接：[外观模式详解 (附java语言源码)](https://blog.csdn.net/cui_yonghua/article/details/91794310)

 6. 享元模式（Flyweight Pattern）：`运用共享技术有效地支持大量细粒度的对象。（Use sharing to support large numbers offine-grained objects efficiently.）`

	详细享元模式介绍可点此链接：[享元模式详解 (附java语言源码)](https://blog.csdn.net/cui_yonghua/article/details/91886352)

 7. 代理模式（Proxy Pattern）:`为其他对象提供一个代理以控制对这个对象的访问。(Provide a surrogate or placeholder foranther object to control access to it.)`

	详细代理模式介绍可点此链接：[代理模式详解 (附java语言源码)](https://blog.csdn.net/cui_yonghua/article/details/90751548)

• **行为型模式（Behavioral Patterns）**：这些设计模式特别关注对象之间的通信。主要包括：
 1. 模版方法模式（Template Pattern）:`定义一个操作中的算法的骨架，而将一些步骤延迟到子类。TemplateMethod 使得子类可以不改变一个算法的结构即可重定义该算法的某些特定步骤。(Define the skeleton of an algorithm inan operation, deferring some steps to subclasses. Template Method lets subclasses redefine certain steps of an algorithm without changing thealgorithm’s structure.)`

	详细模版方法模式介绍可点此链接：[模板方法模式详解 (附java语言源码)](https://blog.csdn.net/cui_yonghua/article/details/91972353)

 2. 命令模式（Command Pattern）：`将一个请求封装为一个对象，从而使你可用不同的请求对客户进行参数化，对请求排队或记录请求日志，以及支持可取消的操作。（Encapsulate a request as an object,thereby letting you parameterize clients with different requests, queue or log requests, and support undoable operations.）`

	详细命令模式介绍可点此链接：[命令模式详解 (附java语言源码)](https://blog.csdn.net/cui_yonghua/article/details/92670278)

 3. 迭代器模式（Iterator Pattern）：`提供一种方法顺序访问一个聚合对象中各个元素，而又不需暴露该对象的内部表示。（Provide a way to access the elements of an aggregate object sequentially without exposing its underlying representation.）`

	详细迭代器模式介绍可点此链接：[迭代器模式详解 (附java语言源码)](https://blog.csdn.net/cui_yonghua/article/details/92798405)

 4. 观察者模式（Observer Pattern）：`定义对象间的一种一对多的依赖关系，以便当一个对象的状态发生改变时，所有依赖于它的对象都得到通知并自动刷新。（Define a one-to-many dependency between objects so that when one object changes state all its dependents are notified and updated automatically.）`

	详细观察者模式介绍可点此链接：[观察者模式详解 (附java语言源码)](https://blog.csdn.net/cui_yonghua/article/details/90644632)

 5. 中介者模式（Mediator Pattern）：`用一个中介对象来封装一系列的对象交互。中介者使各对象不需要显示地相互引用，从而使其耦合松散，而且可以独立地改变它们之间的交互。（Define an object that encapsulates how a set of objects interact. Mediator promotes loose coupling by keeping objects from referring to each other explicitly and it lets you vary their interaction independently.）`

	详细中介者模式介绍可点此链接：[中介者模式详解 (附java语言源码)](https://blog.csdn.net/cui_yonghua/article/details/92839932)

 6. 备忘录模式（Memento Pattern）：`在不破坏封装性的前提下，捕获一个对象的内部状态，并在该对象之外保持该状态，这样以后就可以将该对象恢复到保存的状态。（Without violating encapsulates, captureand externalize an object’s internal state so that the object can be restored to this state later.）`

	详细备忘录模式介绍可点此链接：[备忘录模式详解 (附java语言源码)](https://blog.csdn.net/cui_yonghua/article/details/93111923)

 7. 解释器模式（Interpreter Pattern）：`定义一个语言，定义它的文法的一种表示，并定义一个解释器，该解释器使用该表示来解释语言中的句子。（Given a language, define are presentation for its grammar along with an interpreter that uses there presentation to interpret sentences in the language.）`

	详细解释器模式介绍可点此链接：[解释器模式详解 (没有附java语言源码)](https://blog.csdn.net/cui_yonghua/article/details/93460141)

 8. 状态模式（State Pattern）:`允许一个对象在其内部状态改变时改变它的行为。对象看起来似乎修改了它所属的类。(Allow an object to alter its behavior when its internal state changes. The object will appear to change its class.)`

	详细状态模式介绍可点此链接：[状态模式详解 (附java语言源码)](https://blog.csdn.net/cui_yonghua/article/details/93460491)

 9. 策略模式（Strategy Pattern）:`定义一系列的算法，把它们一个个封装起来，并且使他们可相互替换。本模式使得算法的变化可以独立于使用它的客户。(Define a family of algorithms,encapsulate each one and make them interchangeable. Strategy lets the algorithmvary independently from clients that use it.)`
 
	详细策略模式介绍可点此链接：[策略模式详解（用java语言实现策略模式）](https://blog.csdn.net/cui_yonghua/article/details/90601469)

 
 10. 责任链模式（Chain of Responsibility Pattern）：`为解除请求的发送者和接收者之间的耦合，而使多个对象都有机会处理这个请求。将这些对象连成一条链，并沿着这条链传递该请求，直到有对象处理它。（Avoid coupling the sender of a requestits receiver by giving more than one object a chance to handle the request.Chain the receiving objects and pass the request along the chain until anobject handles it.）`

		详细责任链模式介绍可点此链接：[责任链模式详解 (附java语言源码)](https://blog.csdn.net/cui_yonghua/article/details/93462893)

 11. 访问者模式（Visitor Pattern）:`表示一个作用于某对象结构中的各元素的操作。它使你可以在不改变各元素类别的前提下定义作用于这些元素的新操作。(Represent an operation to be performedon the elements of an object structure. Visitor lets you define a new operation without changing the classes of the elements on which it operates.)`

		详细访问者模式介绍可点此链接：[访问者模式详解 (没有附java语言源码)](https://blog.csdn.net/cui_yonghua/article/details/93462782)


此外还有一些**J2EE模式**：这些设计模式特别关注表示层。这些模式是由 Sun Java Center 鉴定的。

 1. MVC 模式（MVC Pattern） 
 2. 业务代表模式（Business Delegate Pattern）   
 3. 组合实体模式（Composite Entity Pattern） 
 4. 数据访问对象模式（Data Access Object Pattern）    
 5. 前端控制器模式（Front Controller Pattern） 
 6. 拦截过滤器模式（Intercepting Filter Pattern） 
 7. 服务定位器模式（Service Locator Pattern） 
 8. 传输对象模式（Transfer Object  Pattern）


<谢谢>




