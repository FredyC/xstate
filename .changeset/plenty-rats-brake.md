---
'xstate': patch
---

[TS] Make withContext to accept partial shape object

Internally, context is expected it can be partial. This change only allows the same from the TypeScript side.
The same applies to `withConfig`.
