# autooptm

The command line of [AutoOptm](https://autooptm.com): make your training or
inference program faster on your own GPU (`autooptm` opens the terminal UI),
or send it to ours (`autooptm run --cloud .`).

This repository only hosts the release builds. Documentation:
<https://autooptm.com/cli>.

## Install

```sh
curl -fsSL https://autooptm.com/install.sh | sh
```

Where autooptm.com is slow (mainland China, many cloud GPU hosts), install
from this repository's release instead; it downloads from GitHub first:

```sh
curl -fsSL https://github.com/autooptm/cli/releases/latest/download/install.sh | sh
```

Both put one file, `autooptm`, in `~/.local/bin` after checking it against
`SHA256SUMS`. Linux and macOS, x86_64 and arm64; on Windows use WSL.

## 安装

```sh
curl -fsSL https://autooptm.com/install.sh | sh
```

国内网络（包括 AutoDL 等国内 GPU 云）访问 autooptm.com 慢，可以从这里的 Release 安装，会优先从 GitHub 下载：

```sh
curl -fsSL https://github.com/autooptm/cli/releases/latest/download/install.sh | sh
```

装好后运行 `autooptm`，第一次会让你登录。文档：<https://autooptm.com/zh/cli>。
