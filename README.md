# College Subjects

A central hub for my college subjects and laboratory work. Each subject keeps its own repository and laboratories.

The four subject entries are Git submodules, each pinned to a specific commit. They do not update automatically when the original repositories change. Each subject's README links to its laboratory branches.

| Subject | Repository contents |
| --- | --- |
| [Microcontrollers](https://github.com/Paraschiv-Stefan/Microcontrollers) | Applications and homework using an ESP32 LoRa board. |
| [Applied Informatics](https://github.com/Paraschiv-Stefan/Applied-Informatics) | Proteus projects with PIC16LF1937 / PIC16F1937 and website code. |
| [Object-Oriented Programming](https://github.com/Paraschiv-Stefan/Object-Oriented-Programming) | Object-oriented programming laboratories. |
| [Information Theory](https://github.com/Paraschiv-Stefan/Information-Theory) | Information theory laboratories. |

## Clone with submodules

```sh
git clone --recurse-submodules https://github.com/Paraschiv-Stefan/College-Subjects.git
```

For an existing clone:

```sh
git submodule update --init --recursive
```
