[HMCL](https://github.com/HMCL-dev/HMCL) **非官方** Flatpak 仓库。
每天自动构建，保持最新版本！
本仓库非 Minecraft 官方产品。未获 Mojang 许可，亦与 Mojang 无任何关联。
本仓库也并非 HMCL 官方支持。使用此处下载的 HMCL，如有任何问题，请先尝试在官方版 HMCL 中复现。

## 如何安装

如果你的桌面有应用商店，尝试导入 https://github.com/heipiao233/hmcl-flatpak/raw/refs/heads/main/hmcl-flatpak.flatpakrepo
一些应用商店（包括 GNOME Software 和 Plasma 的 Discover）支持直接打开。如果不行，可能可以在其窗口内导入。

### 使用命令行
````bash
flatpak remote-add --if-not-exists hmcl https://github.com/heipiao233/hmcl-flatpak/raw/refs/heads/main/hmcl-flatpak.flatpakrepo
````

## 旧版本 JDK
直接安装 OpenJDK 8/17/21 的对应 Flatpak 包，它们会被检测到。
