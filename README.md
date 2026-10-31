# Hi, I'm Nikolai

I write C++ with a latency budget: lock-free queues, cache-friendly data layouts,
and profiling sessions that end in hardware counters rather than guesses.

Daytime it's game engines and infrastructure; evenings drift toward compilers,
distributed filesystems and trading systems — mostly as upstream patches:

- [llvm/llvm-project](https://github.com/llvm/llvm-project/pulls?q=is%3Apr+author%3Anfedotenko) ![merged](https://img.shields.io/github/issues-search?query=repo%3Allvm%2Fllvm-project%20is%3Apr%20is%3Amerged%20author%3Anfedotenko&label=merged&color=2ea44f) — clang frontend, C++26 odds and ends
- [XTXMarkets/ternfs](https://github.com/XTXMarkets/ternfs/pulls?q=is%3Apr+author%3Anfedotenko) ![merged](https://img.shields.io/github/issues-search?query=repo%3AXTXMarkets%2Fternfs%20is%3Apr%20is%3Amerged%20author%3Anfedotenko&label=merged&color=2ea44f) — hardening an exabyte-scale filesystem: a kmod patch and three [security findings](https://github.com/XTXMarkets/ternfs/issues?q=is%3Aissue+author%3Anfedotenko), a kernel OOB write among them
- [lrvx/lrvx](https://github.com/lrvx/lrvx/pulls?q=is%3Apr+author%3Anfedotenko) ![merged](https://img.shields.io/github/issues-search?query=repo%3Alrvx%2Flrvx%20is%3Apr%20is%3Amerged%20author%3Anfedotenko&label=merged&color=2ea44f) — batching, order tracking and market-data plumbing

Currently building [steroids](https://github.com/nfedotenko/steroids) in public —
low-latency C++ building blocks (SPSC rings, allocators, hot/cold layout), one
benchmarked primitive at a time; [steroidslog](https://github.com/nfedotenko/steroidslog)
is the family's logger. The rest of my experiments live in the pins below.

Strong opinions, loosely held: the fastest syscall is the one you never make,
the only lock-free algorithm with zero bugs is a single-threaded one,
and he who never segfaulted never shipped anything.
