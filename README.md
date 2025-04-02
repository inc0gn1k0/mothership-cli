# mothership-cli

[![PyPI version](https://badge.fury.io/py/mothership-cli.svg)](https://badge.fury.io/py/mothership-cli)

**Modular Python project scaffolding CLI for structured, efficient development.**

---

## 🚀 Quick Start

```bash
pip install mothership-cli

startup mothership             # Set up folders
mothership project_alpha       # Create new modular app
mothership scaffold project_alpha
mothership push project_alpha
mothership pull https://github.com/you/repo.git
```

## 🧠 Features

- Clean folder architecture: `Finance/`, `General/`, `Specialist/`
- Plug-and-play FastAPI boilerplate
- Auto `venv` + `requirements.txt` on pull
- GitHub integration for push/pull

## 📦 Project Layout

```
mothership/
├── Finance/
│   └── your_project/
│       ├── logic/
│       ├── ui/
│       ├── web/
│       └── main.py
└── ...
```

## 📮 License

MIT © 2024 Nikolai Janiszewsky
