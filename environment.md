# 我的环境

> 这一页让 AI 知道「在你机器上能做什么、不能做什么」。
> ⚠️ 本仓库是公开的，**不要在这里写真实用户名、内网 IP、机器名**。

## 操作系统

- Windows 11
- 默认 shell：PowerShell（`pwsh`）
- <!-- 待填：其他系统（macOS / Linux 机器）如果需要也写在这里 -->

## 开发环境

| 工具 | 版本 | 备注 |
|---|---|---|
| Node.js | 24.x | 通过 DSH 内置运行时 |
| pnpm | 11.x | 包管理 |
| Python | 3.12 | 脚本、自动化 |
| Git | 2.56 | 便携版，装在非系统盘 |
| VS Code | 最新 | 主力编辑器 |

## AI 协作环境

- **DeepSeek Harness (DSH)**，profile：`desktop`
- 工作区：文档目录下的一个子文件夹
- 沙箱策略：允许写入工作区，系统目录受限

## 常用路径约定

<!-- 待填：换成你自己的真实路径，但注意别泄露用户名 -->

| 用途 | 路径 |
|---|---|
| 工作区 | `D:\文档\<项目名>` |
| 工具安装 | `D:\应用\` |
| 配置目录 | `C:\Users\<用户名>\.dsh` |

## 已知限制

- 网络：GitHub 直连可用，`raw.githubusercontent.com` 经常超时
- 大文件下载慢时会走国内镜像
- 没有管理员权限的场合较多，尽量用便携版

## 常用命令

```powershell
# 查看工作区
pwd

# 装 Python 依赖
pip install <package>

# 装 Node 依赖
pnpm add <package>
```
