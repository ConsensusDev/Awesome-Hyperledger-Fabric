# Hyperledger Fabric Docs Chinese Index
Hyperledger Fabric 官方文档中文索引

# 目录
- [开发指南](#开发指南)
    - [快速指南](#快速指南)
    - [智能合约](#智能合约)
    - [状态数据库](#状态数据库)
    - [隐私安全](#隐私安全)
    - [技术架构](#技术架构)
    - [性能测试](#性能测试)
    - [其他](#其他)  
    	- [对比选型](#对比选型)  
    	- [常见问题](#常见问题)  
    	- [术语参考](#术语参考)  
       	- [版本更新](#版本更新)  	
- [运维指南](#运维指南)
    - [快速指南](#快速指南)
    - [节点配置](#节点配置)
    - [通道配置](#通道配置)
    - [chaincode 智能合约](#chaincode智能合约)
    - [权限安全](#权限安全)
    - [FabricCA](#FabricCA)
    - [共识出块](#共识出块)
    - [运维监控](#运维监控)
    - [命令参考](#命令参考)
    - [其他](#其他)
- [参考资料](#参考资料)
    - [开发语言](#开发语言)
    - [开发框架](#开发框架)
    - [第三方工具](#第三方工具)
- [其他](#其他)
    - [贡献](#贡献)

# 官方文档
* [官方开发文档主页](https://hyperledger-fabric.readthedocs.io/https://hyperledger-fabric.readthedocs.io/) -  官方开发文档网站，包括项目介绍、网络搭建、智能合约开发以及 dapp 开发等资源【英文】

# 开发指南
## 快速指南
* [关键概念](https://hyperledger-fabric.readthedocs.io/en/latest/key_concepts.html) - 定义了基础组件和关键概念，如区块链网络、身份、联盟成员、管理策略、chaincode 智能合约、排序服务、私有数据和通道等【英文】
* [新手入门](https://hyperledger-fabric.readthedocs.io/en/latest/getting_started.html#) - 运维安装所需的依赖软件说明，指导如何下载安装超级账本的二进制可执行程序、docker 镜像和实例代码以及搭建一个简单的 Fabric 区块链网络，并且简单介绍了 Fabric 应用开发的基本过程如通道创建、chaincode 智能合约的部署调用等【英文】
* [应用开发指南](https://hyperledger-fabric.readthedocs.io/en/latest/developapps/developing_applications.html) -  结合一个多方商业机构间商业票据流通 Fabric 区块链应用场景，详细阐述了如何在Fabric 应用开发中如何进行需求分析、业务流程分析、区块链智能合约数据结构设计以及应用元素拆解设计等应用开发流程【英文】
 * [Fabcar 入门开发教程](https://hyperledger-fabric.readthedocs.io/en/latest/write_first_app.html#) - 结合官方提供的车辆管理实例对 Fabric区块链网络的搭建、nodejs应用的安装、成员加入以及智能合约的调用进行了详细的说明【英文】
* [商业票据开发教程](https://hyperledger-fabric.readthedocs.io/en/latest/tutorial/commercial_paper.html) - 结合官方提供的多方商业结构间商业票据流通实例对 Fabric 区块链网络的搭建、各方商业机构智能合约设计、安装初始化以及业务流程流转过程进行了详细的说明【英文】


## 智能合约
* [什么是 chaincode 智能合约](https://hyperledger-fabric.readthedocs.io/en/latest/chaincode.html) - 介绍什么是 Fabric chaincode 以及 chaincode 的生命周期【英文】
* [chaincode 开发者手册](https://hyperledger-fabric.readthedocs.io/en/latest/chaincode4ade.html#install-hyperledger-fabric-samples) - 结合官方提供的简单资产管理智能合约实例，向开发者介绍了chaincode 的开发、调试、安装、部署、调用以及权限控制等【英文】

## 状态数据库
* [使用 CouchDB](https://hyperledger-fabric.readthedocs.io/en/latest/couchdb_tutorial.html) - 介绍了使用 CouchDB 作为状态数据库的优势、如何在 Fabric 中开启 CouchDB 以及 CouchDB 的索引创建以及分页查询等【英文】
* [使用 CouchDB 作为状态数据库](https://hyperledger-fabric.readthedocs.io/en/latest/couchdb_as_state_database.html) - 对 goLevelDB 和 CouchDB 作为状态数据库进行了对比，以及如何进行 CouchDB 配置、chaincode 如何使用 CouchDB、如何建立数据库索引等【英文】

## 隐私安全
* [Fabric 私有数据的使用](https://hyperledger-fabric.readthedocs.io/en/latest/private_data_tutorial.html) - 介绍了如何定义数据集、chaincode智能合约读写私有数据等【英文】
* [私有数据使用介绍](https://hyperledger-fabric.readthedocs.io/en/latest/private-data-arch.html) - 介绍了私有数据集的定义、私有数据的传播方式、chaincode 智能合约对私有数据的调用以及私有数据的销毁等【英文】

## 技术架构

* [事务流程（Transaction flow](https://hyperledger-fabric.readthedocs.io/en/latest/txflow.html)）- 介绍了事务的发起、背书签名、验证和出块过程和机制【英文】 
* [服务发现（Service Discovery）](https://hyperledger-fabric.readthedocs.io/en/latest/discovery-overview.html)- 介绍了节点之间如何使用服务发现来动态获取通道配置、背书策略以及网络节点布局【英文】
* [通道概念（Channel）](https://hyperledger-fabric.readthedocs.io/en/latest/channels.html)-  通道是 fabric 网络中成员之间可选择性地加入的群组，可保证发生的事务隔离于群组成员之外，从而保证事务的私有和私密性【英文】
* [基于通道的节点事件服务](https://hyperledger-fabric.readthedocs.io/en/latest/peer_event_services.html) - 事件服务允许监听节点的出块以及 chaincode 自定义的事件类型【英文】
* [读写集语义  (Read-Write set sematics) ](https://hyperledger-fabric.readthedocs.io/en/latest/readwrite.html)- 介绍了 fabric 事务运行过程中基于读写版本控制的读写集语义保证数据读写一致性【英文】
* [流言数据传播协议（Gossip protocol）](https://hyperledger-fabric.readthedocs.io/en/latest/gossip.html)- fabric 采用 Gossip 数据传播协议来进行 p2p 节点发现、通道成员管理、账本区块同步等操作【英文】

## 性能测试
* [超级账本区块链性能指标](https://www.hyperledger.org/resources/publications/blockchain-performance-metrics#) - 该白皮书定义了区块链性能评测的基本术语和关键指标【英文】
* [Fabric验证阶段性能优化](https://arxiv.org/abs/1907.08367) - 通过对Fabric验证过程进行剖析重构后，在事务验证过程中采用链码缓存和状态数据库的并行读写，实现验证阶段性能的增长（状态数据库为 CouchDB 性能增长为2倍，LevelDB为1.3倍）【英文】

## 其他

* [错误处理](https://hyperledger-fabric.readthedocs.io/en/latest/error-handling.html) - Fabric 的golang 开发错误处理最佳实践 【英文】

### 对比选型
* [我们放弃以太坊选择了超级账本 ](https://mp.weixin.qq.com/s?__biz=MzU2ODQzNzAyNQ==&mid=2247485060&idx=1&sn=397be46bb07c060ce63f0d83183a69d8&)- OpenGift 团队探索了基于超级账本 Fabric 区块链的生产实践，并对以太坊和超级账本 Fabric 进行了技术选型上的比较分析【译文】

### 常见问题
* [官方 FAQ](https://hyperledger-fabric.readthedocs.io/en/latest/Fabric-FAQ.html) - 社区常问问题【英文】

### 术语参考
* [术语表](https://hyperledger-fabric.readthedocs.io/en/latest/glossary.html) - 定义了使用的术语词汇表及其介绍【英文】
* [cli 命令参考](https://hyperledger-fabric.readthedocs.io/en/latest/command_ref.html) - cli 组件命令行命令参考 [英文]

### 版本更新
* [最新版本说明](https://hyperledger-fabric.readthedocs.io/en/latest/whatsnew.html#release-notes) - 最新版本更新说明【英文】

# 运维指南
## 快速指南
* [搭建你的第一个Fabric 网络](https://hyperledger-fabric.readthedocs.io/en/latest/build_network.html#) - 结合官方提供的 first-network 实例，阐述了如何使用示例中提供的 byfn.sh 工具脚本进行CA证书的生成和网络的启停；configtxgen 工具生成orderer 创世块、通道配置事务、以及锚节点配置事务；chaincode 智能合约的安装部署和调用；byfn.sh 运行调用的 docker-compose 文件分析以及使用 couchdb 作为状态数据库的优势和实践【英文】
* [如何向通道中加入新的组织成员](https://hyperledger-fabric.readthedocs.io/en/latest/channel_update_tutorial.html) - 结合官方提供的 first-network 实例，阐述了如何为新组织成员生成MSP证书、如何获取通道创世块以及将其加入通道【英文】

## 节点配置
* [排序服务节点搭建](https://hyperledger-fabric.readthedocs.io/en/latest/orderer_deploy.html) -  如何搭建 orderer 服务节点 【英文】
* [MSP 成员服务管理](https://hyperledger-fabric.readthedocs.io/en/latest/msp.html) - MSP配置以及最佳实践【英文】

## 通道配置
* [通道配置configtx ](https://hyperledger-fabric.readthedocs.io/en/latest/configtx.html)- Fabric 的共享配置保存在每个通道的系列配置事务中，这里详细介绍了配置信息的数据格式【英文】
* [如何更新通道配置](https://hyperledger-fabric.readthedocs.io/en/latest/config_update.html) - 对通道中的出块设置、成员结构、权限策略等配置参数进行了阐述，并描述了如何通过通道更新事务进行配置【英文】
* [如何定义通道能力（channel capabilities）](https://hyperledger-fabric.readthedocs.io/en/latest/capability_requirements.html)- Fabric 网络中允许运行不同版本的 fabric 程序，通道能力通过定义各种操作产生一致性行为的层级来保证不同版本 fabric 程序之间的兼容性和一致性【英文】

## chaincode智能合约
* [chaincode 外部编译器和启动器](https://hyperledger-fabric.readthedocs.io/en/latest/cc_launcher.html) - chaincode 外部编译器和启动器解决了 peer 组件在没有 docker 环境的环境下仍可对 chaincode 进行编译、运行和发现等操作的限制【英文】
* [chaincode 作为外部服务](https://hyperledger-fabric.readthedocs.io/en/latest/cc_service.html) - chaincode 外部编译器和启动器支持在 Fabric 网络节点外运行chaincode 智能合约的编译、部署和运行，这使得用户可以将chaincode智能合约能作为一种外部服务来进行使用和管理【英文】
* [chaincode 运维指南](https://hyperledger-fabric.readthedocs.io/en/latest/chaincode4noah.html#) - 从运维角度阐述如何进行 chaincode 智能合约的安装、更新部署以及版本升级【英文】

## 权限安全
* [使用硬件安全模块（HSM）](https://hyperledger-fabric.readthedocs.io/en/latest/hsm.html) - 介绍如何使用 HSM 来生成和储存节点使用的私钥【英文】
* [ACL访问控制列表](https://hyperledger-fabric.readthedocs.io/en/latest/access_control.html) - 详述如何通过ACL进行资源访问策略配置【英文】
* [基于身份混淆器（idmixer) 的MSP实现](https://hyperledger-fabric.readthedocs.io/en/latest/idemix.html) -  介绍了什么是身份混淆、如何使用身份混淆器以及如何将其与chaincode进行结合【英文】
* [身份混淆器（idmixer）MSP配置生成工具（idemixgen）](https://hyperledger-fabric.readthedocs.io/en/latest/idemixgen.html)- 介绍了用于生成基于身份混淆器(idmixer) MSP配置文件的 idemixgen 工具的使用方法【英文】
* [TLS 安全传输](https://hyperledger-fabric.readthedocs.io/en/latest/enable_tls.html) - Fabric 基于TLS(安全网络传输协议)的单向或双向验证能提高节点之间的通讯安全，这里详细介绍了如何为 peer、orderer、cli 组件配置 TLS 以及如何进行调试【英文】

## FabricCA
* [FabricCA 运维手册](https://hyperledger-fabric-ca.readthedocs.io/en/latest/operations_guide.html) - 如何使用 Fabric CA 组件搭建联盟组织的 CA 证书发布机构【英文】

## 共识出块
* [背书策略配置](https://hyperledger-fabric.readthedocs.io/en/latest/endorsement-policies.html) - 详细介绍了如何对共识出块所需的背书策略进行配置【英文】
* [可插拔化事务背书和验证机制](https://hyperledger-fabric.readthedocs.io/en/latest/pluggable_endorsement_and_validation.html) -  介绍如何自定制事务背书和验证规则插件【英文】
* [配置运行 Raft 排序服务](https://hyperledger-fabric.readthedocs.io/en/latest/raft_configuration.html) - 介绍了如何配置搭建一个基于 Raft 的 CFT（非拜占庭容错）共识排序服务【英文】
* [配置运行 Kafka 排序服务](https://hyperledger-fabric.readthedocs.io/en/latest/kafka.html) - 介绍了如何配置搭建一个基于 Kafka 的 BFT（拜占庭容错）共识排序服务【英文】
* [排序服务从 Kafka 迁移到 Raft](https://hyperledger-fabric.readthedocs.io/en/latest/kafka_raft_migration.html) - 介绍了如何将基于 Kafka 的排序服务迁移到 Raft 【英文】

## 运维监控
* [运维服务](https://hyperledger-fabric.readthedocs.io/en/latest/operations_service.html) - Fabric中的 orderer 和 peer 组件中提供了一个专门用于运维监控的 HTTP RESTful API 服务，这里详细介绍了运维服务的配置、日志管理、健康检查以及监控的指标【英文】
* [运维监控指标参考](https://hyperledger-fabric.readthedocs.io/en/latest/metrics_reference.html) - 详细描述了运维服务对 Prometheus 和 StatsD 工具提供的监控指标参数【英文】
* [日志控制 ](https://hyperledger-fabric.readthedocs.io/en/latest/logging-control.html)- 日志级别以及日志格式介绍【英文】

## 命令参考
* [常用命令参考](https://hyperledger-fabric.readthedocs.io/en/latest/command_ref.html) - cryptogen、configtx 和 peer 以及服务发现和 fabric ca 等工具命令参考手册

## 其他
* [如何进行版本升级](https://hyperledger-fabric.readthedocs.io/en/latest/upgrade.html) - 如何将 Fabric 程序升级到高版本【英文】

# 参考资料
## 开发语言
* [golang 官网](https://golang.org/) - fabric 底层开发语言，也可用于开发chaincode 智能合约等【英文】
* [nodejs 官网](https://nodejs.org/) - fabric 浏览器、caliper 等工具使用 nodejs 开发，也可用于开发chaincode 智能合约等【英文】
* [java 官网](https://www.java.com/en/) - 可用于开发chaincode 智能合约等【英文】
* [python 官网](https://www.python.org/) - cello BaaS 运维管理平台使用了 python 作为后端接口开发【英文】

## 开发框架
* [reactjs 官网 ](https://reactjs.org/)- fabric 浏览器、cello BaaS 运维管理平台等使用了 reactjs 作为前端框架 【英文】
* [django 官网](https://www.djangoproject.com/) - cello BaaS 运维管理平台使用 Django 框架开发 api-engine 模块 【英文】

## 第三方工具
* [docker 容器 ](https://www.docker.com/)- 可通过 docker 进行 fabric 网络快速搭建部署 【英文】
* [makefile](https://www.gnu.org/software/make/) - 用于自动化编译等目标生成操作 【英文】
* [shell 脚本](https://www.shellscript.sh/) - 提供大量实用工具函数等便捷操作 【英文】

# 其他

## 贡献<!-- omit in toc --> 
欢迎大家提供其他跟 Hyperledger Fabric 相关的资源
可以直接提交Pull Request  
也可以联系我:
* [共识区块链技术社区](https://zhuanlan.zhihu.com/consensusdev)  
![共识区块链技术社区](https://github.com/ConsensusDev/awsome-FISCO-BCOS/blob/master/files/ConsensusDev.jpg)
* 微信  
![Reed的WeChat](https://github.com/ConsensusDev/awsome-FISCO-BCOS/blob/master/files/reed.jpg)
