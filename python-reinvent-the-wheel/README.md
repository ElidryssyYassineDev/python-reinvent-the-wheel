
# Python Reinvent the Wheel 🐍

A hands-on journey to mastering Python for software engineering, data manipulation, backend development, and AI engineering.

The objective is not simply to learn Python syntax. It is to understand the language deeply, develop practical engineering skills, and build real applications using the Python ecosystem.

## 🎯 Learning Objectives

### 1. Python Core
- Master Python fundamentals and advanced language features.
- Understand Python's object model and execution behavior.
- Learn iterators, generators, decorators, context managers, and asynchronous programming.
- Develop clean, maintainable, Pythonic code.

### 2. Data Manipulation
- Work with CSV, JSON, Excel, and structured datasets.
- Learn NumPy and Pandas.
- Clean, transform, aggregate, and analyze data.
- Visualize results using Matplotlib.

### 3. Backend Development
- Build REST APIs using FastAPI.
- Validate data using Pydantic.
- Integrate PostgreSQL and SQLAlchemy.
- Implement authentication, testing, logging, and error handling.

### 4. AI Engineering
- Understand machine learning and deep learning fundamentals.
- Learn Scikit-learn and PyTorch.
- Integrate LLM APIs into applications.
- Explore embeddings, vector databases, RAG, and AI agents.
- Build practical AI-powered backend services.

## 📁 Repository Structure

```text
.
├── notes/                 # Learning notes and explanations
├── exercises/             # Progressive coding exercises
├── projects/              # Practical engineering projects
├── tests/                 # Tests and testing experiments
├── datasets/
│   └── sample/            # Small learning datasets
├── README.md
├── PROGRESS.md
├── BOOTCAMP_ROADMAP.md
├── LEARNER_CONTEXT.md
├── REFERENCE_LIBRARY.md
├── pyproject.toml
└── .gitignore
```

## ⚙️ Development Environment

Requirements:
- Python 3.12 or newer.
- Git.
- A code editor (VS Code or PyCharm recommended).

### Setup on Windows

Clone the repository:

```powershell
git clone https://github.com/YOUR_USERNAME/python-reinvent-the-wheel.git

cd python-reinvent-the-wheel
```

Create a virtual environment:

```powershell
py -m venv .venv
```

Activate it:

```powershell
.\.venv\Scripts\Activate.ps1
```

Verify Python:

```powershell
python --version
```

Install development tools:

```powershell
python -m pip install --upgrade pip
python -m pip install pytest ruff
```

## 🧪 Quality Checks

Run tests:

```powershell
python -m pytest
```

Check code quality:

```powershell
ruff check .
```

Format Python code:

```powershell
ruff format .
```

## 📚 Learning Methodology

Every topic follows an incremental approach:

1. Understand the underlying concept.
2. Study practical examples.
3. Solve progressive exercises.
4. Implement independently.
5. Review and improve the implementation.
6. Consolidate knowledge through testing.

## 🚀 Projects

| Project | Objective |
|---|---|
| Log Archive | File manipulation and CLI development |
| FastAPI CRUD API | Backend and database integration |
| ML Classifier | Machine learning fundamentals |
| CSV Insight API | Data analysis and backend integration |

## 📈 Progress Tracking

Learning progress is documented in [PROGRESS.md](PROGRESS.md).

The curriculum is documented in [BOOTCAMP_ROADMAP.md](BOOTCAMP_ROADMAP.md).

Official learning resources are maintained in [REFERENCE_LIBRARY.md](REFERENCE_LIBRARY.md).

## 💡 Learning Philosophy

Reinvent the wheel to understand how things work, not to unnecessarily replace reliable production libraries.

Every implementation should help develop deeper technical understanding and independent problem-solving skills.

---

**Learning through understanding, implementation, experimentation, and iteration.**
