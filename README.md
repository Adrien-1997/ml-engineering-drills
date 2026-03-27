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

### module5.ipynb &nbsp;·&nbsp; Live Coding Patterns

| Topic | Concepts |
|---|---|
| Sliding window | fixed/variable-size windows, rolling stats with `deque`, O(n) optimization |
| Two pointers | two-sum on sorted arrays, batch processor pattern |
| Data engineering | group-by aggregation, order-preserving deduplication, arbitrary-depth flatten, inverted index |
| ML from scratch | k-fold cross-validation, stratified train-test split, precision/recall/F1, ROC-AUC (trapezoidal rule) |
| Normalization | fit/transform pattern, z-score normalization, permutation importance |

### module4.ipynb &nbsp;·&nbsp; Serving and Production

| Topic | Concepts |
|---|---|
| FastAPI routing | GET/POST/PUT/DELETE routes, path/query parameters, `HTTPException` |
| Pydantic I/O | request/response models, `Field()` constraints, `field_validator`, serialization |
| Lifespan management | `@asynccontextmanager`, startup/shutdown hooks, loading models once |
| Dependency injection | `Depends`, API key auth, pagination, shared model loaders |
| Async/await | async functions, `await`, I/O-bound vs CPU-bound, event loop |
| Concurrent execution | `asyncio.gather`, `asyncio.wait_for`, `asyncio.Semaphore` for rate limiting |
| Thread & process pools | `ThreadPoolExecutor` for blocking I/O, `ProcessPoolExecutor` for CPU work |
| Testing | `pytest` fixtures, `@pytest.mark.parametrize`, `TestClient`, `monkeypatch` |

---

## Usage

Open notebooks in Jupyter or VS Code and work through the exercises in order. Each section follows the pattern: lesson with annotated examples, then exercises with hidden solutions (`# SOLUTION` comments).

## Tags

`python` `machine-learning` `numpy` `pandas` `data-science` `ml-engineering` `jupyter-notebook` `exercises` `interview-prep` `pydantic` `scikit-learn` `logging` `fastapi` `async` `pytest` `algorithms` `sliding-window` `two-pointers`
