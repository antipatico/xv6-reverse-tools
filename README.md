# xv6 Reverse Tools
This repositories provides some basic tools for Reverse Engineering for the xv6
operating system, such as an 8086 disassembler, an ELF32 analyzer and an ELF32
disassembler.

The software is provided as a patch for xv6, as such you must copy this folder
into your xv6-public folder and recompile the whole project.

Versioning is provided from the original version of modified files of xv6.

The version of xv6 is the latest as today: 6.828.

The disassembler is based on [btbd's
disassembler](https://github.com/btbd/disassembler) and as such this project is
released under the Apache-2.0 license.

The ELF32 analyzer is written from scratch thanks to many online resources
\[1\]\[2\]\[3\].

# Author

antipatico

# References

1. [The 101 of ELF files on Linux: Understanding and
Analysis](https://linux-audit.com/elf-binaries-on-linux-understanding-and-analysis/)- Linux Audit
2. [Executable and Linkable Format (ELF)](https://stevens.netmeister.org/631/elf.html) - charngda
3. Executable and Linkable Format (ELF) - Tool Interface Standards (TIS)
