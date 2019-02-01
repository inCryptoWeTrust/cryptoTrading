# cryptoTradingSystem

用py做一些交易

----------------
## 1. [交易环境 trading environment](notebook/1_trading_environment.ipynb)
- ### 申请开通海外服务器
  开通 aws、google cloud、aliyun 等云服务器厂商的实例，并安装 ubuntu/linux 系统，介绍常见操作及`tmux`
- ### `python` 环境
  使用 `miniconda` 配置 python 环境，并安装 `ccxt` 交易所`api`库 和 `numpy` 等高效计算库
  （可能还需要安装 `gcc`）    
  使用 `jupyterLab` 进行远程调试
  使用 `azure notebook` 进程尝试
  

- ### `node·js` 环境
  使用 `nvm` 配置 `node·javascript` 环境，并安装 ccxt

- ### ToDo
  docker 环境    
  包含 redis、rabbitMQ、tensorflow、及 java与交易相关的各种依赖

-------------
## 2. 交易数据
- ### 获取实时数据
  使用 `ccxt` 获取交易所实时数据进行交易   
  （ticker、depth、trade、order、balance）

- ### 获取历史数据
  收集各种历史数据，保存并进行回测
  - 用`ccxt`获取交易所详细的历史数据
  - 获取更多历史数据的其它途径
  - 区块链历史数据

- ### ToDo
  利用 `websocket` 获取数据    
  由于各家交易所 `websocket` 接口不同，较为麻烦，等找到较好的相关的库后再介绍）


------------
## 3. 交易策略


------------
## 4. 交易回测


------------
## 5. 交易监控

- ### 数据监控与可视化（账户余额）

- ### 实时数据可用性监控


