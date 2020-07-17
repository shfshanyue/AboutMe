## 基本信息

+ 姓名: 王贤
+ 手机号: 18335103278
+ 邮箱: xianger94@gmail.com
+ 院校：太原科技大学网络工程/16届
+ github(3K+ star): [https://github.com/shfshanyue](https://github.com/shfshanyue)
+ 博客: [https://shanyue.tech](https://shanyue.tech)

## 工作经历

+ 2016/07 - 至今     [智课教育](http://www.smartstudy.com/)

  > 全栈开发(后端-node 和前端为主，测试环境运维与生产环境 k8s 维护)，团队技术负责人

+ 2015/12 - 2016/03  [豆瓣](https://douban.com)

## 简述

在公司负责**tob云教育项目**的日常开发维护，用户反馈及迭代更新，并带领有六个小伙伴的团队，**四年时间经历了多个前后端项目从立项到维护的整个开发过程**。

对当前我司在线教育的产品业务、盈利模式及技术有深入的理解。如关于考试系统的技术与业务思考可以参考我的博客: [在线教育之考试系统](https://shanyue.tech/business/exam.html)

除了负责 toB 业务外，早期也负责整个测试环境的维护以及现在的 k8s 集群维护。关于公司测试环境服务器的搭建，我对其基础服务进行了抽象与改进，并搭建在了自己的服务器作为测试。

另外我的博客 <https://shanyue.tech> 也会记录自己一些关于技术与业务的思考，这里有我的一些系列文章：

+ [高级前端进阶系列](https://shanyue.tech/frontend-engineering/)
+ [Node 进阶](https://shanyue.tech/node/)
+ [个人服务器运维指南](https://shanyue.tech/op/)

## 开源

### package

+ [promise-utils](https://github.com/shfshanyue/promise-utils): 一些有用的 promise 工具函数，如 map, filter, retry 与 sleep
+ [shfshanyue/serverless-template-zh (serverless)](https://github.com/shfshanyue/serverless-template-zh): 中国云厂商 serverless framework 模板及示例，服务于内部及个人函数应用
+ [shfshanyue/ansible-op (ansible role)](https://github.com/shfshanyue/ansible-op): 公司及个人常用服务器运维脚本
+ [shfshanyue/apollo-server-starter (graphql template)](https://github.com/shfshanyue/apollo-server-starter): 基于 apollo-server 的 graphql 后端脚手架

### Side Project

+ [shfshanyue/shici](https://github.com/shfshanyue/shici): [诗词网](https://shici.xiange.tech) 站长，日常流量 500 PV，前端，后端，爬虫及运维独立完成，后端及爬虫项目 github 不可见
+ [shfshanyue/wechat](https://github.com/shfshanyue/wechat): 个人公众号的微信开发，用以管理个人公众号。另相关开源项目还有微信机器人开发、微信公众号SDK开发及自动发文章定时脚本开发，在 github 上可以找到

## 项目经验

### 教育云系统

教育云是一个服务于各大高校的一个 toB 的项目，主要业务为考试系统，课程服务，以及写作的 AI 批改。我在其中主要负责项目前后端的需求评审，正常迭代，开发以及优化

### 技术栈

+ 前端: react typescript apollo-client
+ 运维：k8s gitlab-ci elk sentry prometheus grafana
+ 后端: koa apollo-server websocket postgres redis

> 关于 graphql 的部分写了一个脚手架: <https://github.com/shfshanyue/apollo-server-starter>

### 日常工作

+ 维护和优化前后端项目，负责前后端项目的任务分配，代码审核以及上线，解决日常反馈问题
+ 监控 sentry 系统，及时解决线上问题
+ 监控 elk，及时发现慢查询，慢请求，不合理的 SQL (如一条 api 对应 100 条 SQL) 并及时解决问题
+ 与产品以及商务开会，确定需求

### 详细

其中技术上我负责了 ts 引入，异常上报，devops接入k8s，监控，grafana 部分图表制作，graphql 的引入以及在 ES 上对日志的优化等部分，业务上负责了考试系统、题库系统、作业模块、课程模块的开发

以下是考试系统的疑难问题

![考试系统疑难点图](https://shanyue.tech/assets/img/exam-business.drawio.05a37563.png)

关于疑难问题的业务思考及解决方案可参考: [在线教育中技术与业务疑难问题之考试系统](https://shanyue.tech/business/exam.html)

还有一些其他的点如下所示：

+ **负责并独立开发 graphql 服务端项目并且全面负责机构后台前端项目，及提高性能**
+ 接入 k8s，并写相对应的资源配置文件
+ 解决一些 OOM 及 CPU 过高的问题
+ 接入日志与异常，提高排查问题速度
+ 负责考试系统开发，并解决其中疑难问题
+ 负责题库系统开发，并解决其中疑难问题
