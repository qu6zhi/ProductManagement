# 兵器库

# CMS内容管理系统

* Pimcore
>官网：https://pimcore.com/
>>资产和文档管理
* Discuz
* Laravel
* Sphinx
> https://github.com/sphinx-doc/sphinx


# Coding开发
* ReviewBoard
>官网：https://www.reviewboard.org/
>>ReviewBoard 是个开源的、可扩展的、友好的基于 Web 的代码评审工具，是用 Python 框架 Django 开发的。
>>>Installing Power Pack
>>>>$ pip install -U ReviewBoardPowerPack
http://downloads.beanbaginc.com/powerpack/
* JetBrains 系列软件汉化包
> https://github.com/pingfangx/jetbrains-in-chinese


* Trac
* Redmine
* GitLab
>官网：https://about.gitlab.com/
>>是一个利用 Ruby on Rails 开发的开源应用程序,实现一个自托管的 Git 项目仓库,可通过 Web 界面进行访问公开的或者私人项目。
>>>GitLab 社区版(CE)和企业版(EE)
>>>>清华源https://mirrors.tuna.tsinghua.edu.cn/gitlab-ce/

# 搜索引擎
* Nutch
> http://nutch.apache.org/
* Sphinx
> https://github.com/sphinx-doc/sphinx
优势
1.强大而快速
Sphinx近年来不断发展，已经能够提供近乎实时的搜索。它的速度包括超过500个查询/秒对1,000,000个文档，最大的索引编号估计为250亿个文档。
Craigslist在Sphinx的帮助下，每天提供超过3亿次查询。它每月的页面浏览量超过500亿。
Infegy使用Sphinx为22亿以上的Twitter，Facebook和各种博客文章编制索引，以提供富有洞察力的社交媒体监控和分析查询。

2.多值属性搜索
Sphinx在分面搜索功能方面拥有丰富的经验。
优酷土豆（好歹看到了一个中国的应用^_^）是中国最大的视频网站，它使用Sphinx进行多值属性搜索，每月向超过4亿用户提供内容，每秒峰值量为15,000个查询。
在Greenice，我们最近使用Sphinx作为电子商务计算机硬件商店。我们对品牌，类型，用途，屏幕分辨率，矩阵，对角线，HDD容量，SSD容量等属性实施了多值属性搜索。



* Elasticsearch

1.近实时索引
Elasticsearch能够几乎立即（在不到1秒内）快速索引快速变化的数据。在数据库不断更新的项目中使用它是合适的。
例如，在优步，Elasticsearch实时汇总动态（激增）定价和供应定位的业务指标。它能够在高峰时间每秒处理超过1,000个查询。

2.高可扩展性
当数据库增长时，查找起来就变得更加困难。但是当您的数据库变大时，Elasticsearch会扩展，因此搜索速度不会降低。
Expedia的，最大的酒店和机票聚合之一，通过提供最高追求，每天1TB具有每秒300K的事件。在Elasticsearch的帮助下，他们成功地改善了客户的预订体验。

3.储存
ES不仅可以用作索引器，还可以用作数据存储器。尽管如此，我们不建议将其用作主存储，并且我们仍然将数据保存在主数据库中以获得更好的安全性和可靠性，仅使用ES来索引数据和存储日志。

4.数据可视化
这是今天在ES中完美实现的时尚功能之一。Elastic Stack（ES，Logstash和Kibana插件的组合）是分析的绝佳工具。它允许实时监控应用程序上的流量（访问者总数，唯一访问者数量，IP地址，最常见的查询，大多数请求的页面，使用的设备和浏览器，按时间显示的流量日志等等） 。
此信息在仪表板中的彩色图表，地图和表格中可视化。这对于与分布式团队合作非常有帮助，因为每个人都可以立即查看最新信息，然后使用这些数据更好地了解您的受众并改进产品的内容和用户体验。
在ES的帮助下，The Guardian拥有一个强大的分析系统，每天能够处理4000万个文档，以创建内容消费的愿景。
在Netflix，在高峰时段有800万个事件和每秒24GB，ES用于视频查看活动，UI活动，错误日志，性能，诊断事件等事件的实时分析。

5.安全分析
Elastic Stack也是一款出色的安全分析工具。近实时日志分析和可视化使您可以识别安全威胁（Web服务器出现问题，链接断开，未经授权访问的尝试，攻击位置等）。您可以从此官方弹性视频中了解更多信息。
通过迁移到ES，戴尔通过确保只有授权人员才能访问其群集来提高安全性。戴尔还将其服务器数量减少了25-30％。

6.机器学习
Elasticsearch可以受益于X-Pack商业插件提供的机器学习功能。机器学习算法专注于时间序列数据中的异常检测和异常检测。

7. AMAZON ELASTICSEARCH SERVICE
Amazon Elasticsearch Service可以快速轻松地进行设置，并在云中运行和扩展Elasticsearch，而无需配置您自己的服务器。

* Solr

Solr是另一个基于Apache Lucene的搜索引擎，因此它与Elasticsearch有许多共同的特性。但是，他们在建筑方面仍然不同。

Solr的优势
1.多值属性搜索
Solr拥有非常棒的搜索功能，这使得该解决方案非常适合像Zappos这样的电子商务网站，这些网站使用Solr搜索和导航150,000种鞋子和其他产品。

2.丰富的功能集
Solr可以开箱即用，具有高度可配置性（甚至超过Elasticsearch）的丰富的全文搜索功能。Solr支持各种建议器实现，突出显示功能（在字段中输入的单词的可视指示）和拼写检查器/“你的意思是什么？”（在ES中不存在）。
在Greenice，我们在为澳大利亚客户开展项目时处理了Solr。他们的网站旨在交流小企业家之间的经验。搜索功能包括突出显示，建议和排序。

3.丰富的内容文档
Solr是少数可以阅读丰富内容文档的搜索引擎之一，包括PDF，Word，XML或纯文本。
这非常适合需要查看网站内大量PDF或Word文件的项目（包括合同，简历，学习材料，电子书等）。

4.数据可视化
香蕉是一种可视化工具（ Kibana的一个分支）适用于Solr，允许管理员动态监控仪表板中的事件和日志。
例如，在银行业务中，经理将能够检索有关失败交易的信息，并且几乎“即时”找出每个问题的原因，极大地减少了手工工作。这也可以减少对日志的手动搜索。

5.机器学习
索尔与合作 彭博，实施机器学习（(Learning-to-Rank plug-in) 根据来自更复杂查询的分数，使用文档重新排名的概念。机器学习旨在为用户提供即时搜索最相关公司，人员和新闻的更好体验。
> http://www.sphinxsearch.org/archives/492

# 网络工具
* IP Scanner
* Network Radar
* Wireshark
>网络数据抓包分析工具
* Burpsuite
>是用于攻击 Web 应用程序的集成平台，包含了许多工具。
* FileZilla
>FTP客户端
* Xshell

# 监控
* Zabbix
* Nagios
* Cacti
* Solarwinds

# Python Web 项目部署
* https://github.com/pyinstaller/pyinstaller
* http://www.pyinstaller.org/downloads.html
* http://blog.itpub.net/26736162/viewspace-2644904/
* https://zhuanlan.zhihu.com/p/65731845
* https://www.pocoo.org/
* https://www.palletsprojects.com/
