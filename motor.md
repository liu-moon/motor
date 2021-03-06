

# 1.1绪论

## 1.1.1自动控制原件

概念：应用在自动控制系统中，起到测量、放大、执行、校正作用的元件。本课程只涉及基于电磁定律

的电磁元件。

## 1.1.2总结控制系统的基本组成

<div align=left><img src="/picture/总结控制系统的基本组成.jpg" width="800px">


## 1.1.3自动控制元件的作用

测量元件—— 测量被控对象状态

放大元件—— 将控制器的微弱信号放大给执行元件

执行元件—— 驱动控制对象直接完成控制任务

校正元件—— 提高系统精度和动态性能

控制对象—— 完成任务的机械装置

## 1.1.4基本电磁定律

磁场是由电流和永磁体产生的，一般记为B，记为磁密

电磁感应定律

$$ e=-W\frac{d\Phi}{dt} $$				W为线圈匝数

安培环路定律(全电流定律)

$$ \oint\vec H\cdot d\vec l=\sum WI​ $$		$$ I​ $$为线圈电流

磁路欧姆定律

$$ \Phi = \frac{F_{m}}{R_{m}} = \frac{WI}{\sum R_{mi}} $$			$$ F_{m} $$为磁动势	$$ R_{m} $$为磁阻



# 1.2基于稳恒磁场的原件

## 1.2.1伺服及相关概念

### 伺服

为使一些机构准确灵敏地工作，需要电机能快速加速、减速、反转以及准确停止。为此出现电动机的分支——伺服电机，表示运动机械必须按照控制指令准确无误地实现运动

测量元件—— 直流测速发电机、旋转变压器、自整角机

放大元件—— 电机驱动器

执行元件—— 直流私服电动机、步进电动机

校正元件—— 直流测速发电机

## 1.2.2直流电机的基本工作原理

### 电机内部示意图

<div align=left><img src="/picture/电机.jpg" width="800px">


### 无换向器时

<div align=left><img src="/picture/无换向器.jpg" width="800px">


### 有换向器时
<div align=left><img src="/picture/有换向器.jpg" width="800px">
感应电动势方向与电流方向相反(反电势)


### 发电机

<div align=left><img src="/picture/发电机.jpg" width="800px">


### 有换向器
<div align=left><img src="/picture/发电机有换向器.jpg" width="800px">  


### last

<div align=left><img src="/picture/电动机last.jpg" width="800px">




## 1.2.3直流电机的结构

定子部分：磁极、机壳、电刷装置、端盖

转子部分：电枢铁芯、电枢绕组、换向器

<div align=left><img src="/picture/电机实物.jpg" width="800px">


### 绕组


<div align=left><img src="/picture/绕组.jpg" width="800px">


## 1.2.4直流电机的磁场

电动机空载状态：机械轴上不接任何机械负载。此时电枢电流非常小

发电机空载状态：电源输出端不接任何电负载。此时电枢电流为零

<div align=left><img src="/picture/空载.jpg" width="800px">


空载磁场

<div align=left><img src="/picture/空载磁场.jpg" width="800px">


电动机的负载状态：机械轴上接机械负载，此时电枢电流随着负载的增大而增大

发电机的负载状态：电源输出端接电负载，此时电枢电流随着电负载变化而变化

负载磁场

<div align=left><img src="/picture/负载磁场.jpg" width="800px">


总磁场

<div align=left><img src="/picture/总磁场.jpg" width="800px">


电枢反应：负载时电枢磁场对气隙磁场的影响

影响：使气隙磁场发生畸变

​	考虑饱和，一个磁极下，增强的小于削弱的，总量减少，表现去磁性

​	磁场等于零的位置偏离几何中性线，到物理中性线。表现磁场发生扭斜

励磁方式：指直流电机的励磁线圈与电枢线圈的连接方式
<div align=left><img src="/picture/励磁方式.jpg" width="800px">





