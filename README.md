# Legal Auto Research

Legal Auto Research 的 Windows 便携包分发仓库。仓库文件仅提供使用说明，不发布应用源代码；源码仓库保持私有。

## 下载与启动

1. 在 [最新 Release](https://github.com/beichen126/Legal-Auto-Research-Release/releases/latest) 下载完整的 `Legal-Auto-Research-win-x64-0.1.11.zip`。
2. **完整解压到全新目录**。不要从 ZIP 预览中启动，不要只拖出启动文件，也不要覆盖旧版本。
3. 解压目录应同时包含 `app`、`runtimes`、`workspace`；双击 `start.cmd`，静默启动用 `start-silent.cmd`，退出用 `stop.cmd`。

包内包含 Python、Node.js、Chromium 和依赖，无需另外安装 Python 或 Node.js。首次启动可能需要 1–3 分钟。

## 当前版本

- LAR：`v0.1.11`
- DSH / dsh-tools：`0.2.0-rc.2`（上游候选版）
- 平台：Windows x64
- 完整 ZIP 的 SHA-256：`03f22eaeb202fa0250605761058114b6e300e54794c775cc4afaba76fc5b63dd`

本版迁移了新版 DSH 的法律预设注册方式，修复便携运行时打包检查和跨目录路径定位。资料库沿用上一版；详细变更与验证结果见 Release 说明。

## 使用边界

- DeepSeek 模型密钥在 DSH 工作台内填写；MinerU 密钥在 LAR 设置页填写。
- 知网、北大法宝和人民法院案例库仍需使用者自己的合法账号、机构权限或校园网，不绕过登录、验证码或付费墙。
- 资料用于本地研究；转载或再分发需自行核实权利。
- 若提示缺少 `runtimes/python/python.exe`，先确认完整解压了 ZIP，且没有被安全软件隔离；便携包并不要求另装 Python。
- 更新时保留旧版本和旧工作区，新包解压到独立目录，不覆盖项目、会话、密钥和登录状态。
