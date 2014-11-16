Learning-Android
================

Weekly summary in the way of learning Android

## 组件
###### ListView
* 重写onMeasure，让滚动条不会出现，这样的ListView非常适合HeaderView是个列表的ListView使用。

## Question
###### Android系统中，为什么需要广播机制（Broadcast）呢?
*  广播机制，本质上它就是一种组件间的通信方式，如果是两个组件位于不同的进程当中，那么可以用Binder机制来实现，如果两个组件是在同一个进程中，那么它们之间可以用来通信的方式就更多了，这样看来，广播机制似乎是多余的。然而，广播机制却是不可替代的，它和Binder机制不一样的地方在于，广播的发送者和接收者事先是不需要知道对方的存在的，这样带来的好处便是，系统的各个组件可以松耦合地组织在一起，这样系统就具有高度的可扩展性，容易与其它系统进行集成


