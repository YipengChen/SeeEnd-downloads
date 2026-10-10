# SeeEnd downloads and policies

Publisher: Yipeng Chen · Contact: ypchenmail@gmail.com

[Desktop downloads](https://github.com/YipengChen/SeeEnd-downloads/releases/tag/v0.8.5) · [Privacy policy](https://yipengchen.github.io/SeeEnd-downloads/) · [Review setup](TESTING.md)

SeeEnd original implementation is proprietary from version 0.8.4 onward. The original source repository remains private. This repository contains public policies, installation instructions, licensing notices and binary downloads only; it does not contain SeeEnd original source code.

The downloadable package includes licenses and matching third-party source materials, also offered as a separate release asset. Those third-party materials retain their respective licenses.

The current SeeEnd 0.8.5 package compiles 22 core modules to native machine code and excludes their Python bytecode. This raises the cost of recovering core logic; it does not prevent reverse engineering. The desktop interface, integration adapters and bundled JavaScript remain outside this compilation scope.

SHA-256 for the current native build:

| Download | SHA-256 |
| --- | --- |
| `SeeEnd-0.8.5-Darwin-arm64.zip` | `a20f70bcc5bfb7f32d90a87be66974bd04c421fe05692a93ada04fc20fd6e603` |
| `SeeEnd-third-party-sources-0.8.5.zip` | `7db94013b497111ea6d175214c540f74b30233e649554976f5ed6ae667d023bf` |

[SeeEnd license](LICENSE) · [Third-party notices](THIRD_PARTY_NOTICES.md) · [Library replacement](LIBRARY_REPLACEMENT.md)

The current review build supports macOS Apple Silicon. It is ad-hoc signed and not Apple-notarized. No Windows or Intel Mac build is provided in this release.
