# DFX deleting candid file in Rust project

```shell
dfx start --background
```

```shell
dfx canister create --all
```

```shell
dfx generate
```

To workaround the issue, add `"did"` to the `rust.declarations.bindings` array in `dfx.json`.
