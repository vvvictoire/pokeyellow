# Pokémon Yellow H4XX [![Build Status][ci-badge]][ci]

This is an edit of Pokémon Yellow, made possible by [pret]’s [pokeyellow] disassembly.

## Goal of the hack

1. Modify some sprites, thus
1. Modifying some palettes
1. Making it possible to catch the 151 pokémons
1. Modifying some strings
1. Putting some QoL (to define)

## Palettes

They’re in `data/sgb/sgb_palettes.asm`

It builds the following ROMs:

- pokeyellow.gbc
- YELLMONS.GB (debug build) ???
- Dmgapse0.h08.patch `sha1: f3346a5559d52c296b8feab0cdbbfb0e250ac161`

To set up the repository, see [**INSTALL.md**](INSTALL.md).


## See also

- [**Wiki**][wiki] (includes [tutorials][tutorials])
- [**Symbols**][symbols]
- **Discord:** [pret][discord]
- **IRC:** [libera#pret][irc]

Other disassembly projects:

- [**Pokémon Red/Blue**][pokered]
- [**Pokémon Gold/Silver**][pokegold]
- [**Pokémon Crystal**][pokecrystal]
- [**Pokémon Pinball**][pokepinball]
- [**Pokémon TCG**][poketcg]
- [**Pokémon Ruby**][pokeruby]
- [**Pokémon FireRed**][pokefirered]
- [**Pokémon Emerald**][pokeemerald]

[pret]: https://github.com/pret/
[pokeyellow]: https://github.com/pret/pokeyellow
[pokered]: https://github.com/pret/pokered
[pokegold]: https://github.com/pret/pokegold
[pokecrystal]: https://github.com/pret/pokecrystal
[pokepinball]: https://github.com/pret/pokepinball
[poketcg]: https://github.com/pret/poketcg
[pokeruby]: https://github.com/pret/pokeruby
[pokefirered]: https://github.com/pret/pokefirered
[pokeemerald]: https://github.com/pret/pokeemerald
[wiki]: https://github.com/pret/pokeyellow/wiki
[tutorials]: https://github.com/pret/pokeyellow/wiki/Tutorials
[symbols]: https://github.com/pret/pokeyellow/tree/symbols
[discord]: https://discord.gg/d5dubZ3
[irc]: https://web.libera.chat/?#pret
[ci]: https://github.com/vvvictoire/pokeyellow/actions
[ci-badge]: https://github.com/vvvictoire/pokeyellow/actions/workflows/main.yml/badge.svg
