# ML Engineering Drills

Structured Python notebooks for ML Engineers, covering core Python patterns, static typing, data manipulation, and validation.

---

## Modules

### module1.ipynb &nbsp;·&nbsp; Python Foundations

| Topic | Concepts |
|---|---|
| Native data structures | list, dict, set, tuple, defaultdict, Counter, deque |
| Functions | `*args`/`**kwargs`, higher-order functions, `functools.partial` |
| Closures | scaler factories, memoization, closure-in-loop pitfalls |
| Generators & iterators | `yield`, batch loaders, `itertools` (islice, chain, groupby) |
| Decorators | timer, retry, TTL cache, `@property`, `@staticmethod`, `@classmethod` |
| Error handling | custom exception hierarchies, context managers (`@contextmanager`) |

### module2.ipynb &nbsp;·&nbsp; Data-Oriented Python

| Topic | Concepts |
|---|---|
| Static typing | annotations, `Optional`, `Union`, `TypeVar`, `Protocol`, `Callable` |
| Dataclasses | `field()`, `__post_init__`, `frozen`, `replace()`, when to use over Pydantic |
| Pydantic | `field_validator`, `model_validator`, `Literal`, `ValidationError`, serialization |
| Pandas | groupby aggregation, `transform`, merge/join, `apply`, `pivot_table`, `melt` |
| Pandas time series | rolling windows, lag features, `shift`, `pct_change` |
| NumPy | vectorization, broadcasting, advanced indexing, softmax and cosine similarity from scratch |

### module3.ipynb &nbsp;·&nbsp; ML Engineering Patterns

| Topic | Concepts |
|---|---|
| OOP for ML | `BaseEstimator`, `TransformerMixin`, abstract base classes (`ABC`) |
| Pipelines & composition | `Pipeline`, `ColumnTransformer`, custom transformers |
| Files, serialization & config | `pathlib`, `json`, `joblib`, `dotenv`, environment variables |
| Logging & debugging | `logging` module, `pdb`, structured log levels |

---

## Usage

Open notebooks in Jupyter or VS Code and work through the exercises in order. Each section follows the pattern: lesson with annotated examples, then exercises with hidden solutions (`# SOLUTION` comments).

## Tags

`python` `machine-learning` `numpy` `pandas` `data-science` `ml-engineering` `jupyter-notebook` `exercises` `interview-prep` `pydantic` `scikit-learn` `logging`
