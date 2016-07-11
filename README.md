**This project is abandoned.** I've been thoroughly convinced that this is
a problem being solved well by existing systems, notably the `s6` process
supervision suite of programs.

This repository will continue to stay up for archival purposes.

# `beginning-scripts`, scripts for the Beginning init system

A repository containing daemon scripts for the [Beginning] init system.

**Beginning is still a work-in-progress.** If you use the scripts
located here, they should be updated in lockstep with Beginning.

## Requirements
- bash
- [Beginning]

## Installation
Before installing, install [Beginning] or these will be of no use.

1. `git clone https://github.com/somasis/beginning-scripts`, or [download a release]

2. `make`

    The makefile follows GNU Makefile standards, and can be influenced by variables
    such as `DESTDIR`, `bindir`, `libdir`, `libexecdir`,`docdir`, `sysconfdir`,
    and `prefix`. Variables for directories are changed in the source files.

    The top of the Makefile contains a full list of variables.

    In order for these scripts to work correctly, you must pass the same variables
    that were passed to Beginning's makefile.

3.  `make install`

[Beginning]:            https://github.com/somasis/beginning
[download a release]:   https://github.com/somasis/beginning-scripts/releases/latest
