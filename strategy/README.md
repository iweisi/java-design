## 策略模式
一个系统有许多许多类（算法类），而区分它们的只是他们直接的行为。   
在基本的策略模式中，选择所用具体实现的职责由客户端承担，并转给策略模式的Context对象。
策略模式可以和工厂模式结合使用。  
如果一个系统的策略多于四个，就需要考虑使用混合模式，解决策略类膨胀的问题。

### 关键代码
算法类实现同一个接口。