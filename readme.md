# Usage

## Install rust
`curl https://sh.rustup.rs -sSf | sh`
test with `cargo --version`

## Get libra code
`git clone https://github.com/libra/libra.git && cd libra`
`./scripts/dev_setup.sh`
`./scripts/cli/start_cli_testnet.sh`

### Create two account
`account create`
`account create`
### Show account list
`account list`
### Mint for first account
`account mint 0 100`
### Show first account balance
`query balance 0`
### Transfer from 0 to 1 account
`transfer 0 1 10`
### Show transaction
`query txn_acc_seq 0 0 false`
