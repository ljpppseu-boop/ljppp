# 文档目录与维护规则

- [当前采用与演进档案](PROJECT_EVOLUTION.md)：当前版本、进度和每次提交简略索引。
- [2026-11-12 / NEWNEW C26 V10交接](changes/2026-11-12_NEWNEW_C26_V10_HANDOFF.md)：实现、有效/无效尝试、软件证据、未完成项与接手步骤。
- [版本固件与校验](../releases/README.md) · [选定证据](../evidence/newnew-c26-v10-20261112/README.md)。

维护规则沿用[fatezerozs/smartcar文档目录](https://github.com/fatezerozs/smartcar/blob/2316cecb3855e4b022febdb6cdd7fcc4349137dc/docs/INDEX.md)与[演进档案维护约定](https://github.com/fatezerozs/smartcar/blob/2316cecb3855e4b022febdb6cdd7fcc4349137dc/docs/PROJECT_EVOLUTION.md)：

1. 当前采用与进度统一维护演进档案，README只给入口。
2. 每次push另写`docs/changes/YYYY-MM-DD_主题.md`，演进档案增加一行。
3. 代码实现、主机回归、实拍观察、实车验收分别记录。
4. 冻结旧版本、失败证据和校验，不改写历史为新成功。
5. 原始录制留本地，只提交选定结构化证据；发布产物与源码明确绑定。
6. 新增/移动文件同时核对相对链接，不将个人C盘路径当作队友下载路径。
