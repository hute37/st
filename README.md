# custom build of st - the simple (suckless) terminal

| branch   | status |
|----------|--------|
| main     | [![CI.Build](https://github.com/hute37/st/workflows/CI-Build/badge.svg?branch=main)](https://github.com/hute37/st/actions?query=workflow%3ACI-Build) |
| stable   | [![CI.Build](https://github.com/hute37/st/workflows/CI-Build/badge.svg?branch=stable)](https://github.com/hute37/st/actions?query=workflow%3ACI-Build) |
| testing  | [![CI.Build](https://github.com/hute37/st/workflows/CI-Build/badge.svg?branch=testing)](https://github.com/hute37/st/actions?query=workflow%3ACI-Build) |
| unstable | [![CI.Build](https://github.com/hute37/st/workflows/CI-Build/badge.svg?branch=unstable)](https://github.com/hute37/st/actions?query=workflow%3ACI-Build) |


_Patched fork of The ["suckless terminal (st)"](https://st.suckless.org/)_

## Upstream

  * initial base from [st (version 0.8.4)](https://git.suckless.org/st/refs.html)
  * based on Julius Hülsmann's st fork :  https://github.com/juliusHuelsmann/st
  
  * my archived repo [st.ex](https://github.com/hute37/st.ex) with no working X-PRIMARY selection
  
### References

  * [Julius Hülsmann's README.md](https://github.com/juliusHuelsmann/st)
  

## Patches

### included in base


  * [patch releases (no-alpha)](https://github.com/juliusHuelsmann/st/releases)
  
  - "alpha" patches requires composite extension, unavailable on x2go remote boxes.



### todo (included in "st.ex")

- newterm
- font2
- visualbell
- w3m
- netwmicon
- colors-at-launch
- nordtheme
- xresources

- 

- scrollback
- scrollback-mouse
- scrollback-mouse-altscreen
- scrollback-mouse-increment


## Custom

### fonts

| Config       | Font |
|--------------|------|
| config       | "Fantasque Sans Mono:pixelsize=22:antialias=true:autohint=true;" |
| xresources   | "Iosevka Nerd Font:pixelsize=18:antialias=true:autohint=true;" |
| config.font2 | "Hack:pixelsize=14:antialias=true:autohint=true;" |



## Credits

- [juliusHuelsmann/st](https://github.com/juliusHuelsmann/st)
- [LukeSmithxyz/st](https://github.com/LukeSmithxyz/st)
- [gnotclub/xst](https://github.com/gnotclub/xst)

