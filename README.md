# 怪物显隐

- [MHGU怪物隐藏.zip](02_build/%E6%88%90%E5%93%81MOD/%E6%80%AA%E7%89%A9%E6%98%BE%E9%9A%90/MHGU%E6%80%AA%E7%89%A9%E9%9A%90%E8%97%8F.zip)

[完整源码与功能说明](01_plugins/monster_hide/)。包内提供安装说明；安装包按原样保存。

构建：克隆到纯 ASCII 路径，准备 Rust nightly、rust-src、cargo-mhgu-forge 1.5.0、ARM GNU Toolchain 和 Python 3。进入本目录后运行：

```powershell
powershell -NoProfile -ExecutionPolicy Bypass -File .\06_tools\build.ps1 -Project monster_hide
python .\06_tools\patches\pack_monster_hide.py
```

2026-11-14 上传已有安装包与当前源码快照；ZIP 完整性及包内 NRO 重定位检查通过，本次未重新编译或进行游戏测试。Eden / Switch 需要另装兼容的 Forge 前置；源码快照不保证与历史二进制逐字节复现。
