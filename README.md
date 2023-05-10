## dependencies

* [foundry and forge](https://github.com/foundry-rs/foundry)

## setup

* run dev-cluster https://github.com/astriaorg/dev-cluster

## deploy contracts

* Weth9 contract
```bash
# deploy Weth9 contract first
export PRIV_KEY=123...
RUST_LOG=debug forge create --private-key $PRIV_KEY src/Weth9.sol:WETH9
```
