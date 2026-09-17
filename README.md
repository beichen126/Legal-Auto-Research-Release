# Legal Auto Research

Legal Auto Research 的私有内测分发仓库。

本仓库不发布源代码。可运行的 Windows x64 便携包请从右侧 **Releases** 页面下载。

## 安装与启动

1. 下载最新 Release 中的 `Legal-Auto-Research-win-x64-*.zip`。
2. 将 ZIP **完整解压到一个全新目录**；不要直接在压缩包预览窗口内运行，也不要只拖出启动文件。
3. 确认解压目录中同时存在 `app`、`runtimes` 和 `workspace` 文件夹。
4. 双击 `LegalAutoResearch.pyw`，或运行 `start.cmd`。
5. 首次启动通常需要 1–2 分钟。退出时运行 `stop.cmd`。

便携包已经包含 Python、Node.js、Chromium 和所需依赖，不需要另外安装 Python。

## 当前内测版

- 版本：`v0.1.10-local-debug`
- 平台：Windows x64
- SHA-256：`10cd64869bfd7ff8ffc2ed200dfe58cee378e15287583ec2c839df931ce1b199`

## 注意事项

- 这是私有内测包，请勿转发或公开发布。
- DeepSeek API Key 在 DSH 工作台内填写；MinerU API Key 在程序“设置”页填写。
- 知网、北大法宝和人民法院案例库仍需使用者自己的合法账号、机构权限或校园网环境。
- 如果提示缺少 `runtimes/python/python.exe`，通常是因为直接从 ZIP 内启动；请重新完整解压后再运行。
