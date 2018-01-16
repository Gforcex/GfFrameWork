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
