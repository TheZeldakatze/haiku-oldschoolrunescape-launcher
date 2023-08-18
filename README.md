# oldschool Runescape Launcher script for Haiku

This is a simple launcher script for launching oldschool Runescape on Haiku.
It contains a workaround that makes the game close when you quit it,
so it actually closes the program itself instead of freezing.

It is based on [https://gitlab.com/coringao/runescape](https://gitlab.com/coringao/runescape)

## Requirements
`pkgman install openjdk11-jre 7z`

## Installing
````
chmod +x Runescape\ Launcher
rc -o runescapeLogo.rsrc runescapeLogo.rdef
resattr -o ./Runescape\ Launcher runescapeLogo.rsrc
````

## License
Copyright (c) 2023, Maite Gamper <mail@maiteswelt.de>

This script is based on https://gitlab.com/coringao/runescape/ 
which is (C) 2020 Carlos Donizete Froes, Licensed under 2-Clause-BSD

Runescape is Copyright (c) 1999-2020, Jagex Ltd.
This script is not in any way affiliated with Jagex Ltd. or Runescape.
