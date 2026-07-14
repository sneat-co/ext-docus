# ext-docus

Public contract for the Sneat Docus extension.

`frontend/` is the sole owner and publisher of
`@sneat/extension-docus-contract`. The private
[`docus`](../docus) repository consumes this package and owns Docus's runtime,
UI, and host application code.

## Layout

```text
typespec/   # frozen wire contract
backend/    # contract-facing Go definitions and checks
frontend/   # @sneat/extension-docus-contract workspace
```
