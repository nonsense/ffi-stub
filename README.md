# Filecoin FFI stub

_For testing and non-production purposes only._

This is an FFI stub that can be used with a go.mod `replace` directive
in tests that do not require real proofs.

## Usage

In your go.mod:

```
replace github.com/filecoin-project/filecoin-ffi => github.com/filecoin-project/ffi-stub v0.1.0
```

## License

Dual-licensed: [MIT](./LICENSE-MIT), [Apache Software License v2](./LICENSE-APACHE), by way of the
[Permissive License Stack](https://protocol.ai/blog/announcing-the-permissive-license-stack/).
