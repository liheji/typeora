## About

#### Dependency

```sh
sudo apt install golang
```

#### Usage

**Build node_inject**

```sh
cd NodeInject
cargo build
# result in target/debug/node_inject
```

**Build license-gen**

```sh
license-gen
cargo build
# result in target/debug/license-gen
```

**Copy  node_inject and license-gen in typora installation directory**

```sh
./node_inject
./license-gen
```
