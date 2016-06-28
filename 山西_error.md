# 山西省
### 从目前的情况看，山西的数据存在以下问题：
#### A.comReportInfo
**1。**存在一些年份的年报详细内容没有抓回，**2**turnover把营业总收入和营业总收入中主营业务收入都包括了；**3.**siteInfo信息有误
#### B.存在bossInfo和bossGiveMoneyInfo,comBossGiveMoneyInfo信息没有返回

### 1.阳泉市腾飞商贸有限公司
#### a.comReportInfo
**siteInfo**,本身原网页没有网站信息，但是返回了网站信息，网站信息中的内容实际上是企业基本信息(和北京存在相同的问题）。
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-28%20%E4%B8%8B%E5%8D%8812.05.12.png)
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-28%20%E4%B8%8B%E5%8D%8812.02.04.png)
**comAssetsInfo**，*turnover*信息重复两次(天津、河北也存在相同的问题)。
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-28%20%E4%B8%8B%E5%8D%881.59.27.png)
### 2.太原道合盛贸易有限公司
#### a.comReportInfo
**1.**13年的报告详细内容没有抓回；
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-28%20%E4%B8%8B%E5%8D%889.30.40.png)
**2.**除了siteInfo阳泉市腾飞商贸有限公司存在相同的问题，营业总收入turnover和营业总收入中主营业务收入mainTurnover，turnover把营业总收入和营业总收入中主营业务收入都包括了，也就是说阳泉市腾飞商贸有限公司的turnover其实也是相同的原因。
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-28%20%E4%B8%8B%E5%8D%889.22.19.png)
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-28%20%E4%B8%8B%E5%8D%889.23.11.png)
#### b.bossGiveMoneyInfo,bossInfo（不是个例）
bossInfo和bossGiveMoneyInfo信息没有返回
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-28%20%E4%B8%8B%E5%8D%889.31.48.png)
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-28%20%E4%B8%8B%E5%8D%889.34.17.png)
### 3.太原市乐创流体科技有限公司
#### a.comBossGiveMoneyInfo
comBossGiveMoneyInfo信息没有返回
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-28%20%E4%B8%8B%E5%8D%889.51.38.png)


