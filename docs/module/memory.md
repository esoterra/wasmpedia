[Modules]: ./index.md
[import]: ./import.md
[exported]: ./export.md
[memory instructions]: ./instructions.md#memory
[zero-indexed]: https://en.wikipedia.org/wiki/Zero-based_numbering

# Memory (Module)

Wasm [Modules] can access "linear memories" that they define or [import].

This is done through [memory instructions] which are able to

* Determine the size of the memory in pages,
* Attempt to grow the memory by some amount,
* and load from or store into the memory.

Memories are defined with a minimum number of pages they need and optionally a maximum number of pages they will ever need.

## Exporting Memory

Memories can also be [exported] which assigns them an external name.

[Modules] can be linked together so that module A's export is connected to module B's import.
This enables two modules to share a memory.

Alternatively, the memory can be exported and used by the host.
