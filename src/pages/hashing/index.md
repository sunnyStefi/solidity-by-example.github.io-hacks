---
title: Hashing with Keccak256
version: 0.8.20
description: Example of hashing using Keccak256 in Solidity
keywords: [hash, hashing, function, functions, keccak256, cryptography]
---

`keccak256` computes the Keccak-256 hash of the input.

Some use cases are:

- Creating a deterministic unique ID from a input
- Commit-Reveal scheme
- Compact cryptographic signature (by signing the hash instead of a larger input)

```solidity
{{{Keccak256}}}
```
