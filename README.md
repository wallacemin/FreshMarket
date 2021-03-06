# FreshMarket
新鲜购O2O新型的网上购菜系统
## 项目背景
近年来，国内食品安全事件时有发生，消费者对高品质、高安全的食品的需求越来越大，天猫、京东、苏宁等电商企业纷纷在生鲜电商入住，电商巨头的入住为生鲜电商市场带来了强劲的动力。凭借着优质的产品、便捷的服务、良好的网购环境，生鲜电商成为新的电商蓝海，满足了消费者对健康食品的需求，赢得了广大消费者的心。在未来的几年里，国内必将有一大批的企业进入生鲜电商市场，生鲜电商行业也会慢慢走向整合的道路，生鲜电商市场也将会越来越大，市场秩序进一步走向规范。但是这些生鲜电商缺乏快速的配送能力，不能提供比菜市场更好的购物体验，而且没有稳定的货源和受制于季节性影响，生鲜缺货时有发生，难以形成规模流通，用户购买不到满意的商品。所以我们的新鲜购网站致力于提供商品展示及订购为核心的网上购物服务宣传自己商店的商品并将自己的商品展现给客户，让客户通过网站便能对自由的选择地购买商品，并采用线下超市的体系，依托于超市原有的资源优势，在采购、运输和保险存储有很大的优势，由于超市遍布社区周边，很好的解决了生鲜的配送过程，给用户一种比菜市场更快速更方便的用户体验。 该网站是通过用户登录浏览商品、购买、确定购买、实现用户模块功能。其中订单的生成，网站后台系统，通过系统管理员管理商品、订单、用户来实现。
## 技术
本平台利用JSP 以及 Servelet 技术+ MySQL数据库构建网站。


## 功能划分
通过对用户需求的分析，可以分析出该网上购物系统大致可以把前台分为四个功能模块：浏览查询商品模块、查看订单模块、购物车模块、个人信息管理模块。后台分为四个模块：商品管理模块，商品种类管理模块，查询商品模块，订单管理模块。
## 功能块描述
### 面向用户部分功能：
(1) 注册功能。顾客首先要注册为网上商城的用户。注册时只要填写登录用户名、密码。注册后，用户可继续如实填写详细个人信息及收货人信息，同时可修改密码、查询个人订单。

(2) 选择产品功能。顾客浏览网上商城，将自己需求的产品放入到购物车中，可连续添加商品。

(3) 管理购物车。顾客选择完商品后可进入购物车页面，查看自己要购买的商品，可修改某一商品数量、取消购买某商品和清空整个购物车。

(4) 订单功能。顾客确定购物车中的商品后提交订单，如顾客已填写收货人信息，则页面显示该信息并由顾客确认。如尚未填写则显示相应表单请其填写，系统记录顾客提交的收货人信息以便其下次购物时使用。顾客提交订单后可在我的订单查询该订单，并可对尚未处理的订单进行付款、确认收货等操作。

(5) 付款功能。顾客在订单被销售方确认后，要选择付款方式，并付款给销售方，然后才可以收到货。

### 后台管理部分功能：
(1) 管理订单功能。管理员可以查看所有会员的订单，还可以查看指定状态的会员订单，对订单进行物流发货

(2) 管理商品功能。管理员可以添加、修改、删除商品。

(3) 管理商品种类功能，管理员可以添加、修改、删除商品种类。
----------

## 流程

![image](https://github.com/cckevincyh/FreshMarket/blob/master/img/1.png)
----------

## 数据流图

![image](https://github.com/cckevincyh/FreshMarket/blob/master/img/2.png)
----------

## 登录界面 

![image](https://github.com/cckevincyh/FreshMarket/blob/master/img/login.png)
----------
## 注册界面

![image](https://github.com/cckevincyh/FreshMarket/blob/master/img/regist.png)

----------
## 主界面

![image](https://github.com/cckevincyh/FreshMarket/blob/master/img/index.png)

----------

## 个人信息界面

![image](https://github.com/cckevincyh/FreshMarket/blob/master/img/info.png)

----------

## 收货地址

![image](https://github.com/cckevincyh/FreshMarket/blob/master/img/address.png)

----------

## 购物车

![image](https://github.com/cckevincyh/FreshMarket/blob/master/img/cart.png)

----------
## 结算

![image](https://github.com/cckevincyh/FreshMarket/blob/master/img/Settlement.png)

----------
## 支付

![image](https://github.com/cckevincyh/FreshMarket/blob/master/img/pay.png)

----------
## 我的订单

![image](https://github.com/cckevincyh/FreshMarket/blob/master/img/order.png)

----------

## 后台

![image](https://github.com/cckevincyh/FreshMarket/blob/master/img/admin.png)

