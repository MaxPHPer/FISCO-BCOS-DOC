
# 前言

商业，本身是一种竞争、自由的经济活动。而自由竞争的结果，天然就容易导致优胜劣汰、垄断集中、甚至寻租。尤其是2008年全球金融危机发生后，“大而不倒Too Big to Fail”的弊病显现，也因此引发了一系列的技术变革与商业变革，启动了一轮从“集中式”走向“分布式”的时代浪潮。

在这个背景下，区块链技术在2008年萌芽成型，并逐渐发展成熟。通过区块链技术解决方案中的共识机制、分布式账本、加密算法、智能合约、点对点通信、分布式计算架构、分布式存储、隐私保护算法、跨链协议等技术模块，可以让商业模式中的参与各方实现了地位对等和互信合作，从而推动了从“信息互联网”到“信任互联网”的时代进步，也令商业模式全面走向“分布式”成为可能。

新型的“分布式商业”模式，按微众银行整理给出的定义，是一种由多个具有对等地位的商业利益共同体所建立的新型生产关系，是通过预设的透明规则进行组织管理、职能分工、价值交换、共同提供商品与服务并分享收益的新型经济活动行为。在主要表现特征上，分布式商业显现出多方参与、共享资源、智能协同、价值整合、模式透明、跨越国界等特点。一个成熟的分布式商业场景具备生产资料由多方持有、产品和服务能力由多方共同构建、商业过程中的相互关系对等，产品和利益分配规则透明等要求。

分布式商业与此前流行的连锁加盟型商业模式及共享商业模式的最大不同之处在于，起到中间链接桥梁作用的不是人或产品、不是信息平台、而只有客观的技术本身。诚然，如果技术不开源，确实也可能演变成新的垄断。因此，发展分布式商业必须始终保持技术开源的态度，各个参与方通过开源社区进行分工合作，就将不再存在话语权集中和垄断的可能性，弱肉强食的“丛林法则”在此就不复存在。这有助于中小微企业真正成为商业价值链的主角，从而激发经济增长动力、广泛提升就业、鼓励创业和创新，实现“反垄断”的人类商业终极理想。

发展开源区块链技术的深远意义已不言而喻，但技术路线的选择也至关重要。虽然最原始的区块链技术起源于虚拟货币及公有链项目，但公有链的项目方往往以融资为目的，其用户则是以价格交易获利为目标，导致各方更多是关注币价的涨跌而非区块链的真正应用能力。由于公有链的代币实质上是“类货币”与“类证券”，已经被中国的监管部门严厉叫停。当潮水退去、大浪淘沙后，联盟链技术已肩负起推动区块链技术继续前行的重任。2018年，业界更是提出“公众联盟链”的发展路线，呼吁联盟链应该积极开放开源，从较为封闭的联盟内或公司内走向大众，让普罗大众真正感受到区块链带来的体验提升、效率提升、成本下降、信任增强、数据互换、责任追溯等好处，实现分布式商业的愿景。

新一代的公众联盟链，对于区块链底层技术提出了新的要求，除了标准的区块链特性之外，还有几个方面仍需要重点加强：首先，由于公众联盟链并不是单一链条，所以需要具备支持多链并行以及跨链通信的技术，同时需能够支撑来自互联网海量交易请求的能力。其次，需要具备快速、低成本地组建联盟和建链的能力，便于各个需求方能够高效建立联盟链网络，让企业间建链合作变得像现在建立“聊天群”一样高效便捷。最后，需要开源和开放，实现联盟成员之间的充分信任。公众联盟链不仅有利于降低企业快速试错的成本，有效提升商业上的容错性，也促进商业社会朝着可信化、透明化的方向深化发展，全面降低合作的操作风险、道德风险、信用风险、信息保护风险等。秉持以上的目标与愿景，我们正式发布了基于“公众联盟链”技术路线的FISCO BCOS 2.0版本。


# FISCO BCOS
FISCO BCOS平台是金融区块链合作联盟（深圳）（以下简称：金链盟）开源工作组以金融业务实践为参考样本，在BCOS开源平台基础上进行模块升级与功能重塑，深度定制的安全可控、适用于金融行业且完全开源的区块链底层平台。金链盟开源工作组的首批成员包括以下单位：微众银行、深证通、腾讯、华为、神州数码、四方精创、博彦科技、越秀金科、亦笔科技等9家单位。


### FISCO BCOS 1.0
FISCO BCOS致力于达到性能、安全、可用性与合规的平衡。

在性能方面，FISCO BCOS 在整体架构和交易处理等方面都进行了大量的优化，包括采用了高效的共识算法，把能并行的计算并行化，减少重复计算，对关键计算单元进行升级等。更进一步地，其性能的核心突破点不仅仅在于单链，更在于基于单链性能优化架构设计，并实现灵活、高效、可靠、安全的并行计算和可平行扩展的能力。这帮助开发者能够灵活地根据自己业务场景的实际需要，通过简单增加机器，达到自己需要的性能。总体上，FISCO BCOS平台优化了网络通信模型，采用拜占庭容错共识机制，结合多链架构和跨链交互方案，可解决并发访问和热点帐户的性能痛点，从而满足金融级高频交易场景需求。

在安全性方面，FISCO BCOS 平台通过节点准入控制、可靠的密钥管理、灵活的权限控制，在应用、存储、网络、主机层实现全面的安全保障。在隐私保护的设计上，支持权限管理、物理隔离，支持国密算法（国家密码局认证的标准算法），同时也对外开源了包括同态加密、零知识证明、群签名、环签名等多种隐私保护算法的实现方案。

在可用性方面，FISCO BCOS设计为7×24小时运行，达到金融级高可用性。在监管支持方面，可支持监管和审计机构作为观察节点加入，获取实时数据进行监管审计。此外，还提供了各种开发接口，方便开发者编写和调用智能合约。

### FISCO BCOS 2.0
FISCO BCOS 2.0版本在原有基础上进行架构升级和优化，在可扩展性、性能、易用性等方面前进了一大步。

实现**群组架构**，在多个节点组成的一个全局网络中，可以存在多个节点子集组成的子网络，这些子网络维护一个独立的账本。这些账本之间的共识、存储都是相互独立的，具备良好的扩展性和安全性。在群组架构中，可以更好地实现平行扩展，满足金融级高频交易场景的需求。同时，群组架构可以快速支持组链需求，极大降低运维难度，真正能够实现企业间建链就像建“聊天群”一样简便。

支持**分布式存储**，使存储突破单机限制，支持横向扩展。计算和存储分离，提高了系统健壮性，即使节点执行服务器故障，数据也不会受影响。分布式存储定义了标准的数据访问CRUD接口，可以适配多种存储系统，同时支持SQL和NoSQL两种数据管理方式，可以更简便地支持多种业务场景。

实现**预编译合约框架**，突破EVM性能瓶颈。支持交易并发处理，大幅提升交易处理吞吐量。预编译合约采用C++实现，内置于底层系统中，区块链自动识别调用合约的交易互斥信息，构建DAG依赖，规划出一个高效的并行交易执行路径。最佳情况下，性能提升可达到CPU核心数的倍数。

另外，FISCO BCOS 2.0版本持续在网络传输模型、计算存储流程等方面进行优化，对性能提升提供巨大帮助。在架构方面，在存储、网络、计算三个角度，围绕高可用性和高易用性进行持续升级。基于模块化、分层、可插拔等设计原则，持续对核心模块进行重塑升级，保证系统健壮性。

更多2.0的特性将在后续章节深入展开介绍。

# 总结

实践之中出真知，FISCO BCOS经过了外部多家机构、多个应用，长时间在生产环境运行的实际检验，是一个稳定、高效、安全的区块链底层平台。

为了让大家更好地了解FISCO BCOS 2.0区块链开源平台，本文档将按照Step By Step的步骤详细介绍了FISCO BCOS 2.0版本的构建、安装、启动，智能合约部署、调用等用法，以及详细介绍FISCO BCOS 2.0整体架构和各模块的设计方案。
