# Ember Tokenizer

A high-performance, from-scratch tokenizer library built to explore and optimize Byte Pair Encoding (BPE) and related subword methods—implemented in both Python (for clarity) and C++ (for speed).

This project is designed as both a learning resource and a performance benchmark, intended for developers and researchers who want to understand tokenization at a deep technical level.

---

## Features

- Naive BPE implementation in Python for educational purposes
- Optimized C++ tokenizer focused on speed and memory efficiency
- Benchmarking suite for comparison with industry tools (e.g., Hugging Face)
- Modular, extensible structure for future additions (WordPiece, SentencePiece, etc.)

---

## Folder Overview

- `python/`: Simple BPE implementation + demo notebook  
- `cpp/`: High-performance C++ implementation  
- `benchmarks/`: Tools for profiling and comparing tokenizer speed/memory  
- `data/`: Sample corpora for testing  
- `diagrams/`: Visuals used in the accompanying video/tutorial  
- `docs/`: Guides and writeups

---

## Getting Started

### Requirements

**Python**
- Python 3.8+
- `numpy`, `matplotlib` (optional for demos)

**C++**
- C++17 or later
- CMake (recommended for building)
- Google Benchmark (optional, for benchmarking)


Work in progress!
