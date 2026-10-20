# AGENTS.md

## 規定

- 所有的回應都使用繁體中文。
- 使用 conda 管理 Python 套件。
- Conda 的環境是 `iem_python`。
- 專案所使用的程式語言為 Python。

## What this repo is

- Personal Python learning notebook repo (student lab: `c115143103-lab/115-programmming`).
- Content and comments are in **Traditional Chinese**; keep that language when editing notebook text.
- No application code, package manager, tests, lint, CI, or build config exist. Only `.gitignore` (standard Python template) and Jupyter notebooks.

## Layout

- Topic folders use **Chinese names** (e.g. `迴圈/` = "loops"). Path encoding can look garbled in some shells — set UTF-8 output (e.g. `[Console]::OutputEncoding = [System.Text.Encoding]::UTF8` in PowerShell) before listing files.
- One notebook per topic so far: `迴圈/loopcode.ipynb` (multiplication-table loop exercises).

## Working with the notebooks

- Notebook kernel: Python 3.12.13 (`iem_python` / `python3`).
- **Do not "fix" or complete exercise code unless explicitly asked.** Cells intentionally contain student mistakes and drafts (e.g. missing `:` after `for`, `i-2` instead of `i=3`, duplicated trial cells). The task is often stated in a nearby markdown cell (e.g. 「練習：將上面每一row最後面的逗號移除」).
- Stored cell `outputs` are often stale or inconsistent with the cell `source` — trust the source, and clear/regenerate outputs rather than editing them by hand.
- Practice/new solutions go in the topic's existing notebook (new cells), not in new scripts or packages.
