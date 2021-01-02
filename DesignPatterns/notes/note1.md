## 设计模式

面向对象：
es6里如何面向对象，三要素，UML类图？
1. 用webpack+babel搭建es6的环境
2. es6 class面向对象语法
3. 面向对象三要素：继承、封装、多态

设计原则：
什么是设计？
5大设计原则（扩展开放，修改关闭等）
从设计到模式

设计模式：
分类：创建型、结构型、行为型、框架型等
给23种是划分优先级，搞懂常用的设计模式。结合核心技术、框架在场景中去使用。

实战：
设计方案
结合示例来更好的理解
用jQuery实现一个简单的购物车
设计分析，画UML类图
7种基础设计模式如何结合使用

## 面向对象

继承，子类继承父类
封装，数据的权限和保密
多态，同一接口不同实现

js里用的继承比较多，封装和多态用的少一点，js里没有接口的概念。

继承：父类是共用的。可以将一些公共的方法抽离出来，提高利用，减少冗余。

封装：(es6尚不支持，可用ts来写)
public 完全开放
protected 对子类开放
private 对自己开放

封装时，减少耦合，不暴露无关的接口。做好权限管理，相应权限只获取相应接口数据。es6目前不支持，一般默认_开头的属性是private，遵循约定。

多态：
同一个接口，不同实现
js应用比较少
需要结合java等语言的接口、重写、重载等功能。

保持子类的开放性和灵活性
面向接口编程

## 示例

jQuery是一个class的类
$('p')是jQuery的一个实例

```js
widnow.$ = function(selector){
  return document.querySelector(selector)
}
```