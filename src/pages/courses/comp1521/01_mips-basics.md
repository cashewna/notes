---
title: "MIPS Basics"
pubDate: 2024-02-12
description: "Introduction to MIPS Assembly Programming"
author: "Krishna Khong"
image:
    url: "https://docs.astro.build/assets/full-logo-light.png"
    alt: "The full Astro logo."
tags: ["comp1521", "24T1", "computer systems fundamentals", "unit 1"]
---
# MIPS Basics

## Architecture
MIPS is a well-known and simple architecture
- historically used everywhere from supercomputers to game consoles
- still popular in some embedded fields e.g. modems/routers, TVs
- but being out-competed by ARM and more recently, RISC-V

## Emulators
- [mipsy](https://github.com/insou22/mipsy) - command-line based emulator written by Zac
- [mipsy-web](https://cgi.cse.unsw.edu.au/~cs1521/mipsy/) - web (WASM) GUI-based version of mipsy written by Shrey

## MIPS
- load and store - transfer data between registers and memory
- computational - perform arithmetic/logical operations
- jump and branch - transfer control of program execution
- coprocessor - standard interface to various co-processors
    - coprocessors implement floating-point operations
- special - miscellaneous tasks (e.g. syscall)