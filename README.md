# DSHTest

本仓库由 DSHTest 工作区初始化。

## 环境

- Git for Windows 2.53.0.windows.2
- 默认分支：`main`

## 使用

```bash
git status
git add .
git commit -m "描述本次改动"
git push
```

## 备注

- 远程仓库尚未关联，待 GitHub 仓库创建后执行：
  ```bash
  git remote add origin git@github.com:<用户名>/<仓库名>.git
  git push -u origin main
  ```
- GitHub SSH 走 443 端口（22 端口被网络屏蔽）。
