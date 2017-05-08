
HFT++, part 1: putting the horse back in front of the cart
---
there are many cool tricks in high performance C++ and we will see some of them in these slides,
but my main goals today are to convince you to

1. measure: you need to *establish a baseline* before attempting to speed up everything in sight
2. think: once you understand what hardware does, most techniques are *common sense*
3. read: there are plentiful references once you know the right google search words

as a result, today not talking much about data structures (market data books and such)
but developing intuition and a base skill set for low latency C++ work

## a typical modern CPU
- super-scalar: a deeply pipelined interpreter of a **high-level language** called "x86 assembly"
    - u-ops
    - hardware can *theoretically* complete multiple asm instructions per cycle (IPC)
- out-of-order: speculative execution, TODO
- a
- b
- c
- d
- e

sadfasdfasdfa

