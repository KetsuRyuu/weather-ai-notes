# Day1

每次敲代码前，思考3个问题：

- 这个代码属于 **数据/可视化/模型/工具**哪一层？
- 以后我还会不会用它？
- 别人（未来的自己）是否可以看懂？

## 基本项目结构

```powershell
project_root/
├── README.md
├── data/
│   ├── raw/          # 原始数据（不改）
│   └── processed/    # 处理后的数据
├── src/
│   ├── __init__.py
│   └── utils/
├── notebooks/
├── scripts/
├── docs/
└── logs/

```



- `data`: 数据永远和代码分开
- `src`：可复用逻辑
- `scripts`: 一次性/CLI脚本
- `notebooks`：探索，实验，画图
- `docs/logs`：给‘人’看的，不是给机器看的