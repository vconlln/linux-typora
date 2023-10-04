# NodeInject

more nodeinject information: [NodeInject](https://github.com/DiamondHunters/NodeInject)

# Example
### Typora Crack
1. inject
```shell
cargo build --bin node-inject --release
mv target/release/node-inject /usr/share/typora
cd /usr/share/typora
sudo ./node-inject
```
2. generator a license
```shell
cargo run --bin license-gen --release
```
3. open typora and input your license.
