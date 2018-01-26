# GfFrameWork

## Entity Component System

* [Entitas-CSharp](https://github.com/sschmid/Entitas-CSharp)
* [ecsrx](https://github.com/grofit/ecsrx)

## Reactive Extensions
响应式编程
* [UniRx](https://github.com/neuecc/UniRx)

## Coroutine

## Future

## IOC/Dependency Injection
依赖注入到容器
framework处理类实例对象之间的关系,类本身只负责实现各自的功能、解耦。

* [strangeioc](https://github.com/strangeioc/strangeioc) The IoC/Binding Framework for Unity3D and C#
* [Zenject](https://github.com/modesttree/Zenject) Dependency Injection Framework for Unity3D

# Three-tier architecture
## MVC
View：收到Model通知，GetModel数据刷新。
Model：数据逻辑处理，数据改变通知View。
Controller: 用户与View交互产生，通过Controller来控制Model。
主动：View在Update中获取更新命(事件、命令)令队列，访问Model数据刷新。
被动：Model变换通知View observer。

## MVCS 
View：用户界面 
Controller：业务逻辑及处理 
Model：数据存储
Store (Service)：数据处理逻辑

## MVP
View：
Model：
Presenter：

## MVVM
View：
Model：
ViewModel:
(Controller):

* [uFrame](https://github.com/uFrame/uFrame.Complete)

## VIPER
View：视图
Interactor:交互器
Presenter：展示器 
Entity：实体
Router：路由器

## MVI
Model-View-Intent

Model:
View:
Intent:

# Information Transfer
## Signals & Slots
## Target/Action
## Delegate

# AI
## FSM
Finite-State Machines
有限状态机

## HFSM
Hierarchical Finite-State Machines
分层有限状态机

## HTN
Hierarchical Task Networks
分层任务网络

## US
Utility Systems
效用系统

## BT
Behavior Trees
* [Event-Based-Behavior-Tree-Planner](https://github.com/Weilin1992/Event-Based-Behavior-Tree-Planner)

## GOAP
Goal Oriented Action Planning
目标导向型行动计划
* [ReGoap](https://github.com/luxkun/ReGoap)

# Net
## RPC
* [MagicOnion](https://github.com/neuecc/MagicOnion)
 
# Concurrency 并发
## Producer-Consumers 

# Software Development Process
Waterfall Model 瀑布模型：计划-需求分析-概要设计-详细设计-编码-测试-运行维护，软件开发按流程递进，有问题逐级反馈。</br>
Build and Fix Model 边做边改模型：</br>
Rapid Prototype Model 快速原型模型：</br>
Evolutionary Model 演化模型：第一次迭代(需求->设计->实现->测试->集成)->反馈->第二次迭代(需求->设计->实现->测试->集成)->反馈->…… </br>
Incremental Model 增量模型：软件系统模块化和组件化，可并发进行</br>
Spiral Model 螺旋模型：</br>
Fountain Model 喷泉模型：</br>
Intelligent model 智能模型：</br>
Hybrid Model/Meta-model混合模型/过程开发模型/元模型:</br>
RAD模型:</br>
Agile software development 敏捷开发 </br>
Test-Driven Development 测试驱动开发(TDD) </br>
