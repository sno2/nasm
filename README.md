# nasm

This is [nasm](https://www.nasm.us/), packaged for [Zig](https://ziglang.org/).
Both the nasm and ndisasm binaries are provided.

## Panics

[Zig's ubsan runtime](https://ziglang.org/download/0.14.0/release-notes.html#UBSan-Runtime)
has found quite a few instances of UB in the nasm source code. Here are two
open PRs that would solve some of the issues:

- https://github.com/netwide-assembler/nasm/pull/63
- https://github.com/netwide-assembler/nasm/pull/76
