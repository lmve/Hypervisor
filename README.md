# Hypervisor

I'm learning about hypersior, which is an implementation of type 1 hypersior for x86 architectures.

## Install Tools
Install [cargo-binutils](https://github.com/rust-embedded/cargo-binutils)
```
cargo install cargo-binutils
```

## Run

```
cd hypervisor
make run [LOG=warn|info|debug|trace]
```