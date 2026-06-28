# 🐍 Python Deep Drive

A structured, hands-on collection of **54 Jupyter Notebooks** that walks through Python from absolute fundamentals to applied data & web tooling — variables, OOP, file I/O, NumPy, Pandas, web requests, scraping, API integration, data visualization (Matplotlib & Seaborn), and debugging. Every topic is documented with explanations, comparisons (often vs. Java), runnable code cells, and practice problems with solutions.

> 📌 This repo is a personal learning log — notebooks are added and refined as topics are studied, so content grows over time.

---

## 📂 Repository Structure

```
python-deep-drive/
├── 01. Python Basics/               → 27 notebooks: variables → modules
├── 02. OOP/                         → 6 notebooks: classes → encapsulation
├── 03. File Handling/
│   ├── 03.1 Text File Types/        → read/write/append modes + sample .txt files
│   ├── 03.2 JSON file Types/        → json.load/dump + sample .json files
│   ├── 03.3 JSONL Types/            → JSON Lines format + data.jsonl
│   └── 03.4 CSV Types/              → csv module (reader/writer/DictWriter) + sample .csv files
├── 04. Numpy/                       → 4 notebooks: arrays, dtypes, booleans, initialization
├── 05. Pandas Library/               → Series, DataFrame, aggregation, CSV/JSON import
├── 06. Python Request Librery/       → HTTP requests, response handling, query params
├── 07. Python BeautifulSoup Library/ → HTML parsing & web scraping
├── 08. API Intergration/             → consuming REST APIs with requests
├── 09. Matplotlib Library/           → 2D/3D plotting, all major chart types
├── 10. Searbon/                      → Seaborn: statistical & relational plots
├── 11. Errors/                       → syntax/runtime/logical errors, debugging, pdb
└── Modules/                          → custom module creation & import patterns
```

---

## 📚 Table of Contents

### 01. Python Basics
| # | Notebook | Covers |
|---|----------|--------|
| 01 | Variables | Syntax, naming rules, PEP 8 conventions, legal/illegal names |
| 02 | DataTypes | Numeric/string/sequence/mapping/boolean types, type conversion |
| 03 | Python Collections | List, Tuple, Set, Dictionary — quick overview |
| 04 | Python Lists | Indexing, slicing, CRUD ops, sort, copy, join (40+ cells) |
| 05 | Python Tuples | Immutability, single-item tuples, nested tuples, workarounds |
| 06 | PythonSet | Uniqueness, add/remove, set properties |
| 07 | Python Range | `range()` internals, negative steps, memory efficiency |
| 08 | Python Dictionaries | Key-value pairs, nested dicts, copy semantics |
| 09 | Python Operators | Arithmetic, Assignment, Comparison, Logical, Identity, Membership, Bitwise |
| 10 | Operator precedence | Evaluation order rules |
| 11 | Input Function | `input()` and type casting |
| 12 | Control Flow Statements | Overview of decision/loop constructs |
| 13 | if, else statement | Conditional branching, if-elif-else |
| 14 | Ternary Operator | One-line conditional expressions |
| 15 | Structural Pattern | `match-case` statement |
| 16 | Loops | For loop fundamentals |
| 17 | For Loop | List comprehension, factorial, inventory problems, break/continue |
| 18 | For-else Statement | `for...else` construct with practice problem |
| 19 | While Loop | `while`, `while-else`, for vs while comparison |
| 20 | Funstions | Function basics, Python vs Java methods, parameters vs arguments |
| 21 | Type of function Arguments | Positional, default, keyword, `*args`, `**kwargs` |
| 22 | Python Built in Functions | `abs()`, `map()`, `len()`, `round()`, `max()/min()`, `isinstance()` |
| 23 | Lambda Functions | Anonymous functions, PEP 8 best practices |
| 24 | f-String | Formatted string literals |
| 25 | Modules & Packages | Custom modules, `math`/`random` |
| 26 | _name method | `if __name__ == "__main__"` construct |
| - | test.ipynb | Scratch/sandbox notebook |

### 02. OOP
| # | Notebook | Covers |
|---|----------|--------|
| 01 | Classes & Objects | Class definition, object creation, naming conventions |
| 02 | self | The `self` parameter explained in depth |
| 03 | init method | `__init__` constructor |
| 04 | Inheritance | Parent/child classes, superclass patterns |
| 05 | Polymorphism | Method overriding, Java vs Python comparison |
| 06 | Encapsulation | `BankAccount` & `UserProfile` real-world examples |

### 03. File Handling
| Subfolder | Notebook | Covers |
|---|----------|--------|
| 03.1 Text File Types | file handling.ipynb | Modes `r`, `w`, `a`, `x`; safe reading with `with`; readline/readlines; writelines |
| 03.2 JSON file Types | 01. JSON.ipynb | `json.load()`, `json.dump()`, dict ↔ JSON conversion |
| 03.3 JSONL Types | JSONL.ipynb | JSON Lines parsing, `json.load()` vs `json.loads()` |
| 03.4 CSV Types | csv.ipynb | `csv.reader`, `csv.writer`, `DictWriter` vs `writer` comparison |

Includes real sample data files: `attendance.txt`, `sample_1.json`, `data.jsonl`, `students.csv`, `fail_students.csv`, etc.

### 04. Numpy
| # | Notebook | Covers |
|---|----------|--------|
| 01 | numpy | Array creation, math operators, `dtype` (int32/float32) |
| 02 | numpy multidimensional array | 2D/3D arrays |
| 03 | Boolian Condition | Boolean comparison & indexing on arrays |
| 04 | Array Initialization | `np.zeros`, `np.ones`, `np.full`, `np.empty` |

### 05. Pandas Library
Series vs DataFrame, `.loc`/`.iloc`, aggregation (`.sum()`, `.mean()`, `.describe()`), sorting, adding/dropping rows & columns, CSV import (`sample (1).csv`).

### 06. Python Request Librery
| # | Notebook | Covers |
|---|----------|--------|
| 01 | Request | `requests.get/post`, `response.text` vs `.content` vs `.json()`, headers |
| 02 | URL Parameters | Query parameters with `params=` |

### 07. Python BeautifulSoup Library
HTML parsing with `bs4`, tag navigation (`soup.p`, `soup.a`), `find()` vs `find_all()`, combining with `requests` for live scraping.

### 08. API Intergration
Practical example of consuming a REST API end-to-end with `requests`.

### 09. Matplotlib Library
| # | Notebook | Covers |
|---|----------|--------|
| 01 | Basics of Mathplotlib | Anatomy of a basic plot |
| 02 | Types of Plots | Bar, Scatter, Pie, Subplots, Histograms, Box Plots, Stack/Area Plots, 3D Scatter/Line/Surface plots, saving figures as PNG |

### 10. Searbon (Seaborn)
| # | Notebook | Covers |
|---|----------|--------|
| 01 | Basics Of Seaborn | Built-in datasets, Relational plots (Scatter), Categorical plots (Box & Violin), Matrix plots (Heatmap on flights data), Multi-plot grids (Pair Plot on the iris dataset), best practices |

### 11. Errors
| # | Notebook | Covers |
|---|----------|--------|
| 01 | Syntax Errors | Common causes & examples |
| 02 | Runtime Errors | Types + `try/except` handling |
| 03 | Logical Errors | Operator precedence bugs, off-by-one, mutable default args, wrong booleans, infinite loops |
| 04 | Debugging Principles | Core debugging techniques |
| 05 | Python Debugger (pdb) | `pdb.set_trace()` walkthrough |
| - | debug.py, breakpoint.py, pdb error test.py | Standalone scripts for live debugger practice |

### Modules
`Addition.py` + `Main.py` — demonstrates `import module`, `import module as alias`, and `from module import function` patterns.

---

## 🚀 Getting Started

### Prerequisites
- Python 3.x
- Jupyter Notebook / JupyterLab, or VS Code with the Jupyter extension

### Installation

```bash
# Clone the repository
git clone https://github.com/thilina-fer/python-deep-drive.git
cd python-deep-drive

# (Recommended) create a virtual environment
python -m venv venv
source venv/bin/activate      # Windows: venv\Scripts\activate

# Install the libraries used across the notebooks
pip install numpy pandas matplotlib seaborn requests beautifulsoup4 jupyter
```

### Running the notebooks

```bash
jupyter notebook
# or open the folder directly in VS Code and run cells with the Jupyter extension
```

> ⚠️ Some notebooks (e.g. in `03. File Handling`) read/write files using **relative paths**, so open them with that notebook's own folder as the working directory.

---

## 🛠️ Tech & Libraries Covered

`Python 3` · `NumPy` · `Pandas` · `Matplotlib` · `Seaborn` · `requests` · `BeautifulSoup4` · `json` / `csv` (standard library) · `pdb`

---

## 👤 Author

**Thilina Dilshan Fernando**
[GitHub @thilina-fer](https://github.com/thilina-fer)

---

⭐ If this helped you learn Python, consider starring the repo!
