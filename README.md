# cellgen

根据输入 CSV 计算 RAM 的 CELL 深度、位宽与拼接方案。

在本仓库根目录运行，uv 根据 `.python-version` 使用 Python 3.12，并自动安装项目：

```powershell
uv run cellgen --help
uv run cellgen input.csv --out-dir output
```

`input.csv` 替换为实际 RAM 规格表。依赖由 `uv.lock` 锁定；需要提前准备环境时，执行 `uv sync --locked`。
