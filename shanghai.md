# 上海市
### 上海市的数据存在以下问题：
#### A.comBossGiveMoneyInfo和bossGiveMoneyInfo
两种情况**1.**无论是股东信息的详情还是企业公示信息的出资信息都不存在的情况下，返回的数据中却有bossGiveMoneyInfo；**2.**返回的是企业公示信息中出资信息。
#### B.changeInfo
更多信息最后有“收起更多”，这四个字需要删除；
#### C.comReportInfo
comReportInfo中comAssetsInfo的turnover信息包含了mainTurnover的信息
#### D.comBossGiveMoneyInfo
comBossGiveMoneyInfo数据没有返回，有的有变更信息，数据也与原网页有出入。
### 1.上海紫江企业集团股份有限公司
#### a.changeInfo
收起更多需要删除

![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-30%20%E4%B8%8A%E5%8D%8811.44.31.png)

#### b.comReportInfo
comReportInfo中comAssetsInfo的turnover信息包含了mainTurnover的信息

![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-30%20%E4%B8%8A%E5%8D%8811.54.08.png)

#### c.comBossGiveMoneyInfo
comBossGiveMoneyInfo数据没有返回，有变更信息。

![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-30%20%E4%B8%8B%E5%8D%8812.48.52.png)

### 2.上海统一星巴克咖啡有限公司
#### a.bossGiveMoneyInfo
查看原网页，股东信息的详情中并没有出资信息（企业公示信息中也没有股东出资信息）。
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-30%20%E4%B8%8B%E5%8D%882.08.07.png)

![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-30%20%E4%B8%8B%E5%8D%882.05.30.png)

#### b.comAdministrativeLicenseInfo
其他部门公示信息中有行政许可信息,该部分信息没有返回；

![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-07-01%20%E4%B8%8A%E5%8D%8811.32.41.png)

#### c.comPunishInfo
其他部门公示信息中有行政处罚信息,该部分信息没有返回；

![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-07-01%20%E4%B8%8A%E5%8D%8811.35.31.png)

### 3.上海禾易建筑设计有限公司
#### a.bossGiveMoneyInfo
股东信息中没有详情内容，返回的是企业公示信息中的股东出资信息。

![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-07-01%20%E4%B8%8B%E5%8D%8812.02.56.png)
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-07-01%20%E4%B8%8B%E5%8D%8812.03.17.png)

### 4.上海浦东海博汽车服务有限公司
#### a.comBossGiveMoneyInfo和bossGiveMoneyInfo
股东信息详情中并没有出资信息，而企业公示信息中的有股东出资信息，但是实缴额错误，另外comBossGiveMoneyInfo也没有返回。

![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-07-01%20%E4%B8%8B%E5%8D%882.30.48.png)
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-07-01%20%E4%B8%8B%E5%8D%882.31.13.png)
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-07-01%20%E4%B8%8B%E5%8D%882.30.59.png)



