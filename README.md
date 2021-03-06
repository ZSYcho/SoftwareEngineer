# SoftwareEngineer
* [第1章 软件工程学概述](#第1章-软件工程学概述)
  * [什么是软件](#什么是软件)
  * [软件危机的概念、表现](#软件危机的概念表现)
  * [产生软件危机的原因以及消除危机的途径](#产生软件危机的原因以及消除危机的途径)
  * [软件工程的概念、本质特性、基本原理](#软件工程的概念本质特性基本原理)
  * [软件工程方法学的三要素](#软件工程方法学的三要素)
  * [软件生命周期分成哪三个阶段？各阶段的任务是什么？](#软件生命周期分成哪三个阶段各阶段的任务是什么)
  * [什么是软件过程？瀑布模型、快速原型模型、增量模型、螺旋模型、喷泉模型的特点](#什么是软件过程瀑布模型快速原型模型增量模型螺旋模型喷泉模型的特点)
* [第2章 可行性研究](#第2章-可行性研究)
  * [可行性研究的目的和内容](#可行性研究的目的和内容)
  * [系统流程图的作用](#系统流程图的作用)
  * [数据流图的概念](#数据流图的概念)
  * [数据流图里面的符号、绘制数据流图](#数据流图里面的符号绘制数据流图)
  * [什么是数据字典，以及与数据流图的关系](#什么是数据字典以及与数据流图的关系)
  * [数据字典的表示方法](#数据字典的表示方法)
  * [成本/效益分析](#成本效益分析)
* [第3章 需求分析](#第3章-需求分析)
  * [结构化分析法SA:分析系统数据流](#结构化分析法sa分析系统数据流)
  * [需求分析阶段的任务](#需求分析阶段的任务)
  * [与用户沟通获取需求的方法](#与用户沟通获取需求的方法)
  * [面向过程的分析方法主要是建立三类模型](#面向过程的分析方法主要是建立三类模型)
  * [需求分析的产品是什么](#需求分析的产品是什么)
  * [软件需求规格说明书的内容](#软件需求规格说明书的内容)
  * [常使用的图形工具](#常使用的图形工具)
* [第4章 形式化说明书技术](#第4章-形式化说明书技术)
* [第5章 总体设计](#第5章-总体设计)
  * [总体设计的任务](#总体设计的任务)
  * [模块化思想](#模块化思想)
  * [衡量模块独立的标准（内聚和耦合的含义、种类）](#衡量模块独立的标准内聚和耦合的含义种类)
  * [启发式规则](#启发式规则)
  * [掌握面向数据流的设计方法](#掌握面向数据流的设计方法)
* [第6章 详细设计](#第6章-详细设计)
  * [详细设计的基本任务](#详细设计的基本任务)
  * [程序的五种控制结构](#程序的五种控制结构)
  * [详细设计的工具和直接的转换](#详细设计的工具和直接的转换)
  * [判定表/判定树的设计](#判定表判定树的设计)
  * [Jackson方法](#jackson方法)
  * [McCabe方法计算复杂度](#mccabe方法计算复杂度)
* [第7章 实现](#第7章-实现)
  * [选择程序设计语言应该考虑哪些元素](#选择程序设计语言应该考虑哪些元素)
  * [良好的编程风格包括哪些](#良好的编程风格包括哪些)
  * [软件测试的目的](#软件测试的目的)
  * [初步测试计划是在哪个阶段制定的](#初步测试计划是在哪个阶段制定的)
  * [黑盒测试和白盒测试的概念](#黑盒测试和白盒测试的概念)
    * [黑盒测试](#黑盒测试)
    * [白盒测试](#白盒测试)
  * [测试步骤（5个）以及相关的文档](#测试步骤5个以及相关的文档)
    * [测试步骤](#测试步骤)
    * [相关的文档](#相关的文档)
  * [单元测试的方法](#单元测试的方法)
    * [测试重点](#测试重点)
    * [代码审查](#代码审查)
  * [渐增式与非渐增式的区别](#渐增式与非渐增式的区别)
  * [自顶向下、自下而上、以及混合策略的优缺点](#自顶向下自下而上以及混合策略的优缺点)
    * [自顶向下](#自顶向下)
  * [自下而上](#自下而上)
    * [混合策略](#混合策略)
  * [确认测试](#确认测试)
  * [白盒测试技术（覆盖标准、基本路径）](#白盒测试技术覆盖标准基本路径)
    * [覆盖标准](#覆盖标准)
    * [基本路径](#基本路径)
  * [黑盒测试技术（等价划分、边界值分析）](#黑盒测试技术等价划分边界值分析)
    * [等价划分](#等价划分)
    * [边界值分析](#边界值分析)
  * [软件调试技术有哪些](#软件调试技术有哪些)
  * [软件可靠性（可靠性和可用性的含义）](#软件可靠性可靠性和可用性的含义)
    * [可靠性](#可靠性)
    * [可用性](#可用性)
* [第8章 维护](#第8章-维护)
  * [什么是维护，维护的类型](#什么是维护维护的类型)
  * [决定软件可维护性的因素](#决定软件可维护性的因素)
  * [文档](#文档)
    * [用户文档](#用户文档)
    * [系统文档](#系统文档)
  * [维护是软件生命周期中所花费最多的阶段](#维护是软件生命周期中所花费最多的阶段)
* [第9\-12章 面向对象软件工程](#第9-12章-面向对象软件工程)
  * [几个概念：类、对象、继承、消息、封装、属性、实例、多态性、重载](#几个概念类对象继承消息封装属性实例多态性重载)
    * [类class](#类class)
    * [对象object](#对象object)
    * [继承inheritance](#继承inheritance)
    * [消息message](#消息message)
    * [封装encapsulation](#封装encapsulation)
    * [属性attribute](#属性attribute)
    * [实例instance](#实例instance)
    * [多态性polymorphism](#多态性polymorphism)
    * [重载overload](#重载overload)
  * [面向对象的方法（4个要素）](#面向对象的方法4个要素)
  * [面向对象方法的优点](#面向对象方法的优点)
  * [面向对象建模的三个模型，以及之间的关系](#面向对象建模的三个模型以及之间的关系)
    * [对象模型](#对象模型)
    * [动态模型](#动态模型)
    * [功能模型](#功能模型)
    * [三者关系](#三者关系)
  * [面向对象设计有哪些启发式规则](#面向对象设计有哪些启发式规则)
  * [CMM等级划分](#cmm等级划分)
