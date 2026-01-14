# tsgo-lsp

A Claude Code plugin providing TypeScript/JavaScript language server support using Microsoft's native Go-based TypeScript compiler (tsgo), delivering ~10x faster type checking and code intelligence.

![tsgo-lsp in Claude Code plugin marketplace](Claude%20Code%20Plugin%20tsgo-lsp.png)

## Quick Install

```bash
# Add marketplace
/plugin marketplace add ClayWarren/tsgo-lsp

# Install plugin
/plugin install tsgo-lsp
```

**Prerequisite:** Install the tsgo binary first:
```bash
npm install -g @typescript/native-preview
```

## Why tsgo?

TypeScript 7's native compiler (tsgo) offers:
- **10x faster** type checking compared to traditional TypeScript
- **Lower memory usage** than the JavaScript-based implementation
- **Standard LSP protocol** for reliable editor integration
- **Near-complete parity** with TypeScript 6.x type checking

## Supported Files

`.ts`, `.tsx`, `.js`, `.jsx`, `.mts`, `.cts`, `.mjs`, `.cjs`

## LSP Features

- Go to Definition
- Find References
- Hover documentation
- Diagnostics (type errors)
- Auto-completions

## Resources

- [TypeScript Native Previews](https://devblogs.microsoft.com/typescript/announcing-typescript-native-previews/)
- [@typescript/native-preview on npm](https://www.npmjs.com/package/@typescript/native-preview)

## License

MIT
