## 周刊材料存档

1、

曾经有两年时间，我离开了前端开发，去做其他事情。等我回来了，一切都变了，Angularjs 消失了，React 成为业界的主流。RESTful 接口不流行了，开始流行 GraphQL。Kubernetes 真的起飞了。仅仅会 React 还不够，实际上人们用的是 next.js，然后大家都在研究各种 redux 替代品。TypeScript 变得无处不在。

-- [Hacker News 读者](https://news.ycombinator.com/item?id=28410937)

1、

达尔文是一个内向的人，选择住在伦敦东南近20英里的乡下，避开城里的各种会议和聚会，专心在书房写作。他偶尔会招待一两个访客，但是通常通过信件与外界联系。他在书房里安装了一面镜子，这样他就可以从工作中抬起头，看看邮递员是否正在路上——这是 19 世纪版本的电子邮件刷新按钮。

--[《思想家与步行之间的关系》](https://lithub.com/on-the-link-between-great-thinking-and-obsessive-walking/)

1、[美国无线网络覆盖地图](https://fcc.maps.arcgis.com/apps/webappviewer/index.html?id=6c1b2e73d9d749cdb7bc88a0d1bdd25b)

![](https://cdn.beekka.com/blogimg/asset/202108/bg2021081012.jpg)

一个很有意思的地图应用，用来查看美国三大全国性移动服务商（T-mobile、Verizon、AT&T）在美国某个地区的网络覆盖情况。

1、

世界上只有美国这个国家，你可以在那里生活几年后称自己为美国人。

-- [Hacker News 读者](https://news.ycombinator.com/item?id=28054943)。这令人联想到深圳，国内好像只有那里，你可以住上几年后称自己为深圳人。

## KubeSphere 材料

https://zhuanlan.zhihu.com/p/74590744

KubeSphere （https://kubesphere.io）是在 Kubernetes 之上构建的开源容器混合云，提供全栈的 IT 自动化运维的能力，简化企业的 DevOps 工作流。

KubeSphere是青云科技在2018年开始做，从写第一行代码就开源的容器平台。

KubeSphere由青云科技在2019年发布，一经推出，就在极短的时间内迅速成为具有国际影响力的云原生开源项目，现已成为全球三大基于Kubernetes的主流容器平台之一。在 GitHub 平台，KubeSphere现有Star数超6500个。

## 优点

- 首先是开箱即用，直接点一点鼠标就可以打造一个高可用的 K8s 集群。这一点对我们这种没有专职运维的中小团队来说很重要。根据我的亲身经历，要从零开始搭建一个高可用的 K8s 集群还是有点门槛的，没有接触过这方面的运维人员，一时半会是搞不定的，其中的坑也非常多。

我们不用在服务搭建与系统优化上花费太多时间，可以把更多的精力放到业务上去。之前我们还自己搭建数据库，缓存，搜索集群，后来全部都使用云服务了。

## 概念

多云
根据Rightscale的同一项调查，84% 的企业组织的应用程序和工作流分散在本地、私有云和公共云环境中。

首先，Docker公司发布了一个开源容器化产品。当他们推出付费容器管理服务时，谷歌已经开发并开源了他们自己的容器管理解决方案 Kubernetes ，赢得了市场。然后，在 Docker 发布了托管容器的企业解决方案后，Google 推出了 Google Kubernetes Engine，再次击败了 Docker。

专访青云“四爷”和他的 KubeSphere
https://zhuanlan.zhihu.com/p/74590744

IDG 2020 年的一项调查发现，81% 的组织在云中至少拥有一个应用程序或部分计算基础设施（高于 2011 年的 51%），并且 55% 的组织目前在多个云中使用多个云提供商。云战略。

“多云”只是意味着使用两个或多个不同的云提供商并利用它们的优势来满足您的需求。这种方法提供了一种替代方案，可以替代依赖一个云提供商或本地基础设施来处理所有事情。

多云是指使用多个公有云平台。混合云是指私有云与公共云的结合。私有云通常托管在本地基础架构上，但也可以由第三方托管。私有云和公共云之间的主要区别在于，私有云的基础架构、硬件和软件都在您的企业或组织专用的私有网络上维护。

更复杂的是，一家使用私有云与多个公共云相结合的公司实际上是通过使用混合多云策略

多云的好处

- 灾难恢复。
- 故障转移。
- 成本优化。
- 避免供应商锁定。
- 数据主权。
- 获得专业服务。


https://www.backblaze.com/blog/multi-cloud-strategy-architecture-guide/

