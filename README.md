# cls-bwt

**cls-bwt** is an implementation of the **BWT (Burrows–Wheeler Transform)** for **FreeArc**.

This is **not a standalone compressor**. It is a preprocessing filter that can improve compression ratio by rearranging data to create more repetitive patterns.  
Effectiveness depends on the input data.

Based on **libsais v2.10.4**:  
https://github.com/IlyaGrebnov/libsais

---

## Options

| Parameter | Description |
|------------|------------|
| `b=<block_size>` | Block size (default: `16mb`) |
| `m=<mode>` | BWT mode: `bwt`, `bwt16` |

**Note**

Parameters can be specified without the `=` separator.

---

## Memory Requirements

Requires: 5 × block_size

---

## Support the Project

[![Support on Patreon](https://c5.patreon.com/external/logo/become_a_patron_button.png)](https://www.patreon.com/Shegorat)

If you find this project useful, consider supporting development on Patreon.
