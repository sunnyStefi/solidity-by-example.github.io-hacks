---
title: Bypass Contract Size Check
version: 0.8.20
description: An example of bypassing contract size check
keywords: [hack, security, bypass, contract, size, check, extcodesize]
---

### Vulnerability

If an address is a contract then the size of code stored at the address will be greater than 0 right?

Let's see how we can create a contract with code size returned by `extcodesize` equal to 0.

```solidity
{{{ContractSize}}}
```
