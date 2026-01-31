# Pokémon Red and Blue [![Build Status][ci-badge]][ci]

This is a _forked_ disassembly of Pokémon Red and Blue.

It builds the following ROMs:

- Pokemon Red (UE) [S][!].gb `sha1: ea9bcae617fdf159b045185467ae58b2e4a48b9a`
- Pokemon Blue (UE) [S][!].gb `sha1: d7037c83e1ae5b39bde3c30787637ba1d4c48ce2`
- BLUEMONS.GB (debug build) `sha1: 5b1456177671b79b263c614ea0e7cc9ac542e9c4`

To set up the repository, see [**INSTALL.md**](INSTALL.md).

<br/>

## Main differences compared to regular pokered

• Virtual Console patches for this fork are considered <ins>redundant</ins>  
due to how the main implementation for this project works.  
  
• Once finished, it will serve as an option for any Nintendo Power cart  
or a flashcart supporting at least 512 KiB ROM size and 32 KiB RAM size.

• RAM can be either SRAM (requires a battery) or FRAM (requires nothing).  
  
• SRAM/FRAM expansion is not yet supported, and is also not the main scope  
of this particular project for reasons that aren't able to be specified.

<br/>

## See also

These are not mine:

- [**Wiki**][wiki] (includes [tutorials][tutorials])
- [**Symbols**][symbols]
- [**Tools**][tools]

<br/>

You can find pret on [Discord (pret, #pokered)](https://discord.gg/d5dubZ3).

For other pret projects, see [pret.github.io](https://pret.github.io/).

[wiki]: https://github.com/pret/pokered/wiki
[tutorials]: https://github.com/pret/pokered/wiki/Tutorials
[symbols]: https://github.com/pret/pokered/tree/symbols
[tools]: https://github.com/pret/gb-asm-tools
[ci]: https://github.com/pret/pokered/actions
[ci-badge]: https://github.com/pret/pokered/actions/workflows/main.yml/badge.svg
