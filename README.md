# evokerr-kernels

Split into one repository per root manager, so each has its own release list:

| | builds |
|---|---|
| [evokerr-resukisu](https://github.com/evoker0/evokerr-resukisu) | ReSukiSU + SUSFS |
| [evokerr-sukisu](https://github.com/evoker0/evokerr-sukisu) | SukiSU-Ultra + SUSFS + KPM |
| [evokerr-ksunext](https://github.com/evoker0/evokerr-ksunext) | KernelSU-Next + SUSFS |

Each covers the seven GKI KMIs from android12-5.10 to android16-6.12 and rebuilds when
Google publishes a new monthly branch or the root manager ships a new tag.

Pick the file whose KMI matches `uname -r` on your device. A kernel built for a different
KMI generation will not boot.

This repository is kept only so older links still resolve. Nothing is built here.