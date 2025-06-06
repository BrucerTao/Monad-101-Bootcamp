1. 简单描述一下本地开发、部署合约的流程

- 环境搭建:安装 solidity 编译器、安装 node.js、安装 npm、安装 metamask 插件、安装 web3.js 库
- ​ 编写合约代码 ​​：使用 ​​Solidity​​ 编写合约
- 编译与测试 ​​：通过框架编译合约生成字节码和 ABI，编写单元测试（如使用 Hardhat 的测试脚本），在本地测试网络（如 Ganache）部署并调试合约
- 部署到区块链 ​​：将合约部署到区块链上，需要使用区块链钱包（如 Metamask）导入私钥，并将合约 ABI 和字节码上传到区块链上

2. 简单描述一下用户在使用一个 DApp 时与合约交互的流程

- 连接钱包：用户通过浏览器插件（如 MetaMask、WalletConnect）或 DApp 内置钱包授权登录
- 发起交互请求 ​：用户在 DApp 内输入合约地址、方法名、参数等信息，并点击“调用”按钮发起请求
- 等待结果 ​：DApp 监听区块链上合约执行结果
- 解析结果 ​：DApp 解析区块链上合约执行结果，并根据业务需求展示给用户

3. 通读「区块链黑暗森林自救手册」，列出你觉得最重要的三个安全技巧

- 零信任:简单来说就是保持怀疑，而且是始终保持怀疑，小心任何未知来源的文件
- 大资产使用冷钱包或多签钱包保护关键资产
- 开发用主机、服务器需要正规防护软件，注意防范黑客攻击
- 签名交易时，检查交易的内容
