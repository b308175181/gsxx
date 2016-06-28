# 江苏省
### 就目前观察结果看，江苏省数据存在以下问题：
#### A.punishInfo,comAdministrativeLicenseInfo,comPunishInfo返回异常信息
#### B.companyInfo
不止是以下公司，观察其他公司的数据发现当**regNo表示统一社会信用代码**，数据不能返回。
#### C.comReportInfo
**1.**comReportInfo中comAssetsInfo的**turnover**信息重复两次,**2.**企业基本信息当成**siteInfo**。
### 1.太仓明昌金属制品有限公司
#### a.punishInfo,comAdministrativeLicenseInfo,comPunishInfo
原网页并没有行政处罚信息和行政许可信息，而返回的数据形式特别奇怪，这种数据在我打开网页加载数据的一瞬间有看到，但是之后再也没见过了。
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-28%20%E4%B8%8B%E5%8D%882.55.47.png)
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-28%20%E4%B8%8B%E5%8D%883.30.32.png)
#### b.companyInfo
**regNo统一社会信用代码**字段信息没有返回
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-28%20%E4%B8%8B%E5%8D%885.08.42.png)
#### c.comReportInfo
**1.**comReportInfo中comAssetsInfo的**turnover**信息重复两次,**2.**企业基本信息当成**siteInfo**。
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-28%20%E4%B8%8B%E5%8D%883.33.46.png)
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-28%20%E4%B8%8B%E5%8D%883.38.58.png)
#### d.mainMemberInfo,mortageInfo
**主要人员信息**,**动产抵押登记信息**没有返回,动产抵押登记信息*有详情*。
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-28%20%E4%B8%8B%E5%8D%883.08.27.png)
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-28%20%E4%B8%8B%E5%8D%883.12.10.png)
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-28%20%E4%B8%8B%E5%8D%883.19.06.png)
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-28%20%E4%B8%8B%E5%8D%883.28.28.png)
### 2.江苏省建工集团有限公司
#### a.punishInfo,comAdministrativeLicenseInfo,comPunishInfo
和太仓明昌金属制品有限公司的问题相同；
#### b.companyInfo
**regNo统一社会信用代码**字段信息没有返回
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-28%20%E4%B8%8B%E5%8D%884.54.21.png)
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-28%20%E4%B8%8B%E5%8D%884.46.02.png)
#### c.comReportInfo
**1.**comReportInfo中comAssetsInfo的**turnover**信息重复两次,**2.**企业基本信息当成**siteInfo**。
### 3.南京九天药房连锁有限公司
#### a.punishInfo,comAdministrativeLicenseInfo,comPunishInfo
和太仓明昌金属制品有限公司的问题相同；
#### b.companyInfo
其中的regNo表示注册号，数据返回正常。
![](http://o7qrps1cr.bkt.clouddn.com/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202016-06-28%20%E4%B8%8B%E5%8D%885.36.08.png)
#### c.comReportInfo
**1.**comReportInfo中comAssetsInfo的**turnover**信息重复两次,**2.**企业基本信息当成**siteInfo**。


