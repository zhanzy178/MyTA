# MyTA
> 组长：詹宗沅
> 小组成员：张涵玮 张家侨 詹宗沅 刘俊君

------

## 1 项目名称

My TA (teaching assistant)

</br>

## 2 项目背景

先如今的大学的教学中，teaching assistant是教师与学生交流不可或缺的一部分
TA的作用主要在作业布置，作业收发，作业统分，作业讲解，课程相关公告发布，甚至有的TA需要协助完成课堂签到
但是实际中TA对老师的协助效率往往较低，以我自身经验而言，大学中有部分课程的TA是从未见过面的，TA往往是在线上通过QQ的方式联系学生；所以当前的教师-TA教学体系存在如下问题：

- TA与同学的交流，题目的讲解机会少
- 往往大多数与TA的联系都是不私戳的，因此和作业相关的解答只有部分人知道
- 传统的纸质签到效率低，且浪费纸张
- 传统纸质作业收发存在，时间不统一，作业本不统一的问题，极大加大了ta的工作难度
- ta题目讲解往往都是堆积到一定程度后，通过一堂课的时间进行的讲解，无法提高同学的积极性和参与度，而且由于时间原因只能讲解部分题目
- QQ群大多数是无用信息，不适合作业的公布，课程通知的发布等TA活动

综上考虑上述问题，我们提出开发My TA安卓手机app设想，使用手机APP作为教师-TA-学生之间提高信息交换效率的桥梁

</br>

## 3 功能描述

> 功能分为两大块内容，一类是面向教师和TA的功能，一类是面向学生的功能。
>
> 粗体表示第一阶段完成的功能，斜体代表后期任务

- TA端：

  1. **创建课程（Course）**

     - **布置作业（Homework）**
     - **设置临时签到**

     - *问答聊天室（后期任务）*
     - *成绩发布（后期任务）*
     - *统计信息（后期任务）*

- 学生端

  1. **添加课程**
     - **作业**
       - **作业提交机制**
         - **通过文件上传**
         - *app内自带markdown编辑器，app内做题提交（后期任务）*
       - *作业提醒系统（后期任务）*
     - **签到**
     - **查看成绩**
     - *问答聊天室（后期任务）*



</br>

## 5 项目前端构建

**TODO: 前端逻辑**



</br>

## 4 项目后端构建

### 4.1 后台数据库

关系型数据库包含三个关系表：User， Course， Homework

1. User有用户基本信息，还包括用户类型：TA，Student
2. Course是课程可以由TA创建，Student选择添加课程
3. Homework是TA布置的任务，任务有个标识符表示隶属于某个Course，代表某个课程的作业

**TODO: 涵玮完善数据库的表设计，提交接口说明到项目API文档中**

### 4.2 后端服务器搭建

相关接口说明

**TODO: 涵玮搭建服务器，完善前端http请求接口，同时提交接口协议说明到项目API文档中**

