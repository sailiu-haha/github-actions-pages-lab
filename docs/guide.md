# 使用指南

在仓库根目录用 Python 3.11 执行以下命令：

```powershell
python -m pip install -r requirements.txt
python -m pytest -v
python -m pip install -r requirements-docs.txt
python -m mkdocs build --strict
python -m mkdocs serve
```

构建输出位于 `site/`。预览服务默认监听 `http://127.0.0.1:8000/`。修改 `docs/` 下的 Markdown 后即可在本地查看。
