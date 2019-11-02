## 合成复用原则
1. 继承的耦合性太高
2. 组合/聚合可以降低耦合性，也能达到使用另一个类的方法
3. 继承结构,子类可以获得父类内部实现细节,破坏封装。组合结构:整体不能看到部分的内部实现细节,不会破坏封装
4. 继承模式是单继承,不支持动态继承,组合模式可以支持动态组合
5. 继承结构中,子类可以回溯父类,直到Object类,这样就可以根据业务实现多态(向上转型和向下转型)  ,组合中不可以实现多态
6. 在开发 过程中,如果复用的部分不会改变,为了安全性和封装的本质,应该使用组合,当我们不仅需要复用,而且还可能要重写或扩展,则应该使用继承