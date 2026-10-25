# Counter: Solana Pinocchio

This example program is written with [Pinocchio](https://github.com/anza-xyz/pinocchio): it reads
and writes the account's bytes directly, with no serialization library. See the
[Counter README](../README.md) for how the program works.

## Build and test

```shell
pnpm build-and-test
```

This builds the program with `cargo build-sbf` and runs the tests in
[LiteSVM](https://github.com/LiteSVM/litesvm), in-process, with no local validator.

## Deploy

```shell
pnpm build
pnpm deploy
```
