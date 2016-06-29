# 内蒙古自治区
### 内蒙古的数据存在以下问题：
#### A.bossInfo
存在bossInfo定位不准，导致信息错位，有多页的股东信息**只返回最后一页**的股东信息；
#### B.comBossGiveMoneyInfo和bossGiveMoneyInfo
两个字段均存在相同问题，有两种情况：**1.**数据没有返回；**2.**返回数据，但是有多页信息**只返回第一页信息**。
#### C.comReportInfo
comReportInfo中的**对外的投资信息investmentInfo**没有返回。
#### D.抽查检查信息没有返回
#### E.changeInfo
changeInfo中有**详情**链接，没有返回详情中内容。
#### F.comAdministrativeLicenseInfo
存在comAdministrativeLicenseInfo中**detail**数据返回错误信息
#### G.comBossShareChangeInfo
原网页存在comBossGiveMoneyInfo信息，股东出资信息有变更信息，而comBossShareChangeInfo返回的是变更信息，而这个**不等同于股权变更信息**。
### 1.内蒙古河套投资股份有限公司
#### a.bossInfo
股东信息定位不准，导致信息错位。并且共35页的股东信息只返回了最后一页的股东信息。
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-29%20%E4%B8%8A%E5%8D%8812.27.43.png)
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-29%20%E4%B8%8A%E5%8D%8812.28.05.png)
#### b.comBossGiveMoneyInfo
**企业公示信息中的股东出资信息**没有返回；
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-29%20%E4%B8%8A%E5%8D%8812.34.54.png)
#### c.comReportInfo
comReportInfo中的**对外的投资信息investmentInfo**没有返回。
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-29%20%E4%B8%8A%E5%8D%8812.48.21.png)
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-29%20%E4%B8%8A%E5%8D%8812.53.28.png)
#### d.抽查检查信息没有返回
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-29%20%E4%B8%8A%E5%8D%8812.56.14.png)
### 2.内蒙古民丰种业有限公司
#### a.bossInfo
和内蒙古河套投资股份有限公司有相同的问题；
#### b.changeInfo
changeInfo中有详情链接，没有返回详情中内容。
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-29%20%E4%B8%8A%E5%8D%881.03.45.png)
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-29%20%E4%B8%8A%E5%8D%881.03.53.png)
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-29%20%E4%B8%8A%E5%8D%881.09.31.png)
#### c.comReportInfo
comReportInfo中的**对外的投资信息investmentInfo**没有返回。
### 3.海拉尔农垦（集团）大河湾农牧有限责任公司
#### a.bossInfo
和内蒙古河套投资股份有限公司有相同的问题；
#### b.bossGiveMoneyInfo和comBossGiveMoneyInfo
只返回第一页的数据。
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-29%20%E4%B8%8A%E5%8D%881.57.54.png)
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-29%20%E4%B8%8A%E5%8D%8810.25.44.png)
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-29%20%E4%B8%8A%E5%8D%881.58.09.png)
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-29%20%E4%B8%8A%E5%8D%8810.25.59.png)
### 4.内蒙古中国国际旅行社有限责任公司
#### a.bossInfo
和内蒙古河套投资股份有限公司有相同的问题；
#### b.bossGiveMoneyInfo
bossGiveMoneyInfo在bossInfo的详情中，该数据没有返回
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-29%20%E4%B8%8A%E5%8D%882.05.07.png)
#### c.comAdministrativeLicenseInfo
comAdministrativeLicenseInfo中detail数据返回错误信息
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-29%20%E4%B8%8A%E5%8D%882.09.03.png)
#### d.comBossGiveMoneyInfo
comBossGiveMoneyInfo数据没有返回
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-29%20%E4%B8%8A%E5%8D%889.29.53.png)
#### e.comBossShareChangeInfo
返回的是comBossGiveMoneyInfo的变更信息，而且有多页，只返回第一页的信息。
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-29%20%E4%B8%8A%E5%8D%889.11.01.png)
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-29%20%E4%B8%8A%E5%8D%889.11.45.png)















