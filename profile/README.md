# Datumesh

Datumesh gives every number a name you can call and a signed receipt you can check.

```text
datumesh.com/relay/ecb.europa.eu/fx_reference(USD, 2026-11-20)
```

answers `1.099`: the ECB's euro reference rate for the US dollar on 20 November 2026, with a receipt signed by `datumesh.com#eddd0c12fedb022e`. The web address of the same cell is
<https://datumesh.com/cell/datumesh.com/relay/ecb.europa.eu/fx_reference(USD,2026-11-20)>.

**Start at [datumesh.com/docs](https://datumesh.com/docs/)**: get data six ways, calculate on your machine, connect an agent. Every series has month pages: [datumesh.com/series](https://datumesh.com/series/).

| Repository | What it is |
|---|---|
| [datumesh-spec](https://github.com/datumesh-com/datumesh-spec) | The protocol specification, schemas and test vectors |
| [datumesh](https://github.com/datumesh-com/datumesh) | The `datumesh` command: a local resolver, calc and an MCP server for agents |
| [datumesh-verify-py](https://github.com/datumesh-com/datumesh-verify-py) | Receipt verifier for Python (`pip install datumesh`) |
| [datumesh-verify-js](https://github.com/datumesh-com/datumesh-verify-js) | Receipt verifier for JavaScript (`npm install @datumesh/verify`) |
| [datumesh-http](https://github.com/datumesh-com/datumesh-http) | The mesh over HTTPS: the server behind datumesh.com |
| [datumesh-local](https://github.com/datumesh-com/datumesh-local) | The local resolver library behind the `datumesh` command |
| [datumesh-core](https://github.com/datumesh-com/datumesh-core), [-store](https://github.com/datumesh-com/datumesh-store), [-engine](https://github.com/datumesh-com/datumesh-engine), [-formula](https://github.com/datumesh-com/datumesh-formula) | The Rust crates underneath |
