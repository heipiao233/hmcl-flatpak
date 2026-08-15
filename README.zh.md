[中文](README.zh.md) | [English](README.md)

---

# [HMCL](https://github.com/HMCL-dev/HMCL) **非官方** Flatpak 仓库
每天自动构建，保持最新版本！
本仓库非 Minecraft 官方产品。未获 Mojang 许可，亦与 Mojang 无任何关联。
本仓库也并非 HMCL 官方支持。使用此处下载的 HMCL，如有任何问题，请先尝试在官方版 HMCL 中复现。

## 如何安装

[点击此处安装](https://heipiao233.github.io/hmcl-flatpak/install_zh_CN.html)。

如果没有任何反应，有可能您的系统不支持 `flatpak+https` 链接。请下载 [.flatpakref](https://github.com/heipiao233/hmcl-flatpak/raw/refs/heads/main/net.huangyuhui.hmcl.flatpakref) 文件，然后在您的文件管理器中运行该文件。

### 使用命令行
````bash
flatpak install https://github.com/heipiao233/hmcl-flatpak/raw/refs/heads/main/net.huangyuhui.hmcl.flatpakref
````

## 旧版本 JDK
直接安装 OpenJDK 8/17/21 的对应 Flatpak 包，它们会被检测到。
```
flatpak install org.freedesktop.Sdk.Extension.openjdk{8,17,21}
```
