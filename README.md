# KMM - Kit Mod Manager
In a vigilant effort to always make things harder than they need to be, I've decided to make my own mod manager. It uses [fuse-overlayfs](https://github.com/containers/fuse-overlayfs) to accomplish it.
I wanted to make this in Rust but I'm not smart enough to understand the FUSE and OverlayFS libraries.

# Usage

```sh
kmm path/to/mods path/to/game
```

