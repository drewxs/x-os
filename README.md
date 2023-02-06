# Kernl

Minimal rust kernel.

## Prerequisites

```bash
cargo install bootimage
rustup component add llvm-tools-preview
```

## Development

```bash
# create bootable disk image
cargo bootimage
```
