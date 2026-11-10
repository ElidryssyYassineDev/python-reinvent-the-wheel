
# Python Reinvention — Official Reference Library

This document contains trusted technical documentation for the technologies covered in this repository.

## 1. Python Core

| Resource | Purpose | Documentation |
|---|---|---|
| Python Tutorial | Language fundamentals | https://docs.python.org/3/tutorial/ |
| Python Language Reference | Syntax and semantics | https://docs.python.org/3/reference/ |
| Python Standard Library | Built-in modules | https://docs.python.org/3/library/ |
| Python Typing | Type hints | https://docs.python.org/3/library/typing.html |
| Python Data Model | Objects and dunder methods | https://docs.python.org/3/reference/datamodel.html |
| Python Packaging | Project packaging and dependencies | https://packaging.python.org/en/latest/ |
| PEP 8 | Python style conventions | https://peps.python.org/pep-0008/ |

## 2. Development Tools and Testing

| Resource | Purpose | Documentation |
|---|---|---|
| pip | Package installation | https://pip.pypa.io/en/stable/ |
| pytest | Automated testing | https://docs.pytest.org/en/stable/ |
| Ruff | Linting and formatting | https://docs.astral.sh/ruff/ |
| mypy | Static type checking | https://mypy.readthedocs.io/en/stable/ |
| Docker | Containerization | https://docs.docker.com/ |

## 3. Data Manipulation and Analysis

| Resource | Purpose | Documentation |
|---|---|---|
| NumPy | Numerical computing | https://numpy.org/doc/stable/ |
| Pandas | Data manipulation and analysis | https://pandas.pydata.org/docs/ |
| Matplotlib | Data visualization | https://matplotlib.org/stable/ |
| Jupyter | Interactive notebooks | https://docs.jupyter.org/ |

## 4. Backend Development

| Resource | Purpose | Documentation |
|---|---|---|
| FastAPI | REST API development | https://fastapi.tiangolo.com/ |
| Pydantic | Data validation | https://docs.pydantic.dev/latest/ |
| SQLAlchemy | ORM and database integration | https://docs.sqlalchemy.org/en/20/ |
| Alembic | Database migrations | https://alembic.sqlalchemy.org/en/latest/ |
| PostgreSQL | Relational database | https://www.postgresql.org/docs/ |
| HTTPX | HTTP client | https://www.python-httpx.org/ |
| Python asyncio | Asynchronous programming | https://docs.python.org/3/library/asyncio.html |

## 5. Machine Learning

| Resource | Purpose | Documentation |
|---|---|---|
| Scikit-learn | Traditional machine learning | https://scikit-learn.org/stable/ |
| PyTorch | Deep learning | https://pytorch.org/docs/stable/ |
| Hugging Face | ML and AI ecosystem | https://huggingface.co/docs |

## 6. LLM Engineering and Generative AI

| Resource | Purpose | Documentation |
|---|---|---|
| Hugging Face Transformers | Pretrained models and inference | https://huggingface.co/docs/transformers/ |
| Hugging Face Datasets | Dataset loading and processing | https://huggingface.co/docs/datasets/ |
| Hugging Face Tokenizers | Tokenization | https://huggingface.co/docs/tokenizers/ |
| LangChain | LLM application orchestration | https://docs.langchain.com/ |
| LlamaIndex | Data ingestion and RAG | https://docs.llamaindex.ai/ |
| Qdrant | Vector database | https://qdrant.tech/documentation/ |
| pgvector | Vector search in PostgreSQL | https://github.com/pgvector/pgvector |
| OpenAI API | LLM API integration | https://platform.openai.com/docs/ |
| Anthropic API | Claude API integration | https://docs.anthropic.com/ |

## 7. Security and Engineering Practices

| Resource | Purpose | Documentation |
|---|---|---|
| OWASP Top 10 | Application security awareness | https://owasp.org/www-project-top-ten/ |
| OWASP API Security | API security risks | https://owasp.org/www-project-api-security/ |
| Git Documentation | Version control | https://git-scm.com/doc |
| GitHub Documentation | Repository management | https://docs.github.com/ |

---

## Documentation Usage Rules

1. Prefer official documentation for technical claims and API usage.
2. Verify version-specific behavior before suggesting implementation.
3. Never present deprecated APIs as modern best practices.
4. Use documentation examples as a starting point, not as a substitute for understanding.
5. Distinguish stable APIs from experimental functionality.
6. When official documentation is unclear, consult maintained technical references and explain the uncertainty.
7. Avoid unnecessary framework dependencies when native Python or a simpler library is sufficient.

## Learning Philosophy

Understand the underlying concept before adopting an abstraction.

Use small implementations to understand how things work, then use established libraries for real-world engineering.
