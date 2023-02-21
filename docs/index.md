[Module]: ./module/index.md
[Imports]: ./module/import.md
[Exports]: ./module/export.md
[data]: ./module/data.md
[functions]: ./module/function.md

[ISA]: https://en.wikipedia.org/wiki/Instruction_set_architecture

# Wasmpedia
An Open Source encyclopedia for WebAssembly (Wasm)

## What is Wasm?
WebAssembly, or "wasm", is a general-purpose virtual [ISA] designed to be a compilation target for a wide variety of programming languages. Much of its distinct personality derives from its security, code compression, and decoding optimization features.

The unit of WebAssembly code is the [Module]. Modules consist of a header followed by a sequence of sections. There are sections describing a WebAssembly's interactions with other modules ([Imports] and [Exports]), sections declaring [data] and other implements used by the module, and sections defining [functions].

## What content goes here?
For now, we'll only host content about Wasm 2.0 to get started.

In the future, we may add content about Wasm proposals and ecosystem tools.
