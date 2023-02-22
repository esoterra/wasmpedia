[Modules]: ./module/index.md
[Components]: ./component/index.md
[Guest]: ./guest.md

# Host

A host is something that can run [Guest](./guest.md) [Modules] and [Components].

Most hosts are based on "runtimes" that may internally
* Ahead-of-time (AOT) compile to the native format
* Act as an interpreter of Wasm instructions
* Perform Just-in-time (JIT) compilation

Some host runtimes use a combination of these approaches.