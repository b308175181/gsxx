# 吉林省
### 从现阶段观察情况看，吉林省数据存在以下问题：
#### A.bossGiveMoneyInfo和comBossGiveMoneyInfo
工商公示信息的股东信息中并没有详情，而bossGiveMoneyInfo返回的是企业公示信息中的股东出资信息(comBossGiveMoneyInfo),并且实际的comBossGiveMoneyInfo的出资方式(认缴和实缴)也没有返回；
#### B.changeInfo
存在有多条多页changeInfo，但只返回一条信息。
#### C.comReportInfo
comAssetsInfo中turnover信息重复两次

### 1.吉林白山正茂药业股份有限公司
#### a.comReportInfo
comAssetsInfo中turnover信息重复两次；

![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-29%20%E4%B8%8B%E5%8D%885.07.28.png)
### 2.延边新视野文化传媒股份有限公司
#### a.bossGiveMoneyInfo
工商公示信息的股东信息中并没有详情，而bossGiveMoneyInfo返回的是企业公示信息中的股东出资信息(comBossGiveMoneyInfo)。

![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-29%20%E4%B8%8B%E5%8D%889.45.52.png)
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-29%20%E4%B8%8B%E5%8D%889.46.03.png)
#### b.comBossGiveMoneyInfo
**出资方式**信息没有返回

![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-29%20%E4%B8%8B%E5%8D%889.47.51.png)
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-29%20%E4%B8%8B%E5%8D%889.47.33.png)
#### c.changeInfo
只返回一条changeInfo信息。

![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-29%20%E4%B8%8B%E5%8D%889.50.09.png)
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-29%20%E4%B8%8B%E5%8D%889.51.13.png)



