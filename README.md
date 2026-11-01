# Moonside EarthBound Music Editor

Moonside EarthBound Music Editor is a fork of **EBMusEd**, a ROM hacking tool for editing and playing back *EarthBound*'s N-SPC music sequence data.

The aim is to retain the original editor's functionality while improving its interface, playback accuracy, and ease of use. Moonside is intended for both longtime EBMusEd users and people who are just getting started with *EarthBound* music hacking.

## What's different?

- **Piano roll:** A visual way to inspect and edit notes alongside the existing sequence editor, without replacing the original workflow. Reminiscent of FL Studio's piano roll.
- **Echo emulation:** Implement playback of the SNES DSP echo effects so songs can be previewed more faithfully in the editor.
- **Easier to learn:** Reduce the learning curve with clearer controls, more approachable editing tools, and better presentation of N-SPC commands.
- **Improved command editing:** More convenient editing of sequence opcodes, including contextual controls for command parameters.
- **64-bit port:** Makes it smoother in some hardware.
- **Cross-platform support (planned):** Planned Linux and macOS release (At last!)

## Using MoonMusEd

Like the original EBMusEd, Moonside works with *EarthBound* ROM data. You will need to supply your own ROM; no game ROMs or copyrighted game assets are distributed with this project.

For an introduction to music editing, see the [EBMusEd tutorials on the CoilSnake Wiki](https://github.com/pk-hack/CoilSnake/wiki/EBMusEd). The original editor's **Help → Code list** is also a useful reference for sequence commands.

The existing sequence-editing workflow remains an important part of Moonside. New visual editing features are intended to complement it, not require experienced users to relearn everything.


### Linux and macOS

Native support is **planned**. Build instructions will be added once the relevant ports are usable. Windows binaries should not be assumed to run natively on either platform.
I'm trying to port it to GTK for Linux at this moment.

## Background

EBMusEd was originally written by **Goplat**, who shared its source code with the community on the starmen.net PK Hack forum. The project was subsequently maintained and improved by community contributors through [PKHackers/ebmused](https://github.com/PKHackers/ebmused).

I made this version for myself as I work a lot and often find myself taking too long to make a single song in time I do NOT have and wished I could just work like I do in FL Studio.
But I decided it was too good to keep to myself so I want to contribute back by publishing it.

I hope this makes life a bit easier to the veterans and newcomers alike.


## Why Moonside?

I feel like my personal branch looks sketchy so I named it after something also sketchy from the game, I also don't wish to make it part of the original EBMusEd as it feels profane

Wel come to Moo nsi ns dem oons ide

## Building with Visual Studio Code in Windows

- Have MinGW installed.
- Open the `/ebmused` directory in VS Code and press CTRL+Shift+B.
- The executable will be build to `/build/release/ebmused.exe`


## License

This project is based on EBMusEd, which is distributed under the MIT License. See [LICENSE](LICENSE) for the applicable license terms and copyright notices.
