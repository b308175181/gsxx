# 北京市
### 就观察结果看，北京的数据存在以下问题：
#### A.bossInfo
存在bossInfo信息**没有抓回**，以及**发起人信息**是否也可以算是bossInfo？
#### B.bossGiveMoneyInfo
存在bossGiveMoneyInfo信息**没有返回**的情况，有些数据返回但是信息的**拆分有错误**，另外一些bossGiveMoneyInfo的信息**包含在bossInfo的详情中**；
#### C.changeInfo
存在changeInfo信息**没有返回**的情况，有些数据返回，但是包**含有详情**的信息有错误；
#### D.comReportInfo
存在comReportInfo信息**没有返回**，有返回的信息中也出现**siteInfo信息错误**（a.除了把网站信息抓回，还把企业基本信息抓回，b.本身原网页没有网站信息，但是返回了网站信息，网站信息中的内容实际上是企业基本信息）。
#### E.抽查检查信息
源网站有抽查检查信息，但是我们的代码似乎没有抓该字段，原始数据中没有出与该信息相对应的字段。
### 1.北京京东世纪信息技术有限公司
#### a.changeInfo缺失
changeInfo字段有详情链接，链接进去后是具体变更信息。
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-27%20%E4%B8%8B%E5%8D%8812.43.22.png)
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-27%20%E4%B8%8B%E5%8D%8812.44.02.png)
### 2.拉卡拉支付股份有限公司
#### a.bossGiveMoneyInfo
bossGiveMoneyInfo信息拆分错误
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-27%20%E4%B8%8B%E5%8D%8812.53.12.png)
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-27%20%E4%B8%8B%E5%8D%8812.57.20.png)
#### b.comBossGiveMoneyInfo与bossGiveMoneyInfo的区别是？
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-27%20%E4%B8%8B%E5%8D%882.05.19.png)
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-27%20%E4%B8%8B%E5%8D%882.05.10.png)
#### c.comReportInfo里面的siteInfo信息有误
把企业基本信息也包括进去了
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-27%20%E4%B8%8B%E5%8D%882.11.19.png)
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-27%20%E4%B8%8B%E5%8D%882.19.44.png)
### 3.北京市逗逗烟花爆竹有限公司
#### a.bossGiveMoneyInfo包含在bossInfo的详情中
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-27%20%E4%B8%8B%E5%8D%882.24.16.png)
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-27%20%E4%B8%8B%E5%8D%882.24.27.png)
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-27%20%E4%B8%8B%E5%8D%882.24.42.png)
#### b.抽查检查信息,没有这个字段
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-27%20%E4%B8%8B%E5%8D%882.29.32.png)
### 4.北京七维航测科技股份有限公司
#### a.发起人信息算股东信息吗？
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-27%20%E4%B8%8B%E5%8D%882.33.49.png)
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-27%20%E4%B8%8B%E5%8D%882.35.53.png)
#### b.changeInfo
changeInfo字段内容没有返回，变更信息中有详细内容
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-27%20%E4%B8%8B%E5%8D%882.40.44.png)
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-27%20%E4%B8%8B%E5%8D%882.41.04.png)
### 5.北京链家房地产经纪有限公司
#### a.changeInfo
changeInfo中有详细内容，字段信息也有错误
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-27%20%E4%B8%8B%E5%8D%882.48.46.png)
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-27%20%E4%B8%8B%E5%8D%882.40.26.png)
### 6.四方电气（集团）股份有限公司
#### a.发起人信息
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-27%20%E4%B8%8B%E5%8D%883.33.54.png)
#### b.comReportInfo
年报中的siteInfo源信息并没有该字段，而返回的数据似乎把企业基本信息当成siteInfo了
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-27%20%E4%B8%8B%E5%8D%883.39.02.png)
#### c.changeInfo
changeInfo字段信息没有返回，变更信息包含详情。
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-27%20%E4%B8%8B%E5%8D%883.47.27.png)



