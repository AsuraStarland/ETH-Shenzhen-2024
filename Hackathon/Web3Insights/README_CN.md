# Web3Insights

> 一个专注于 Web3 生态系统、社区、仓库和开发者的综合指标平台

## 项目赛道

Open-Source Tools/Infrastructure

## Bounty 赛道

BGA

## 项目概述

虽然 Web3 生态系统与传统开源社区有相似之处，但标准的指标系统往往无法为 Web3 项目提供全面的理解、趋势跟踪和项目评估。Web3Insights 旨在通过为 Web3 项目的独特景观提供定制的分析和洞察来弥补这一差距。

像 OpenBuild 这样的社区在高效评估其 Bootcamp 等项目的活跃贡献者和参与者时很困难，手动统计管理耗时较长，即使使用像 OSS Insight 这样的工具，获取单个开发者的详细表现指标成本较高。这些生态系统中的奖励分配也缺乏标准化。

## 核心功能

1. **生态系统分析**：搜索和分析特定 Web3 生态系统或社区内的活跃项目和贡献者，呈现全面的指标数据。

2. **项目特定洞察**：通过项目名称直接搜索指标数据，并结合使用 GPT-4 生成的 AI 驱动分析报告。

3. **开发者画像**：使用 GitHub 用户名或 Web3 钱包地址搜索和汇编开源贡献数据和链上生态系统参与指标。

4. **定制指标系统**：将专有指标框架与 Web3 生态系统数据库相结合，为不同生态系统提供定制的分析维度。

5. **身份关联**：持续构建一个可靠的数据库，关联 Web3 空间内的 GitHub 用户、电子邮件地址和钱包地址。

6. **奖励分发平台**：
   - 直接向作为平台用户的贡献者分发奖励
   - 为非平台用户生成智能合约 Bounties/Grants，允许他们认领奖励
   - 用户数据库匹配和电子邮件通知，通过 GitHub 用户名进行身份验证

## 技术栈

- 前端：Remix.js 与 TypeScript
- 后端：Node.js
- 数据库：PostgreSQL 用于关系数据，Redis 用于缓存
- 用户认证：Clerk 用于安全的用户管理
- 区块链集成：viem 用于基于以太坊的交互
- AI 集成：OpenAI API 用于 GPT-4o 分析
- API：OpenDigger、OSS Insight、RSS3 DSL API 用于灵活的数据查询

## 路线图

1. 2024.08 - ETHShenzhen 黑客松
   1. MVP 上线，包含用户系统、基本搜索和分析功能
   2. 集成 AI 驱动的分析报告
   3. 使用 Starknet 和 OpenBuild 作为初始测试生态系统/社区
2. 2024 年第三季度
   1. 实施奖励分配系统
   2. 推出高级的生态系统特定指标和分析工具
   3. 更多功能即将推出

## 项目团队

- [pseudoyu](https://github.com/pseudoyu)

## 项目链接

| 项目 | 链接 |
| --- | --- |
| 在线演示 | [web3insights.app](https://web3insights.app) |

## 联系方式

- 电子邮件：[pseudoyu@connect.hku.hk](mailto:pseudoyu@connect.hku.hk)
