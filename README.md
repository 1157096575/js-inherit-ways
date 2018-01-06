# 继承：

> javascript的几种继承方式

## 

``` bash
# 一个对象可以使用本不属于自己的属性，那么就说这个对象继承了这些属性。
# 主流的面向对象编程语言他们的继承是类与类之间的继承;
# 在ES6之前，js的继承是对象与对象之间的继承。


# 例如：

function Animal() {}
Person.prototype.MAX_AGE = 25;
var animal = new Animal();

因为animal可以访问自身__proto__属性指向的对象的属性，
我们就说animal继承自它的隐式原型。
        
