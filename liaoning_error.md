# 辽宁省
### 从现阶段观察情况看，辽宁省数据存在以下问题：
#### A.bossGiveMoneyInfo和comBossGiveMoneyInfo
工商公示信息的股东信息中并没有详情，而bossGiveMoneyInfo返回的是企业公示信息中的股东出资信息(comBossGiveMoneyInfo),并且实际的comBossGiveMoneyInfo的出资方式(认缴和实缴)也没有返回；
#### B.comReportInfo
**1.****regNo**字段信息没有返回；**2.**comAssetsInfo的**turnover**内容重复两次
#### C.mortageInfo
动产抵押登记信息信息不全，字段内容**没有抓回**，如**mortageMoney，mortageScope，mortageType**抓回的内容为空字符串，但实际上原网页内容是存在的。
### 1.盘锦万顺实业有限公司
#### a.bossGiveMoneyInfo
工商公示信息的股东信息中并没有详情，而bossGiveMoneyInfo返回的是企业公示信息中的股东出资信息(comBossGiveMoneyInfo)。
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-29%20%E4%B8%8B%E5%8D%882.00.00.png)
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-29%20%E4%B8%8B%E5%8D%882.00.10.png)
#### b.comBossGiveMoneyInfo
**出资方式**信息没有返回
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-29%20%E4%B8%8B%E5%8D%882.03.26.png)
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-29%20%E4%B8%8B%E5%8D%882.02.10.png)
#### c.comReportInfo
两个问题：**1.**年报中的**regNo**字段信息没有返回
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-29%20%E4%B8%8B%E5%8D%882.09.41.png)
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-29%20%E4%B8%8A%E5%8D%8811.19.42.png)
**2.**年报中的comAssetsInfo的**turnover**内容重复两次
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-29%20%E4%B8%8A%E5%8D%8811.17.48.png)
### 2.大连远东工具有限公司
#### a.mortageInfo
动产抵押登记信息信息不全，字段内容**没有抓回**，如**mortageMoney，mortageScope，mortageType**抓回的内容为空字符串，但实际上原网页内容是存在的。
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-29%20%E4%B8%8B%E5%8D%882.46.09.png)
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-29%20%E4%B8%8B%E5%8D%882.46.01.png)
#### b.comReportInfo
与盘锦万顺实业有限公司有相同的问题。
### 3.盘锦辽油晨宇集团有限公司
#### a.comBossGiveMoneyInfo
企业公示信息的股东出资信息中有**修改信息**。
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-29%20%E4%B8%8B%E5%8D%883.23.56.png)























