
<!-- TOC -->

- [1. `geth`命令帮助](#1-geth命令帮助)
- [2. VERSION:](#2-version)
- [3. USAGE:](#3-usage)
- [4. cmd释义](#4-cmd释义)
    - [4.1. `COMMANDS`--主命令](#41-commands--主命令)
    - [4.2. `ETHEREUM OPTIONS`--以太坊选项](#42-ethereum-options--以太坊选项)
    - [4.3. `LIGHT CLIENT OPTIONS`--轻客户端选项](#43-light-client-options--轻客户端选项)
    - [4.4. `DEVELOPER CHAIN OPTIONS`--开发者链选项](#44-developer-chain-options--开发者链选项)
    - [4.5. `TRANSACTION POOL OPTIONS`--交易池选项](#45-transaction-pool-options--交易池选项)
    - [4.6. `PERFORMANCE TUNING OPTIONS`--性能调整选项](#46-performance-tuning-options--性能调整选项)
    - [4.7. `ACCOUNT OPTIONS`--帐户选项](#47-account-options--帐户选项)
    - [4.8. `API AND CONSOLE OPTIONS`--API和控制台选项](#48-api-and-console-options--api和控制台选项)
    - [4.9. `NETWORKING OPTIONS`--网络选项选项](#49-networking-options--网络选项选项)
    - [4.10. `MINER OPTIONS`--矿工选项](#410-miner-options--矿工选项)
    - [4.11. `GAS PRICE ORACLE OPTIONS`--`GAS`价格预言机选项](#411-gas-price-oracle-options--gas价格预言机选项)
    - [4.12. `VIRTUAL MACHINE OPTIONS`--虚拟机选项](#412-virtual-machine-options--虚拟机选项)
    - [4.13. `LOGGING AND DEBUGGING OPTIONS`--记录和调试选项](#413-logging-and-debugging-options--记录和调试选项)
    - [4.14. `METRICS AND STATS OPTIONS`--指标及统计选项](#414-metrics-and-stats-options--指标及统计选项)
    - [4.15. `WHISPER (deprecated)`--Whisper--<font color=red size=3>Deprecated</font>](#415-whisper-deprecated--whisper--font-colorred-size3deprecatedfont)
    - [4.16. `ALIASED (deprecated)`--别名选项--<font color=red size=3>Deprecated</font>](#416-aliased-deprecated--别名选项--font-colorred-size3deprecatedfont)
    - [4.17. `MISC OPTIONS`--杂项](#417-misc-options--杂项)
- [5. COPYRIGHT:](#5-copyright)

<!-- /TOC -->
# 1. `geth`命令帮助
```
geth --help
```

# 2. VERSION:
`1.11.21-unstable`
   
# 3. USAGE:
`geth [options] command [command options] [arguments...]`

# 4. cmd释义
## 4.1. `COMMANDS`--主命令
|COMMANDS:|msg_cn|msg|
|:--|:--|--:|
|`account`|账户管理|Manage accounts|
|`attach`|启动交互式 JavaScript 环境（连接到节点）|Start an interactive JavaScript environment (connect to node)|
|`console`|启动交互式 JavaScript 环境|Start an interactive JavaScript environment|
|`copydb`|从目标链数据文件夹创建本地链|Create a local chain from a target chaindata folder|
|`dump`|从存储中转储特定块|Dump a specific block from storage|
|`dumpconfig`|显示配置值|Show configuration values|
|`dumpgenesis`|将创世块 JSON 配置转储到标准输出|Dumps genesis block JSON configuration to stdout|
|`export`|将区块链导出到文件中|Export blockchain into file|
|`export-preimages`|将原像数据库导出到 RLP 流中|Export the preimage database into an RLP stream|
|`import`|导入区块链文件|Import a blockchain file|
|`import-preimages`|从 RLP 流导入原像数据库|Import the preimage database from an RLP stream|
|`init`|引导并初始化一个新的创世块|Bootstrap and initialize a new genesis block|
|`inspect`|检查数据库中每种数据类型的存储大小|Inspect the storage size for each type of data in the database|
|`js`|执行指定的JavaScript文件|Execute the specified JavaScript files|
|`license`|显示许可证信息|Manage accounts|
|`makecache`|生成 ethash 验证缓存（用于测试）|Generate ethash verification cache (for testing)|
|`makedag`|生成 ethash 挖掘 DAG（用于测试）|Generate ethash mining DAG (for testing)|
|`removedb`|删除区块链和状态数据库|Remove blockchain and state databases|
|`show-deprecated-flags`|显示已弃用的标志|Show flags that have been deprecated|
|`version`|打印版本号|Print version numbers|
|`version-check`|检查（在线）当前版本是否存在任何已知的安全漏洞|Checks (online) whether the current version suffers from any known security vulnerabilities|
|`wallet`|Manage Ethereum presale wallets|管理以太坊预售钱包|
|`help, h`|显示命令列表或一个命令的帮助|Shows a list of commands or help for one command|

## 4.2. `ETHEREUM OPTIONS`--以太坊选项
|ETHEREUM OPTIONS:|msg_cn|msg|
|:--|:--|--:|
||||

## 4.3. `LIGHT CLIENT OPTIONS`--轻客户端选项
|LIGHT CLIENT CMD:|msg_cn|msg|
|:--|:--|--:|
||||

## 4.4. `DEVELOPER CHAIN OPTIONS`--开发者链选项
|DEVELOPER CHAIN OPTIONS:|msg_cn|msg|
|:--|:--|--:|
||||

## 4.5. `TRANSACTION POOL OPTIONS`--交易池选项
|TRANSACTION POOL OPTIONS:|msg_cn|msg|
|:--|:--|--:|
||||

## 4.6. `PERFORMANCE TUNING OPTIONS`--性能调整选项
|PERFORMANCE TUNING OPTIONS:|msg_cn|msg|
|:--|:--|--:|
||||

## 4.7. `ACCOUNT OPTIONS`--帐户选项
|ACCOUNT OPTIONS:|msg_cn|msg|
|:--|:--|--:|
||||

## 4.8. `API AND CONSOLE OPTIONS`--API和控制台选项
|API AND CONSOLE OPTIONS:|msg_cn|msg|
|:--|:--|--:|
||||

## 4.9. `NETWORKING OPTIONS`--网络选项选项
|NETWORKING OPTIONS:|msg_cn|msg|
|:--|:--|--:|
||||

## 4.10. `MINER OPTIONS`--矿工选项
|MINER OPTIONS:|msg_cn|msg|
|:--|:--|--:|
||||

## 4.11. `GAS PRICE ORACLE OPTIONS`--`GAS`价格预言机选项
|GAS PRICE ORACLE OPTIONS:|msg_cn|msg|
|:--|:--|--:|
||||

## 4.12. `VIRTUAL MACHINE OPTIONS`--虚拟机选项
|VIRTUAL MACHINE OPTIONS:|msg_cn|msg|
|:--|:--|--:|
||||

## 4.13. `LOGGING AND DEBUGGING OPTIONS`--记录和调试选项
|LOGGING AND DEBUGGING OPTIONS:|msg_cn|msg|
|:--|:--|--:|
||||

## 4.14. `METRICS AND STATS OPTIONS`--指标及统计选项
|METRICS AND STATS OPTIONS:|msg_cn|msg|
|:--|:--|--:|
||||

## 4.15. `WHISPER (deprecated)`--Whisper--<font color=red size=3>Deprecated</font>
|METRICS AND STATS OPTIONS:|msg_cn|msg|
|:--|:--|--:|
||||

## 4.16. `ALIASED (deprecated)`--别名选项--<font color=red size=3>Deprecated</font>
|ALIASED (deprecated) OPTIONS:|msg_cn|msg|
|:--|:--|--:|
||||

## 4.17. `MISC OPTIONS`--杂项
|MISC OPTIONS:|msg_cn|msg|
|:--|:--|--:|
||||

# 5. COPYRIGHT:
`Copyright 2013-2020 The core-geth and go-ethereum Authors`