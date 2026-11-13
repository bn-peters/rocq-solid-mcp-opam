# rocq-solid-mcp-opam

An opam repository for [RocqSolid](https://github.com/bn-peters/rocq-solid-mcp),
an MCP server for Rocq proof development.

It contains `rocq-solid-mcp-lsp`, a patched
[rocq-lsp](https://github.com/rocq-community/rocq-lsp) (source:
[bn-peters/rocq-lsp](https://github.com/bn-peters/rocq-lsp), branches
`rocq-solid-9.x`) for Rocq 9.0, 9.1, and 9.2. It installs the usual
`coq-lsp` binary and libraries, so it replaces (and conflicts with) `coq-lsp`.

```bash
opam repo add rocq-solid https://github.com/bn-peters/rocq-solid-mcp-opam.git
opam install rocq-solid-mcp-lsp
```

The packages `bens-rocq-lsp.*` are the same patch set under its old name and
are kept for existing installations.
