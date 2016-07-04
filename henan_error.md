# 河南省
### 河南省的数据存在以下问题：
#### A.changeInfo
存在一些公司更多信息没有加载
#### B.comBossShareChangeInfo
没有翻页获得多页信息
#### C.bossGiveMoneyInfo
出资方式没有返回或者返回的是企业公示信息中的股东出资信息；
#### D.comReportInfo
**1.sharesChangeInfo**

原网页股权变更信息不存在，sharesChangeInfo返回的是changeInfo修改信息；

**2.changeInfo**

changeInfo修改信息被当做sharesChangeInfo返回，所以changeInfo没有返回；

**3.comAssetsInfo**

comAssetsInfo的turnover信息包含了mainTurnover的信息

**4.bossGiveMoneyInfo**

bossGiveMoneyInfo也返回了修改信息的内容；

**5.siteInfo**

返回了企业基本信息的内容
#### E.pledgeInfo
remark表示的是变化情况返回的却是公示日期的内容，程序没有定义公示日期这个字段

### 1.焦作市景安机电设备制造有限公司
#### a.changeInfo
更多信息没有返回

![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-07-04%20%E4%B8%8B%E5%8D%887.38.11.png)
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-07-04%20%E4%B8%8B%E5%8D%887.38.17.png)

#### b.comBossShareChangeInfo
有多页信息，程序没有翻页。

![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-07-04%20%E4%B8%8B%E5%8D%887.41.02.png)
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-07-04%20%E4%B8%8B%E5%8D%887.41.09.png)

#### c.comReportInfo
**1.sharesChangeInfo**
股权变更信息不存在，sharesChangeInfo返回的是changeInfo修改信息；

![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-07-04%20%E4%B8%8B%E5%8D%887.46.38.png)
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-07-04%20%E4%B8%8B%E5%8D%887.46.44.png)

**2.changeInfo**
changeInfo修改信息被当做sharesChangeInfo返回，所以changeInfo没有返回；
**3.comAssetsInfo**
comAssetsInfo的turnover信息包含了mainTurnover的信息

![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-07-04%20%E4%B8%8B%E5%8D%887.52.10.png)

**4.bossGiveMoneyInfo**
bossGiveMoneyInfo也返回了修改信息的内容；

![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-07-04%20%E4%B8%8B%E5%8D%887.55.01.png)

### 2.河南新郑农村商业银行股份有限公司
#### a.bossGiveMoneyInfo
出资方式没有返回

![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-07-04%20%E4%B8%8B%E5%8D%889.12.31.png)
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-07-04%20%E4%B8%8B%E5%8D%889.12.21.png)

#### b.pledgeInfo
remark表示的是变化情况返回的却是公示日期的内容，程序似乎没有定义公示日期这个字段

![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-07-04%20%E4%B8%8B%E5%8D%889.17.34.png)
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-07-04%20%E4%B8%8B%E5%8D%889.17.42.png)

### 3.鹤壁市鑫源石油运输有限公司
#### a.comBossGiveMoneyInfo
多页信息没有翻页，并且针对一个股东多次出资，信息会出错。

![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-07-04%20%E4%B8%8B%E5%8D%889.29.02.png)
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-07-04%20%E4%B8%8B%E5%8D%889.29.28.png)
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-07-04%20%E4%B8%8B%E5%8D%889.29.15.png)

#### b.comBossShareChangeInfo
有多页信息，程序没有翻页。

![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-07-04%20%E4%B8%8B%E5%8D%889.32.37.png)
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-07-04%20%E4%B8%8B%E5%8D%889.32.31.png)

### 4.郑州市第一建筑工程集团有限公司

#### a.bossGiveMoneyInfo
返回的是企业公示信息中的股东出资信息

![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-07-04%20%E4%B8%8B%E5%8D%889.55.36.png)
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-07-04%20%E4%B8%8B%E5%8D%889.54.44.png)

#### b.comReportInfo
**siteInfo**返回了企业基本信息的内容

![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-07-04%20%E4%B8%8B%E5%8D%889.59.07.png)
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-07-04%20%E4%B8%8B%E5%8D%8810.00.02.png)

