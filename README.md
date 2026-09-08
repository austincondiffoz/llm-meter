# llm-meter

Estimate LLM cost of a file before you send it

Built for my own use; public in case it helps someone.

## How to use

```bash
python cost.py prompt.txt --model gpt-4o-mini --expect-out 500
```

## Getting started

```bash
# stdlib only
```

## Highlights

- Per-model pricing table in JSON
- Reports input/output tokens and USD estimate
- Heuristic token estimate (~4 chars/token)
- Zero dependencies

## Project structure

```text
├── docs/
│   ├── development.md
│   ├── roadmap.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── tests/
│   └── test_smoke.py
├── .editorconfig
├── .gitignore
├── SECURITY.md
├── cost.py
└── pricing.json
```

## Development

```bash
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
python -m pytest -q
```

## 说明

个人练习项目, 谨慎用于生产环境。
