## Demeter Principle
1. 迪米特法则（最少知道原则）：对自己知道的类知道的越少越好，降低类之间的耦合，并不是完全没有依赖
2. 在一个类中的成员变量，方法返回值，方法参数中出现的类成为直接朋友，方法中的局部变量称为陌生人，应该减少陌生人的出现