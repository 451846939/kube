# kube-derive
Add `#[derive(CustomResource)]` to your custom resource struct.

## Installation
Add the `derive` feature to `kube`:

```toml
[dependencies]
kube = { version = "0.45.0", feature = ["derive"] }
```

## Usage
See the **[kube-derive API Docs](https://docs.rs/kube-derive/)**

## Examples
See the `crd_` prefixed [examples](../examples) for more.

## Development
Help very welcome! Kubebuilder like features, testing improvement, openapi feature. See https://github.com/clux/kube-rs/labels/derive