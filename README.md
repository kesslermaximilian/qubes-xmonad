# Overview

This repository is a fork of
[xmonad](https://www.github.com/xmonad/xmonad) and contains patches to
provide better integration with [QubesOS](https://www.qubes-os.org/).

The origin fork of this was [dschoepe/qubes-xmonad](https://github.com/dschoepe/qubes-xmonad).
This is an attempt to update this fork to the current xmonad master.

# Changes

- Window border colors are determined by the `qubesColors` field
  in the `XConfig` structure. The default colors can be overwritten
  by changing this field in the xmonad configuration file.
