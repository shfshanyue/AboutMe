## 基本信息

+ 姓名: 王贤
+ 手机号: 18335103278
+ 邮箱: xianger94@gmail.com
+ 院校：太原科技大学网络工程/16届
+ github: [https://github.com/shfshanyue](https://github.com/shfshanyue)
+ 博客: [https://shanyue.tech](https://shanyue.tech)


## 工作经历

+ 2016/07 - 至今     [智课教育](http://www.smartstudy.com/)

  > 全栈开发(后端和前端为主，测试环境运维与生产环境 k8s 维护)，团队技术负责人

+ 2015/12 - 2016/03  [豆瓣-实习](https://douban.com)

## 简述

在公司负责一条业务线的日常开发维护(七人团队)，用户反馈及迭代更新。曾全权负责(从立项到上线)了一个后端项目，两个小程序，三个前端项目及一个 SSR 项目，目前也在持续维护多个后端和多个前端项目，并把一个后端整改成 graphql，也曾与其他同事共同维护一个 flutter 项目。另外早期也会用 scrapy 做一些爬虫。

除了负责业务外，早期也负责整个测试环境的维护以及现在的 k8s 集群维护。关于公司测试环境服务器的搭建，我对其基础服务进行了抽象与改进，并搭建在了自己的服务器，方便试错及测试， **如我的服务器模拟公司的基础服务，独立部署了 consul/elk/gitlab/prometheus/grafana/docker/k8s**。

另外我的博客 <https://shanyue.tech> 也会记录自己一些关于技术的思考，这里有我的一些系列文章：

+ [高级前端进阶系列](https://shanyue.tech/frontend-engineering/)
+ [flutter 笔记](https://shanyue.tech/flutter-guide/)
+ [个人服务器运维指南](https://shanyue.tech/op/)
+ [k8s 实践](https://github.com/shfshanyue/learn-k8s)
+ [使用 graphql 构建 web 应用](https://github.com/shfshanyue/graphql-guide)

## 开源

### As a maintainer

+ [shfshanyue/cls-session (npm)](https://github.com/shfshanyue/cls-session): Node CLS 的实现，并避免了 Promise 在 async_hooks 中内存泄漏问题
+ [shfshanyue/serverless-template-zh (serverless)](https://github.com/shfshanyue/serverless-template-zh): 中国云厂商 serverless framework 模板及示例 （更快的访问速度）
+ [shfshanyue/ansible-op (ansible role)](https://github.com/shfshanyue/ansible-op): 个人服务器运维脚本
+ [shfshanyue/apollo-server-starter (graphql template)](https://github.com/shfshanyue/apollo-server-starter): 基于 apollo-server 的 graphql 后端脚手架
+ [shfshanyue/vim-config](https://github.com/shfshanyue/vim-config): vim config
+ [shfshanyue/tmux-config](https://github.com/shfshanyue/tmux-config): tmux config

### As a contributor

+ [webpack](https://github.com/webpack/webpack/pull/4525): 关于 webpack cli 与 config 冲突的一个兼容
+ [git-tips/tips](https://github.com/git-tips/tips/graphs/contributors): 关于 git 的几个小技巧

## Side Project

> 我自己的应用大多部署在我自建的服务器，serverless (微信公众号开发)以及阿里云的 OSS (纯前端)上。

+ [shfshanyue/2019-ncov (Star 466)](https://github.com/shfshanyue/2019-ncov): 全国新型冠状病毒，肺炎疫情实时省市地图， **单日 PV 最高48万** <https://ncov.shanyue.tech/>
+ [shfshanyue/tomato](https://github.com/shfshanyue/tomato): 基于 vue 与 cordova 的番茄闹钟APP
+ [shfshanyue/eleven](https://github.com/shfshanyue/eleven): 小程序十一选五小助手，单日 PV 不到100
+ [shfshanyue/cheat-sheets](https://github.com/shfshanyue/cheat-sheets): cheat sheets，单日 PV 不到十个
+ [shfshanyue/reacht-rubic](https://github.com/shfshanyue/react-rubic): 使用 react 开发的魔方，尚未正式上线
+ [shfshanyue/shici](https://github.com/shfshanyue/shici): 使用 next.js 与 graphql 做一个诗词小站，并使用自建的 gitlab-ci/traefik 自动部署，单日 PV 不到100，服务器架构切换时闭站
+ [shfshanyue/shici-server](https://github.com/shfshanyue/shici-server): 使用 graphql 做一个诗词小站的服务端，并使用自建的 gitlab-ci/traefik 自动部署
+ [shfshanyue/wechat-ncov](https://github.com/shfshanyue/wechat-ncov): 个人微信机器人，用以自动通过好友，加群后欢迎语以及基金、疫情信息监控
+ [shfshanyue/wechat](https://github.com/shfshanyue/wechat): 个人公众号的微信开发，包括面试题API及看文需扫码关注功能
+ [shfshanyue/tieba_post](https://github.com/shfshanyue/tieba_post): 模拟百度贴吧的登录及自动发帖
+ [shfshanyue/spider (python)](https://github.com/shfshanyue/spider): python 写的网页定时备份小工具
+ [shfshanyue/koa-mini](https://github.com/shfshanyue/koa-mini): 40 行代码实现一个 koa

## 项目经验

### 教育云系统

#### 简介

教育云是一个服务于各大高校的一个 toB 的项目，主要业务为考试系统，课程服务，以及写作的 AI 批改。我在其中主要负责项目前后端的需求评审，正常迭代，开发以及优化

#### 技术栈

+ 前端: react typescript apollo-client
+ 运维：k8s gitlab-ci elk sentry prometheus grafana
+ 后端: koa apollo-server websocket postgres redis

其中我负责了 ts，sentry，gitlab-ci，peomethues metric，grafana 部分图表，graphql 的引入以及在 ES 上对日志的优化

> 关于 graphql 的部分写了一个脚手架: <https://github.com/shfshanyue/apollo-server-starter>

#### 日常工作

+ 维护和优化前后端项目，负责前后端项目的任务分配，代码审核以及上线，解决日常反馈问题
+ 监控 sentry 系统，及时解决线上问题
+ 监控 elk，及时发现慢查询，慢请求，不合理的 SQL (如一条 api 对应 100 条 SQL) 并及时解决问题
+ 与产品以及商务开会，确定需求

#### 详细

+ **负责并独立开发 graphql 服务端项目并且全面负责机构后台前端项目**
+ **进行项目优化，使 graphql 项目能够做到按需加载请求所需字段，按需查询数据库字段，压缩了计算时间，响应大小以及传输时间**
+ graphql 能够产生大部分前端所需接口，增加了前后端同学的开发效率，减少了后端同学的重复劳动
+ 迁移部分老后端接口至 graphql，并且使 graphql 作为其它项目的服务层，以后前端（包括前台，后台，以及机构后台）新接口由 graphql 代替，逐步迁移掉老后端
+ 引导前端完成node中间层项目，使前端更加熟悉业务，并且能够更加自由组合自己所需数据
+ **使用 graphql 提高前端性能，充分利用缓存，避免冗余 API 查询以及更好地用户体验**
+ **完成项目的容器化，并添加 CI/CD，使项目自动部署，减少人力成本**
+ 优化项目镜像，减少 build 时间，在测试环境的部署时间控制在一分钟以内
+ 使用 CI, k8s 结合 nginx，完成项目的多分支开发，即每个分支都有一个地址进行开发测试，完成通过测试合并到主分支，保障项目质量
+ 对后端项目使用 typescript 重构，提高项目质量
+ **解决高并发问题，对项目添加自动水平扩展，增加了项目的 High Available**
+ 使用 redis 完成了 pub/sub，解决了多节点 ws 推送问题
+ 添加了 sentry，自动收集生产环境报错，使开发人员能够及时响应问题
+ **对日志进行优化，添加 requestId, 能够快速在 elk 中定位到相关 log，利于查询性能问题以及定位 bug**

