# 师愈社教师工作台 · 发布仓库

这是师愈社教师工作台的安装包与更新清单仓库，不包含教师资料、密钥、班级数据或源码。

## 最新版本

- [下载最新版](https://github.com/chengzi-06/shiyushe-teacher-workbench-releases/releases/latest)
- 更新清单：<https://github.com/chengzi-06/shiyushe-teacher-workbench-releases/releases/latest/download/latest.json>

## 安装

- macOS（Apple 芯片）：解压 ZIP，双击「启动工作台.command」，选择专用资料文件夹。
- Windows x64：解压 ZIP，双击「启动工作台.cmd」，选择专用资料文件夹。

程序与资料分开保存；升级前先做完整备份并关闭旧版。详细说明见 [INSTALL.md](INSTALL.md)。

## 软件内检查更新

工作台「设置 → 程序与工具 → 程序与更新」填入上面的更新清单地址，点「检查更新」。只检查版本、平台和资料结构兼容性，不自动替换程序；下载 ZIP 后回到「检查程序更新包」校验，再按安装说明切换。

## 完整性

每个 Release 附 `SHA256SUMS.txt` 和 `latest.json`；ZIP 内还有逐文件校验清单。校验不替代发布者身份确认，请只使用本仓库发布的安装包。
