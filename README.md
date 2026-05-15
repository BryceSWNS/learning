# Learning 项目文件说明

## 启动http本地服务

`cd /home/tou/learning && python3 -m http.server 8000`

## 文件列表

| 文件 | 内容 | 打开方式 | 本地服务地址 |
|------|------|---------|------------|
| `git-essentials.html` | 大厂必备 Git 操作基础知识手册 | <file://wsl.localhost/Ubuntu/home/tou/learning/git-essentials.html> | <http://localhost:8000/git-essentials.html> |
| `progit-zh.html` | 《Pro Git》第二版 官方中文版（单页 HTML，可全文搜索，构建 2.1.78） | <file://wsl.localhost/Ubuntu/home/tou/learning/progit-zh.html> | <http://localhost:8000/progit-zh.html> |
| `progit-zh.pdf` | 《Pro Git》第二版 官方中文版（PDF，501 页） | <file://wsl.localhost/Ubuntu/home/tou/learning/progit-zh.pdf> | <http://localhost:8000/progit-zh.pdf> |
| `runoob-git-tutorial-full.html` | 菜鸟教程 Git 文档合并提取版（15 章节） | <file://wsl.localhost/Ubuntu/home/tou/learning/runoob-git-tutorial-full.html> | <http://localhost:8000/runoob-git-tutorial-full.html> |
| `runoob-git-tutorial-extracted.html` | 菜鸟教程 Git 入口页正文提取版 | <file://wsl.localhost/Ubuntu/home/tou/learning/runoob-git-tutorial-extracted.html> | <http://localhost:8000/runoob-git-tutorial-extracted.html> |

## WSL + Windows 浏览器访问说明

- 直接访问本地文件时请使用 `file://wsl.localhost/<发行版名>/...`，例如：`file://wsl.localhost/Ubuntu/home/tou/learning/runoob-git-tutorial-full.html`
- 如果你的发行版不是 `Ubuntu`，请替换为实际名称（可在终端执行 `wsl -l` 查看）
