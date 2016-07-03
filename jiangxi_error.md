# 江西省
### 江西省的数据存在以下问题：
#### A.comBossGiveMoneyInfo和bossGiveMoneyInfo
股东信息的详情中没有出资信息，返回的是企业公示信息中的股东出资信息，而股东出资信息中的出资方式没有返回。
#### B.股权冻结信息
有的公司司法协助公示信息中有股权冻结信息，其中有详情内容，这部分信息没有返回。
#### C.mortageInfo
mortageDetail没有返回
#### D.comReportInfo
bossGiveMoneyInfo,investmentInfo,sharesChangeInfo,siteInfo这几个字段要么没有返回信息，要么返回的信息是错误的。comAssetsInfo要么没有返回，要么和其他省份一样turnover包括了mainTurnover的信息。
### 1.江西人之初营养科技股份有限公司
#### a.comBossGiveMoneyInfo和bossGiveMoneyInfo
股东信息的详情中没有出资信息，返回的是企业公示信息中的股东出资信息，而股东出资信息中的出资方式没有返回。

![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-07-01%20%E4%B8%8B%E5%8D%884.30.36.png)
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-07-01%20%E4%B8%8B%E5%8D%884.31.09.png)
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-07-01%20%E4%B8%8B%E5%8D%884.35.56.png)
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-07-01%20%E4%B8%8B%E5%8D%884.42.53.png)

#### 2.股权冻结信息
司法协助公示信息中有股权冻结信息，其中有详情内容，这部分信息没有返回。

![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-07-01%20%E4%B8%8B%E5%8D%884.45.42.png)
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-07-01%20%E4%B8%8B%E5%8D%884.47.01.png)

#### 3.comReportInfo
bossGiveMoneyInfo,investmentInfo,sharesChangeInfo,siteInfo这几个字段都发生了错误，定位错误，一个字段包括了其他字段的信息。comAssetsInfo中turnover也包括了mainTurnover的信息。
**bossGiveMoneyInfo**

![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-07-01%20%E4%B8%8B%E5%8D%885.34.29.png)

**investmentInfo**

![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-07-01%20%E4%B8%8B%E5%8D%885.36.48.png)

**sharesChangeInfo**

![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-07-01%20%E4%B8%8B%E5%8D%885.39.09.png)

**siteInfo**

![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-07-01%20%E4%B8%8B%E5%8D%885.39.58.png)

**comAssetsInfo**

![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-07-01%20%E4%B8%8B%E5%8D%885.35.48.png)

### 2.于都高山青草奶业有限公司
#### a.comBossGiveMoneyInfo和bossGiveMoneyInfo
与江西人之初营养科技股份有限公司不同，这两个字段返回的信息都是正确的，与原网页的信息是一致的，出资方式也有返回。
#### b.comReportInfo
13,14,15三年的年报，只有13年的年报发生以下的情况：bossGiveMoneyInfo信息错误，包含了年报的修改信息；

![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-07-03%20%E4%B8%8B%E5%8D%881.32.37.png)

### 3.赣州五环机器股份有限公司
#### a.mortageInfo
mortageDetail没有返回

![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-07-03%20%E4%B8%8B%E5%8D%881.57.19.png)
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-07-03%20%E4%B8%8B%E5%8D%881.57.13.png)

#### b.comBossGiveMoneyInfo和bossGiveMoneyInfo
与江西人之初营养科技股份有限公司相同
#### 3.comReportInfo
**bossGiveMoneyInfo**
信息错误，错误的信息应该是股东信息，但是在年报中根本没有出现

![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-07-03%20%E4%B8%8B%E5%8D%882.14.21.png)

**companyInfo**,**siteInfo**,**comAssetsInfo**没有返回

![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-07-03%20%E4%B8%8B%E5%8D%882.12.53.png)
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-07-03%20%E4%B8%8B%E5%8D%882.13.03.png)
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-07-03%20%E4%B8%8B%E5%8D%882.13.39.png)




