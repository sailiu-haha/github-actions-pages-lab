# GitHub Actions 与 GitHub Pages 实验

本仓库演示计算器的 pytest 单元测试，以及用 GitHub Actions 构建和发布 MkDocs 文档。

- `ci.yml` 在推送或拉取请求时运行测试。
- `deploy.yml` 在 `main` 文档更新或手动触发时构建并发布站点。
- Pages 的发布来源设为 **GitHub Actions**。
