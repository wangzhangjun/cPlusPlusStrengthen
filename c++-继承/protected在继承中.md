protected和private相似，在类外只能用公有类成员来访问protected修饰的类成员。private和protected之间的区别在于只有在父类的子类中才会出现。子类的成员可以直接访问父类的protected成员，但不能直接访问基类的private成员。因此，对于外部世界来说，保护成员的行为与私有成员类似；但是对于派生类来说，保护成员的行为与公有成员相似。

**但是，注意：**

最好对类的数据成员采用私有的访问控制，不要使用保护。
