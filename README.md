# Caesar Benchmark

**Caesar Benchmark** is a lightweight CPU performance benchmark based on the classic Caesar cipher.

It uses a deliberately straightforward implementation: index shifting and alphabet-based substitution. Lowercase and
uppercase letters are handled separately, while non-alphabetic characters are left unchanged. This creates a pure
low-level workload consisting of linear memory access, arithmetic operations, and conditional branches.

**This is intentional.** Suggestions to replace the math with lookup tables or other optimizations will be rejected. The
goal is to stress-test the CPU and compiler on this specific pipeline, not to find the fastest possible Caesar cipher.

*Note: This is a synthetic mini-benchmark, not a comprehensive test suite. For full system evaluation, use professional
tools like Geekbench.*

## Implementations

This is a meta-repository that coordinates multiple implementations of the benchmark across different ecosystems:
* [**C++ Implementation**](https://github.com/01eksa/caesar-cpp) — ready ✔️
* **C# Implementation** — *Planned*
* **Python Implementation** — *Planned*

## Getting Started

To clone this repository along with all its submodules, use the `--recursive` flag:

```bash
git clone --recursive https://github.com/01eksa/caesar-benchmark.git
```
