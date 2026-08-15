[中文](README.zh.md) | [English](README.md)

---

# **Unofficial** Flatpak repo of [HMCL](https://github.com/HMCL-dev/HMCL)
Automatically built daily to stay up-to-date!
NOT OFFICIAL MINECRAFT PRODUCT. NOT APPROVED BY OR ASSOCIATED WITH MOJANG.
This repo is also not supported by HMCL developers. If you encountered any problem please try to reproduce it in official HMCL.

## How to install

[Click here to install](https://heipiao233.github.io/hmcl-flatpak/install_zh_CN.html).

If nothing happens, maybe your system does not support `flatpak+https` urls. Please download the [.flatpakref file](https://github.com/heipiao233/hmcl-flatpak/raw/refs/heads/main/net.huangyuhui.hmcl.flatpakref) file, then run it from your file manager.

### In command line
```bash
flatpak install https://github.com/heipiao233/hmcl-flatpak/raw/refs/heads/main/net.huangyuhui.hmcl.flatpakref
```

## Older JDKs
Install corresponding OpenJDK 8/17/21 Flatpak, them could be detected.
```
flatpak install org.freedesktop.Sdk.Extension.openjdk{8,17,21}
```
