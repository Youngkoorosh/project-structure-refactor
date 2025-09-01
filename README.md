# 🧹 Project Structure Refactor

This repository contains a hands-on exercise for restructuring a disorganized project directory using basic Linux CLI commands. The goal is to apply a series of file and folder operations to transform the initial layout into a cleaner, more maintainable structure.

## 📁 Initial Structure

```
project
├── devv
│   ├── codes
│   │   ├── code1.py
│   │   └── code2.py
│   └── logs
│       ├── log1.txt
│       ├── log2.txt
│       └── log3.txt
└── tools
    └── script.sh
```

## 🎯 Target Structure

```
project
├── dev
│   ├── codes
│   │   ├── main.py
│   │   └── utils.py
│   └── tools
│       └── script.sh
└── tools
    └── script.sh
```

## 🛠️ Tasks to Perform

- Rename `devv` directory to `dev`
- Rename `code1.py` → `main.py`, and `code2.py` → `utils.py`
- Delete the `logs` directory and its contents
- Copy the `tools` directory into `dev` (not move)

## 📌 Notes

- You may use any CLI commands you've learned so far.
- Using `cd` to navigate directories is encouraged for clarity.
- Submit your solution either directly or via a `solution.sh` script.

---

Happy scripting! 🐧
