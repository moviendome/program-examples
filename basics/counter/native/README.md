# Counter: Solana Native

This example program is written in Solana using only the Solana toolsuite.

## Build and test

```shell
pnpm build-and-test
```

This builds the program with `cargo build-sbf` and runs the tests in
[LiteSVM](https://github.com/LiteSVM/litesvm), in-process, with no local validator. See the
[Counter README](../README.md) for how the program works.

## Deploy

```shell
pnpm build
pnpm deploy
```
