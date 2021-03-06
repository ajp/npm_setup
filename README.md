# NPM Setup

[![Patreon](https://img.shields.io/badge/patreon-donate-brightgreen.svg)](https://www.patreon.com/bkuhlmann)

Shell scripts for the installation of commonly used NPM packages.

Sometimes, when setting up a new machine, there is a need for automating the install of commonly
used packages (i.e. setting up your toolbox). This solves that problem by providing a master list of
commonly used packages which can be installed via a single command.

<!-- Tocer[start]: Auto-generated, don't remove. -->

# Table of Contents

- [Features](#features)
- [Requirements](#requirements)
- [Setup](#setup)
- [Usage](#usage)
- [Versioning](#versioning)
- [Code of Conduct](#code-of-conduct)
- [Contributions](#contributions)
- [License](#license)
- [History](#history)
- [Credits](#credits)

<!-- Tocer[finish]: Auto-generated, don't remove. -->

# Features

Installs the following packages (only if not already installed):

- Development
    - [Failing Code](https://www.npmjs.org/package/failing-code)
    - [Node Offline Debug](https://github.com/HPSoftware/node-offline-debug)
    - [JSCS](http://jscs.info)
    - [Elm Oracle](https://github.com/ElmCast/elm-oracle)
- Graphics
    - [imacss](https://github.com/akoenig/imacss)
    - [SVGO](https://github.com/svg/svgo)
    - [TMI](https://github.com/addyosmani/tmi)
- Assets
    - [Grunt](http://gruntjs.com)
    - [Broccoli](https://github.com/joliss/broccoli)
    - [UnCSS](https://github.com/giakki/uncss)
- Testing
    - [pageres](https://github.com/sindresorhus/pageres)
- Metrics
    - [WOPR](https://github.com/yaronn/wopr)
- Utilities
    - [hget](https://github.com/bevacqua/hget)

# Requirements

- [macOS](https://github.com/bkuhlmann/mac_os)

# Setup

Open a terminal window and execute one of the following depending on your version preference:

Current Version (stable):

    git clone https://github.com/bkuhlmann/npm_setup.git
    cd npm_setup
    git checkout v2.0.0

Master Version (unstable):

    git clone https://github.com/bkuhlmann/npm_setup.git
    cd npm_setup

# Usage

Edit the `settings/packages.txt` as you see fit. Blank lines and lines that begin with '#' will be
ignored. Then open a terminal window to execute the following command:

    bin/run

Running the script will present the following options:

    i: Install packages.
    q: Quit/Exit.

Choose option 'i' to install.

The options prompt can be skipped by passing the desired option directly to the `bin/run` script.
For example, executing "bin/run i" will execute the install.

# Versioning

Read [Semantic Versioning](http://semver.org) for details. Briefly, it means:

- Patch (x.y.Z) - Incremented for small, backwards compatible, bug fixes.
- Minor (x.Y.z) - Incremented for new, backwards compatible, public API enhancements/fixes.
- Major (X.y.z) - Incremented for any backwards incompatible public API changes.

# Code of Conduct

Please note that this project is released with a [CODE OF CONDUCT](CODE_OF_CONDUCT.md). By
participating in this project you agree to abide by its terms.

# Contributions

Read [CONTRIBUTING](CONTRIBUTING.md) for details.

# License

Copyright (c) 2014 [Alchemists](https://www.alchemists.io).
Read [LICENSE](LICENSE.md) for details.

# History

Read [CHANGES](CHANGES.md) for details.
Built with [Bashsmith](https://github.com/bkuhlmann/bashsmith).

# Credits

Developed by [Brooke Kuhlmann](https://www.alchemists.io) at
[Alchemists](https://www.alchemists.io).
