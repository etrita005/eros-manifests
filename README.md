# eros-manifests

Eros 项目使用 `repo` 工具管理多仓库代码。以下是初始化项目的步骤：

## 初始化项目

### 1. 初始化 repo

```bash
repo init -u https://github.com/etrita005/eros-manifests.git -b wuyi --manifest-name=eros.xml
```

### 2. 同步代码

```bash
repo sync
```

## 常用命令

| 命令 | 说明 |
|------|------|
| `repo init -u <url> -b <branch>` | 初始化 repo 仓库 |
| `repo sync` | 同步所有项目代码 |
| `repo status` | 查看所有项目状态 |
| `repo forall -c <command>` | 对所有项目执行命令 |
| `repo start <branch>` | 创建新分支 |
