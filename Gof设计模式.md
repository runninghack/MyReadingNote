markdown

面向对象设计最困难的部分是将系统分解为对象集合。因为要考虑许多因素：封装、粒度、依赖关系、灵活性、性能、演化、复用等等。它们都影响着系统的分解，并且这些因素通常还是互相冲突的。

##一. 设计模式怎样解决设计问题

Strategy模式：现实中没有描述过程或算法的对象。

Abstract Factory、Factory Method、Prototype三个模式要解决的是DIP应用以后的创建对象难题。

Abstract Factory, Builder产生那些专门负责生成其他对象的对象。

State模式：将实体的每一个状态描述为一个对象。

Facade模式：怎样用对象表示完整的子系统。

Flyweight模式：如何支持大量的最小粒度的对象。

Visitor和Command生成的对象专门负责实现对其他对象或对象组的请求。

