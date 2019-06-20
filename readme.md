# Usage

## install rust
`curl https://sh.rustup.rs -sSf | sh`
test with `cargo --version`

## get libra code
`git clone https://github.com/libra/libra.git && cd libra`
`./scripts/dev_setup.sh`
`./scripts/cli/start_cli_testnet.sh`

### 创建两个账户
`account create`
`account create`
### 查看账户
`account list`
### 给第一个账户挖矿
`account mint 0 100`
### 查看账户
`query balance 0`
### 转账
`transfer 0 1 10`
### 查看交易
`query txn_acc_seq 0 0 false`
