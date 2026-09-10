# SuccubusKill-Windows

《魅魔杀》Windows 桌面打包版分发仓库。

## 下载

前往 [Releases](https://github.com/meigang1993/SuccubusKill-Windows/releases) 页面
下载 `SuccubusKill.exe`（约 215 MB），放到全英文路径下直接运行即可，无需安装。

## 为什么单独一个仓库

主仓库 `meigang1993/-` 里的 `Windows版/` 目录使用 Git LFS 存储，真实二进制不计入
Git 仓库体积。但 LFS 免费额度为 1GB 存储 + 1GB 出网流量/月，249 MB 的包被下载
4 次就会耗尽当月流量，导致他人克隆失败。

Release 附件单文件上限 2 GB 且不计 LFS 流量，更适合对外分发，因此单独建此仓库。

## 版本对应

| Release | 游戏版本 |
|:--|:--|
| v26.0910.02 | v26.0910.02 |

## 源码

游戏源码与素材在主仓库：<https://github.com/meigang1993/->
