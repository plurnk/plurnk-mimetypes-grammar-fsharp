# @plurnk/plurnk-mimetypes-grammar-fsharp

Pre-built `tree-sitter-fsharp` WASM grammar for the [@plurnk/plurnk-mimetypes](https://github.com/plurnk/plurnk-mimetypes) framework.

## install

```
npm i @plurnk/plurnk-mimetypes-grammar-fsharp
```

## what's in here

- **`fsharp.wasm`** — pre-built from the pinned upstream [tree-sitter-fsharp](https://github.com/ionide/tree-sitter-fsharp) commit (`fsharp` subdirectory) (SHA in `.grammar-pin`)
- `scripts/build-wasm.mjs` — reproducible rebuild from the pinned source
- `scripts/verify-wasm.mjs` — CI byte-identical reproducibility check

Declares only `web-tree-sitter` as a peer — no native `tree-sitter`, no node-gyp.

## license

MIT. The bundled `fsharp.wasm` is built from the upstream tree-sitter-fsharp grammar; see the pinned commit for that project's attribution.
