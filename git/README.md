# Git

## 获取 GIt 仓库

1. 在本地初始化 Git 仓库；
2. 从其他服务器 **克隆** 已有的 Git 仓库。

### 初始化仓库

进入需要管理的项目的根目录 *（新的项目，直接新建文件夹，并进入即可）*，并执行以下命令：

```bash
git init
```

该命令会创建一个隐藏的  `.git`  的子目录，此目录 **不得随意改动**。

### 克隆已有的仓库

进入你项目需要放置的目录，并执行以下命令：

```bash
git clone <url>
```

将你项目的 url 地址替换掉  `<url>`  即可，例如：

```bash
git clone https://github.com/SeptEarlyMorning/git-knowledge.git
```

当你想将项目重新命名时，在命令后接上新的名称即可，例如：

```bash
git clone https://github.com/SeptEarlyMorning/git-knowledge.git my_git-knowledge
```

上面使用的是  `HTTPS` 协议，你也可使用 `SSH` 传输协议 *（使用该协议时需要配置 **密钥**）*。

## 记录每次更新到仓库



