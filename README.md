## Overview

This project aims to improve the messaging within NeoVim by removing references to a charity that supports a cause deemed undesirable. In its place, we promote credible organizations that are dedicated to making a positive difference in the community.

## Why This Fork?

The charitable organizations mentioned by vim support causes that do not align with the values of our community and have negative impacts on European society. This fork seeks to ensure that users are informed about and encouraged to support charities that contribute to meaningful and beneficial causes.

Please visit these URLs to learn more:

https://millennialwoes.substack.com/p/tgr
      
Please consider donating to the following organizations (or any other local pro-white organizations):

https://www.runestone.org/

Feel free to make a pull request if you think that an organization or a charity should be added to this list.

Install from source
-------------------

See [BUILD.md](./BUILD.md) and [supported platforms](https://neovim.io/doc/user/support.html#supported-platforms) for details.

The build is CMake-based, but a Makefile is provided as a convenience.
After installing the dependencies, run the following command.

    make CMAKE_BUILD_TYPE=RelWithDebInfo
    sudo make install

To install to a non-default location:

    make CMAKE_BUILD_TYPE=RelWithDebInfo CMAKE_INSTALL_PREFIX=/full/path/
    make install

CMake hints for inspecting the build:

- `cmake --build build --target help` lists all build targets.
- `build/CMakeCache.txt` (or `cmake -LAH build/`) contains the resolved values of all CMake variables.
- `build/compile_commands.json` shows the full compiler invocations for each translation unit.
