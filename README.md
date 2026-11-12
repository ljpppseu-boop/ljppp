# ljppp：智能车代码与调试交接

最新版：**NEWNEW_C26_DIRECT_20261112_V10**（2026-11-12），独立C26工程。

- **[下载最新版完整工程](releases/NEWNEW_C26_DIRECT_20261112_V10/source-code.zip)**：包含SDK、Keil工程、应用与主机检查。解压后打开`NEWNEW_C26_DIRECT_20261112_V10/demo/mdk/newnew_c26.uvprojx`，目标`nor_sdram_zf_dtcm`。
- [冻结固件、MAP与校验](releases/NEWNEW_C26_DIRECT_20261112_V10/README.md) · [应用源码浏览](source-review/NEWNEW_C26_DIRECT_20261112_V10/README.md)。
- [本次详细交接与下一步](docs/changes/2026-11-12_NEWNEW_C26_V10_HANDOFF.md) · [当前采用与演进](docs/PROJECT_EVOLUTION.md) · [文档目录及维护规则](docs/INDEX.md)。

C26 ON发车、OFF停止。直道目标1.4m/s，弯道按舵量/边距降速，实际环岛最高1.0m/s、避砖0.55m/s。Keil构建0错误0警告、所列主机检查通过；**V10尚未实车验收**，不宣称已完整通过环岛、红砖或1.4m/s稳定性验收。

本仓库归档独立NEWNEW，不替换fatezerozs/smartcar的MPC主工程。原始视频和串口字节流留本地，云端只保存选定结构化证据。
