# 开端

## 工作中JavaScript的痛点

- 维护性，接手别人项目，没有注释，痛苦地研究之前逻辑
- 健壮性，自己的项目，一联调，类型、属性就报错
- 写的函数，因为不知道别人会传入什么，写各种判断，力求包括所有情况，还是不行

## 发展

社区推动
  - facebook推出flow
  - 微软推出typescript

## 野马与缰绳

如果JavaScript是一匹野马，那么typescript就是束缚野马的缰绳

## 强类型、弱类型

- typescript是强类型，javascript是弱类型

## 静态类型语言、动态类型语言

- 静态类型语言：在编译阶段确定
- 动态类型语言：在运行阶段确定

动态类型语言，对类型宽松，bug不易发觉，运行时消耗大

动态类型的支持者：
- 类型宽松 -> 使用类型检查
- 运行时消耗大 -> v8引擎针对此进行了优化
- 易读性差 -> 文档工具