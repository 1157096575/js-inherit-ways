# 继承：

> 什么是继承

## 

``` bash
# 一个对象可以使用本不属于自己的属性，那么就说这个对象继承了这些属性。
# 主流的面向对象编程语言他们的继承是类与类之间的继承;
# 在ES6之前，js的继承是对象与对象之间的继承。


# 例如：

function Animal() {}
Animal.prototype.MAX_AGE = 25;
var animal = new Animal();

因为animal可以访问自身__proto__属性指向的对象的属性，
我们就说animal继承自它的隐式原型。
```


> javascript的几种继承方式

## 

``` bash
# 继承方式1: 默认的原型继承
# 继承方式2: 原型覆写
# 继承方式3: copy继承
# 继承方式4: copy加原型的组合
# 继承方式5: Object.create
# 继承方式6: Object.create加原型的组合继承
# 继承方式7: 原型组合式继承(也可以认为这是类式继承)
```
