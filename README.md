# 蓝盾安全

纯 C 语言编写的 Windows 安全软件：快速反应型 · 低资源 · 本地 AI。

## 发布结构
- `index.html` — 蓝盾安全官网（单文件自包含版，任何电脑浏览器直接打开）
- `蓝盾安全_Setup.exe` — Windows 安装包（Inno Setup 打包，3.7MB）

## 在线发布（GitHub）
1. 把本目录推送到 GitHub 仓库（如 `lanshield`）
2. 仓库 Settings → Pages → 选择 main 分支根目录 → 官网 = `https://<用户名>.github.io/<仓库名>/`
3. 新建 Release（Tag 如 `v1.0.0`）→ 上传 `蓝盾安全_Setup.exe` 为附件
4. 把 `index.html` 里下载按钮 href 改为 Release 附件直链：
   `https://github.com/<用户名>/<仓库名>/releases/download/v1.0.0/蓝盾安全_Setup.exe`
