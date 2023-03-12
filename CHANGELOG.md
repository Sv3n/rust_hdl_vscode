# Changelog
## [0.4.1] - 2023-03-12

- Updated README

## [0.4.0] - 2023-01-03

- Change embedded language server for Linux from gnu to musl

## [0.3.2] - 2020-10-04

- Fix automatic server update

## [0.3.1] - 2020-04-05

- Fix client crashing when opening file without workspace

## [0.3.0] - 2020-01-26

- Added automatic updates of language server
- Added `entarch` snipped for Entity + Architecture

## [0.2.0] - 2019-12-30

- Embedded `vhdl_ls` updated to version 0.12.0.
- Standard and IEEE packages are now integrated by the `vhdl_ls` language server.  
**NOTE**: These libraries should be removed from any global `vhdl_ls.toml` files.

## [0.1.0] - 2019-12-21

- Standard and IEEE packages are now installed to extension global directory.
- Updated language server
  - Goto defintion.
  - Find references.
  - `vhdl_ls.toml` now redifines library files instead of appending them.

## [0.0.4] - 2019-12-05

- Added standard and IEEE libraries.
- If no `.vhdl_ls.toml` is found in HOME, a standard configuration with std and IEEE is created.

## [0.0.3] - 2019-12-03

- VHDL files are now opened with `ISO 8859-1` encoding.

## [0.0.2] - 2019-12-03

- Added `vhdlls.restart` command to restart the language server.

## [0.0.1] - 2019-12-02

Embedded Language Server version: [4206fee8c4322542b386299c557fbd7d610a5cb6](https://github.com/kraigher/rust_hdl)

First release.
