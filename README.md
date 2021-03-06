Dinning（订餐系统）
========

专为企业定制的方便快捷的订餐工具。

## 一、关于

当今社会生活节奏越来越快，特别是企业或团体，项目时间紧，人员众多而繁杂时，为节省时间，企业或团队都会进行集体订餐。但由于工作繁忙无法抽出时间去统计每个人想要吃什么，吃那家的饭菜，更无精力去计算每次的详细费用及情况，因此就产生了快捷订餐的需求。

订餐系统（Dinning）是一个帮助团队或者公司订餐的工具。对于订餐的整个流程来说，我们只关注中间的部分，即员工订餐到统计的过程。我们的目标是实现快速订餐并准确统计结果以发给供应商打包送餐，当然也包括一些基本的对菜品的导入、订单查询和用户管理。

### 1.具体使用场景

___使用场景决定了需求，如果你所在的场景不是如下描述，请谨慎使用本系统。___

1. 供应商提供菜单
2. 负责人将菜单导入订餐系统
3. 负责人开启订餐
4. 成员注册系统
5. 成员开始订餐并生成订单
6. 负责人统计今日订单
7. 负责人将订单导出发给供应商

### 2.功能特性

#### 2.1 方便的菜品管理

每个地区，每家店面的饭菜，甚至每天的食物都是不一样的，能够方便的导入菜品是订餐的第一步。本订餐系统不仅提供了方便的导入功能(包括菜品、单价以及详细内容等)，并能对导入的菜品进行有效的管理；此外还提供了每日菜单公告的功能，进行额外的公告提醒。

#### 2.2 快捷的订餐方式

在每天的某个时刻，由有管理权限的人员激活订餐，注册者即可开始快捷订餐之旅。在订餐页面订餐者可方便的选取一份或多份饭菜，然后生成订单；也可在多个订单中生成多份饭菜。无论使用哪种方式，只要提交订单，订餐者所要的饭菜都会被最终统计。

#### 2.3 实用的订单统计

订单的统计是本系统的核心功能。当管理者停止今日订餐后，可对今日订单进行统计，并能输出个性化的统计内容，例如今日订餐有什么多少份还有什么多少份等。此外还可对订单进行各种使用操作处理以及导出今日订单到word方便打印发给某餐馆或某供应商。

### 3.架构特性

订餐系统（Dinning）使用Spring2.5/Struts2/iBatis为架构，支持Oracle和MySql数据库；可使用常见的Web服务器（例如Tomcat,Websphere等）进行部署。

### 4.开源免费

订餐系统（Dinning）使用MIT协议开源，因此你无需考虑附带责任，只需在你的代码中保留原许可协议即可。

## 二、配置部署



