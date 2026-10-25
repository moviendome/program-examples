# Counter: Anchor

The Anchor version has its own `initialize_counter` instruction: the `init` constraint creates
the account, which the native and Pinocchio versions leave to the client. See the
[Counter README](../README.md) for how the program works and how the three versions differ.

## Build and test

```shell
pnpm install
anchor test
```
