# Awesome-Hyperledger-Fabric
超级账本 Fabric 技术开发资源列表  
A Curated List of Awesome Hyperledger Fabric Resources

# 目录
- [基本资料](#基本资料)
- [核心项目](#核心项目)
- [工具](#工具)
- [开发](#开发)
    - [SDK](#SDK)
    - [入门](#入门)
    - [示例](#示例)
- [文档](#文档)
    - [Fabric开发文档](#Fabric开发文档)
    - [SDK开发文档](#SDK开发文档)
- [文章](#文章)
- [视频](#视频)
- [案例](#案例)
- [书籍](#书籍)
- [人物](#人物)
- [社区](#社区)
- [其他](#其他)


# 基本资料
* [官网](https://www.hyperledger.org/projects/fabric) - 项目官网网站【英文】
* [开发文档](https://hyperledger-fabric.readthedocs.io) - 开发文档中心【英文】
* [白皮书](https://www.hyperledger.org/resources/publications#white-papers) - 项目的白皮书【英文】
* [Fabric Github](https://github.com/hyperledger/fabric) - 开源项目 Github 地址【英文】
* [Hyperledger GitHub](https://github.com/hyperledger) - 超级账本项目相关的开源项目【英文】

# 核心项目
* [Fabric](https://github.com/hyperledger/fabric) - 联盟区块链底层技术平台【英文】
* [Fabric-CA](https://github.com/hyperledger/fabric-ca) - CA 证书颁发机构搭建工具【英文】

# 工具
* [区块链浏览器](https://github.com/hyperledger/blockchain-explorer) - Fabric 的区块链浏览器工具，支持快速搭建【英文】
* [区块链 BaaS](https://github.com/hyperledger/cello) - 基于 python 和 nodejs 的 fabric 网络运维管理平台，支持  docker swam、k8s、物理机、虚拟云部署，可快速搭建一个 BaaS 平台【英文】
* [性能测试工具](https://github.com/hyperledger/caliper) - 基于 nodejs 的区块链基准测试工具，支持多个区块链（如 fabric、fisco/bcos 和以太坊等）的性能测试【英文】

## 第三方脚手架
* [Convector](https://github.com/hyperledger-labs/convector) - 类似 Composer 脚手架工具，为 hyperledger fabric 提供开发工具【英文】

# 开发
## SDK
* [Java](https://github.com/hyperledger/fabric-sdk-java) - 基于Java的链访问SDK【英文】
* [Node.js](https://github.com/hyperledger/fabric-sdk-node) - node.js的SDK【英文】
* [Go](https://github.com/hyperledger/fabric-sdk-go) - GO语言的链访问SDK【英文】
* [Python](https://github.com/hyperledger/fabric-sdk-py) - Python语言的链访问SDK【英文】

## 入门
* [基础概念](https://hyperledger-fabric.readthedocs.io/en/latest/key_concepts.html) - 定义了基础组件和关键概念，如区块链网络、身份、联盟成员、管理策略、chaincode 智能合约、排序服务、私有数据和通道等【英文】
* [入门指南](https://hyperledger-fabric.readthedocs.io/en/latest/getting_started.html#) - 快速入门教程，安装所需的依赖软件说明，指导如何下载安装超级账本的二进制可执行程序、docker 镜像和实例代码以及搭建一个简单的 Fabric 区块链网络，并且简单介绍了 Fabric 应用开发的基本过程如通道创建、chaincode 智能合约的部署调用等【英文】
* [应用开发指南](https://hyperledger-fabric.readthedocs.io/en/latest/developapps/developing_applications.html) -  结合一个多方商业机构间商业票据流通 Fabric 区块链应用场景，详细阐述了如何在Fabric 应用开发中如何进行需求分析、业务流程分析、区块链智能合约数据结构设计以及应用元素拆解设计等应用开发流程【英文】
* [chaincode 基础](https://hyperledger-fabric.readthedocs.io/en/latest/chaincode.html) - 介绍什么是 Fabric chaincode 以及 chaincode 的生命周期【英文】
* [chaincode 开发者手册](https://hyperledger-fabric.readthedocs.io/en/latest/chaincode4ade.html) - 结合官方提供的简单资产管理智能合约实例，向开发者介绍了chaincode 的开发、调试、安装、部署、调用以及权限控制等【英文】

## 示例

### 官方示例
* [fabric-samples](https://github.com/hyperledger/fabric-samples) - fabric 官方提供的包括网络搭建、车辆管理、商业票据等示例代码【英文】

### Token 
* [Kuma token](https://github.com/Kunstmaan/hyperledger-fabric-kuma-token-example) - 基于 fabric 发布简单的 token 示例【英文】

### 供应链
* [hlf1.4-supply-chain](https://github.com/ialberquilla/hlf1.4-supply-chain) - 基于 fabric 1.4 的供应链概念性验证示例【英文】
* [financial-platform-with-blockchain](https://github.com/callmewindow/financial-platform-with-blockchain) - 北航学生基于 fabric 区块链的供应链金融平台课程实践

# 文档

## Fabric开发文档
* [官方开发文档](https://hyperledger-fabric.readthedocs.io/https://hyperledger-fabric.readthedocs.io/) -  官方开发文档网站，包括项目介绍、网络搭建、智能合约开发以及 dapp 开发等资源【英文】
* [官方开发文档中文索引](https://github.com/ConsensusDev/Awesome-Hyperledger-Fabric/blob/master/Hyperledger_Fabric_Docs_CN_Index.md)
* [官方开发文档中文社区翻译](https://hyperledgercn.github.io/hyperledgerDocs/)

## SDK开发文档
* [nodejs SDK 开发文档](https://hyperledger.github.io/fabric-sdk-node/release-1.4/index.html) - nodejs sdk 官方开发文档【英文】
* [java SDK 开发文档](https://hyperledger.github.io/fabric-gateway-java/) - nodejs sdk 官方开发文档【英文】
* [go SDK 开发文档](https://github.com/hyperledger/fabric-sdk-go) - nodejs sdk 官方开发文档【英文】
* [python SDK 开发文档](https://github.com/hyperledger/fabric-sdk-py/tree/master/docs) - python sdk 官方开发文档【英文】

# 文章

## 技术选型
* [我们放弃以太坊选择了超级账本](https://mp.weixin.qq.com/s?__biz=MzU2ODQzNzAyNQ==&mid=2247485060&idx=1&sn=397be46bb07c060ce63f0d83183a69d8&) - OpenGift 团队探索了基于超级账本 Fabric 区块链的生产实践，并对以太坊和超级账本 Fabric 进行了技术选型上的比较分析
* [Hyperledger Fabric、FISCO BCOS 等五大联盟链横向对比](https://www.lieyunwang.com/archives/448365) - 本文选择了Hyperledger Fabric、FISCO BCOS、微软的Coco、企业以太坊联盟（EEA）及R3的Corda这五个具有一定影响力的联盟链，拟从设计理念、生态、效率、扩展性、节点管理与权限管理、智能合约、部署与运维友好性、隐私保护八个方面进行比对，以供各位开发者、爱好者参考

## 开发教程

### 供应链
* [使用 Hyperledger Fabric 来搭建区块链供应链追溯](https://coding-bootcamps.com/ultimate-guide-for-building-a-blockchain-supply-chain-using-hyperledger-fabric-and-composer.html) - 讲解了 Hyperledger Fabric 开发区块链供应链追溯，包括基本概念介绍、智能合约的设计编写、业务网络结构的规划和部署【英文】


# 视频
* [Youtbue 官方地址](https://www.youtube.com/channel/UCCFdgCWH_1vCndMPVqQlwZw/videos) - Fabric 官方在 Youtube 上发布的介绍视频【英文】
* [超级账本 BDD开发](https://www.youtube.com/watch?v=70gLjrlUwlI) - 官方介绍BDD（行为驱动开发）开发模式【英文】
* [Gossip 协议](https://www.youtube.com/watch?v=FQGkvZI55oI) - 官方介绍 p2p 网络中使用的 Gossip 协议【英文】

# 案例
* [应用案例集合](https://www.hyperledger.org/resources/publications#case-studies) - 官方提供的案例集合 【英文】

# 书籍
* [《区块链原理、设计与应用》](https://item.jd.com/12159265.html) - 由超级账本 Fabric 核心开发者杨保华等撰写的 Fabric 架构设计与应用开发书籍
* [《HyperLedger Fabric开发实战：快速掌握区块链技术》](https://item.jd.com/12381034.html) - 由浅入深讲述 Fabric 架构原理以及应用开发
* [《Hyperledger Cookbook》](https://www.amazon.com/Hyperledger-Cookbook-implementing-blockchain-frameworks-ebook/dp/B07Q4DD8TN) - 全面介绍了 Hyperledger 区块链项目集合, 包括 Fabric, Sawtooth, Indy, Burrow, 和 Iroha; 以及 Composer, Explorer 和 Caliper 等工具【英文】
* [《Blockchain By Example》](https://www.amazon.com/Blockchain-Example-Decentralized-applications-Hyperledger/dp/1788475682) - 通过实例讲解如何使用 Bitcoin, Ethereum, and Hyperledger 来开发 dapp，以及使用 IPFS 和 swarm 来实现去中心化文件存储【英文】

# 人物

* [杨保华](http://yeasy.github.io/) - 超级账本全球技术委员会委员、Fabric 核心开发人员

# 社区
* [StackOverflow](https://stackoverflow.com/questions/tagged/hyperledger-fabric)
* [邮件列表](https://lists.hyperledger.org/g/fabric)
* [RocketChat](https://chat.hyperledger.org/) 
* [Wiki 主页](https://wiki.hyperledger.org/display/fabric/) 
* [线下活动](https://www.meetup.com/pro/hyperledger)
* [共识区块链技术社区](https://zhuanlan.zhihu.com/consensusdev)  
![共识区块链技术社区](https://github.com/ConsensusDev/awsome-FISCO-BCOS/blob/master/files/ConsensusDev.jpg)

# 其他

## 贡献<!-- omit in toc --> 
欢迎大家提供其他跟 Hyperledger Fabric 相关的资源
可以直接提交Pull Request  
也可以联系我:
* 微信  
![Reed的WeChat](https://github.com/ConsensusDev/awsome-FISCO-BCOS/blob/master/files/reed.jpg)

 
