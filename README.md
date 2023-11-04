# saourlabs 开发者指南

本指南用指导新进入 saourlabs 的开发者，让开发者可以根据自己的兴趣参与相应项目的开发，主要包括项目介绍和如何参与项目的开发

## 1. saourlabs 项目介绍

- [wallet-chain-node](https://github.com/savour-labs/wallet-chain-node):一个对接各公链的一个节点 RPC 服务, 统一一套钱包接口服务，目前已经支持 BTC, ETH, ADA, Arbi, OP, Scroll, Zksync, Tron, Tezos, Oasis, Cosmos 等 40 多条主流链。
- [key-locker](https://github.com/savour-labs/key-locker): 一个链上密钥管理工具，可以用于社交恢复钱包和 MPC 钱包的去中心化密钥管理。
- [skyeye](https://github.com/savour-labs/skyeye): 数字货币行情聚合器，目前已经支持所有主流的中心化交易所，去中心化交易所也在支持中
- [fieryeyes](https://github.com/savour-labs/fieryeyes): NFT 聚合器项目，目前已经暂停开发
- [hailstone](https://github.com/savour-labs/hailstone): 业务中台项目，对接各个后端 rpc 服务，如 [wallet-chain-node](https://github.com/savour-labs/wallet-chain-node), [skyeye](https://github.com/savour-labs/skyeye) 等项目
- [protect-x-contracts](https://github.com/savour-labs/protect-x-contracts): layer3 隐私社交协议链的经济模型，逆向重新质押协议合约
- [wallet-sdk](https://github.com/savour-labs/wallet-sdk): Hd 钱包 SDK, 助记词生成，离线助词导出私钥生成地址，交易离线签名，目前已经支持 BTC, ETH, ADA, Arbi, OP, Scroll, Zksync, Tron, Tezos, Oasis, Cosmos 等 40 多条主流链。
- [shadow-x-app](https://github.com/savour-labs/parapack): 一个 RN 开发的隐私社交钱包，目前已经对接完 7 条主流链，集成 DAPP 浏览器，闪兑和行情等功能。
- [bitcoin-sdk-lite](https://github.com/savour-labs/bitcoin-sdk-lite): 轻量级的 BTC 钱包 SDK
- [savour-treasure](https://github.com/savour-labs/savour-treasure): savour 社区任务管理加金库合约
- [savour-proto](https://github.com/savour-labs/savour-proto): 所有项目的 protobuf 接口定义
- [savour-secret](https://github.com/savour-labs/savour-secret): nodeJS 实现的门限共享秘密算法库
- [universe-uni](https://github.com/savour-labs/universe-uni): uni-app 开发的隐私社交钱包，目前已经暂停开发
- [savour-prototype](https://github.com/savour-labs/savour-prototype): 产品原型设计稿
- [savnode](https://github.com/savour-labs/savnode): layer3 Mpc 节点，目前暂停开发，等 layer3 隐私社交协议开发会重新启动
- [distribute](https://github.com/savour-labs/distribute): IOS app 发布的分发平台(企业签模式的那种，不能上架 app store, 企业签或超级签完成之后可以使用这个分发平台)。
- [savour-offical](https://github.com/savour-labs/savour-offical): savourlabs 官网，目前暂停运营
- [shadow-x](https://github.com/savour-labs/shadow-x): layer3 隐私社交协议项目，后续会改名为 protect-x
- [protect-x-sdk](https://github.com/savour-labs/protect-x-sdk): 马上就会启动开发的 layer3 隐私社交协议 sdk, 供第三方接入时使用

  
## 2. 开发指南

每个项目下面会有对应的 issure, issure 如果被标记为 task 的就是需要开发的任务，对应的 task 下面也会有开发赏金，任务开发完成之后提交 PR, 如果 PR 有问题，会有改进评论，开发者需要根据改进评论进行 fix, 如果 PR 被合并了就说明该任务已完成，开发就会获得对应任务的赏金。


## 3. 如何贡献

### 3.1.组织内的开发者

- 第一步：克隆代码，切换到 develop 分支
- 第二步：基于 develop 分支切开发分支
- 第三步：根据任务 spec 开发任务
- 第四步：提交代码到开发分支并提PR
- 第五步：Savourlabs 技术负责人 Review 代码，若 PR 有问题，根据评论改进
- 第六步：合并 PR，发放任务奖励


### 3.2.非组织内的开发者

- 第一步：fork 代码到自己的 github 下
- 第二步：基于自己 github 下 repo 切分支开发
- 第三步：根据任务 spec 开发任务
- 第四步：提交代码到自己 github 下的 repo 并提 PR 到 savourlabs 项目
- 第五步：Savourlabs 技术负责人 Review 代码，若 PR 有问题，根据评论改进
- 第六步：合并 PR，发放任务奖励


