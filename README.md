# hzt

个人代码仓库，用于存放日常脚本、笔记和实验性代码。

## 目录结构

| 路径 | 用途 |
| --- | --- |
| `docs/` | 笔记、方案、踩坑记录 |
| `.gitignore` | 通用忽略规则（系统、编辑器、各语言依赖） |
| `.editorconfig` | 统一缩进与换行，避免跨编辑器 diff 噪音 |
| `LICENSE` | MIT 许可 |

后续按需要新增的目录（暂未创建，有内容时再建）：

- `scripts/` — 一次性脚本与自动化任务
- `src/` — 有明确功能的代码，按语言或主题分子目录

## 获取代码

本仓库使用 SSH 认证：

```bash
git clone git@github.com:hzt54888/hzt.git
cd hzt
```

还没有配置 SSH 密钥的话，先在
[SSH and GPG keys](https://github.com/settings/keys) 添加公钥，再执行上面的命令。

## 提交约定

提交信息采用 `类型: 描述` 的形式，常用类型：

- `feat` — 新增功能
- `fix` — 修复问题
- `docs` — 文档改动
- `chore` — 构建、依赖、配置类杂项
- `refactor` — 不改变行为的重构

示例：

```
feat: 增加日志清理脚本
fix: 修正时间解析的时区问题
```

## 环境

主力环境为 Linux/macOS，脚本类代码以 Bash 与 Python 为主；涉及其他语言时会在对应目录下补充说明。

## License

[MIT](./LICENSE) © 2026 hzt54888
