# Hi, I'm Nikolai

I write C++ with a latency budget: lock-free queues, cache-friendly data layouts,
and profiling sessions that end in hardware counters rather than guesses.

Daytime it's game engines and infrastructure; evenings drift toward compilers,
distributed filesystems and trading systems — mostly as upstream patches:

- [llvm/llvm-project](https://github.com/llvm/llvm-project/pulls?q=is%3Apr+author%3Anfedotenko) — clang frontend, C++26 odds and ends
- [XTXMarkets/ternfs](https://github.com/XTXMarkets/ternfs/pulls?q=is%3Apr+author%3Anfedotenko) — hardening an exabyte-scale filesystem: a kmod patch and three [security findings](https://github.com/XTXMarkets/ternfs/issues?q=is%3Aissue+author%3Anfedotenko), a kernel OOB write among them
- [lrvx/lrvx](https://github.com/lrvx/lrvx/pulls?q=is%3Apr+author%3Anfedotenko) — batching, order tracking and market-data plumbing

My own experiments live in the pins below.

Strong opinions, loosely held: the fastest syscall is the one you never make,
the only lock-free algorithm with zero bugs is a single-threaded one,
and he who never segfaulted never shipped anything.
