# Awesome Python

A curated collection of exceptional Python frameworks, libraries, software, and resources. This comprehensive guide helps developers discover the best tools for their Python projects.

## Table of Contents

- [Admin Panels](#admin-panels)
- [Algorithms and Design Patterns](#algorithms-and-design-patterns)
- [Asynchronous Programming](#asynchronous-programming)
- [Audio](#audio)
- [Authentication](#authentication)
- [Build Tools](#build-tools)
- [Caching](#caching)
- [Command-line Tools](#command-line-tools)
- [Computer Vision](#computer-vision)
- [Cryptography](#cryptography)
- [Data Analysis](#data-analysis)
- [Data Validation](#data-validation)
- [Data Visualization](#data-visualization)
- [Database](#database)
- [Deep Learning](#deep-learning)
- [DevOps Tools](#devops-tools)
- [GUI Development](#gui-development)
- [Machine Learning](#machine-learning)
- [Natural Language Processing](#natural-language-processing)
- [Web Frameworks](#web-frameworks)
- [And many more...](#)

## Admin Panels

Frameworks for building administrative interfaces:

- **[django-grappelli](https://github.com/sehmaschine/django-grappelli)** - Enhanced skin for Django Admin Interface
- **[flask-admin](https://github.com/flask-admin/flask-admin)** - Extensible administrative interface framework for Flask
- **[streamlit](https://github.com/streamlit/streamlit)** - Build dashboards, reports, and chat apps in minutes

## Algorithms and Design Patterns

Python implementations of data structures, algorithms, and design patterns:

### Algorithms
- **[algorithms](https://github.com/keon/algorithms)** - Minimal examples of data structures and algorithms
- **[thealgorithms](https://github.com/TheAlgorithms/Python)** - All algorithms implemented in Python

### Design Patterns
- **[python-patterns](https://github.com/faif/python-patterns)** - Collection of design patterns in Python
- **[transitions](https://github.com/pytransitions/transitions)** - Lightweight finite state machine implementation

## Asynchronous Programming

Libraries for asynchronous, concurrent, and parallel execution:

- **[asyncio](https://docs.python.org/3/library/asyncio.html)** - Python standard library for asynchronous I/O
- **[trio](https://github.com/python-trio/trio)** - Friendly library for async concurrency and I/O
- **[uvloop](https://github.com/MagicStack/uvloop)** - Ultra-fast asyncio event loop
- **[twisted](https://github.com/twisted/twisted)** - Event-driven networking engine

## Audio

Libraries for manipulating audio and metadata:

### Audio Processing
- **[librosa](https://github.com/librosa/librosa)** - Python library for audio and music analysis
- **[pydub](https://github.com/jiaaro/pydub)** - Manipulate audio with a simple high-level interface

### Metadata
- **[mutagen](https://github.com/quodlibet/mutagen)** - Handle audio metadata for various formats

## Authentication

Libraries for implementing authentication schemes:

### OAuth
- **[authlib](https://github.com/lepture/authlib)** - Ultimate Python library for OAuth and OpenID
- **[django-allauth](https://github.com/pennersr/django-allauth)** - Authentication app for Django

### JWT
- **[pyjwt](https://github.com/jpadilla/pyjwt)** - JSON Web Token implementation in Python

## Build Tools

Tools for compiling software from source code:

- **[pybuilder](https://github.com/pybuilder/pybuilder)** - Continuous build tool written in pure Python
- **[scons](https://github.com/SCons/scons)** - Software construction tool

## Caching

Libraries for caching data:

- **[django-cacheops](https://github.com/Suor/django-cacheops)** - ORM cache with automatic granular event-driven invalidation
- **[python-diskcache](https://github.com/grantjenks/python-diskcache)** - Fast cache backend with SQLite and file support

## Command-line Tools

Libraries and tools for building CLI applications:

### Development
- **[click](https://github.com/pallets/click/)** - Create beautiful command-line interfaces
- **[python-fire](https://github.com/google/python-fire)** - Generate CLIs from any Python object

### Terminal Rendering
- **[rich](https://github.com/Textualize/rich)** - Rich text and beautiful formatting in the terminal
- **[tqdm](https://github.com/tqdm/tqdm)** - Fast, extensible progress bar

### Productivity
- **[cookiecutter](https://github.com/cookiecutter/cookiecutter)** - Create projects from templates
- **[httpie](https://github.com/httpie/cli)** - User-friendly cURL replacement

## Computer Vision

Libraries for computer vision tasks:

- **[opencv](https://opencv.org/)** - Open Source Computer Vision Library
- **[kornia](https://github.com/kornia/kornia/)** - Differentiable Computer Vision Library for PyTorch
- **[pytesseract](https://github.com/madmaze/pytesseract)** - Wrapper for Google Tesseract OCR

## Cryptography

Libraries for cryptographic operations:

- **[cryptography](https://github.com/pyca/cryptography)** - Cryptographic primitives and recipes for Python
- **[paramiko](https://github.com/paramiko/paramiko)** - Native Python SSHv2 protocol library

## Data Analysis

Libraries for data analysis:

- **[pandas](http://pandas.pydata.org/)** - High-performance data structures and analysis tools
- **[datasette](https://github.com/simonw/datasette)** - Multi-tool for exploring and publishing data
- **[optimus](https://github.com/hi-primus/optimus)** - Agile Data Science Workflows with PySpark

## Data Validation

Libraries for validating data:

- **[pydantic](https://github.com/pydantic/pydantic)** - Data validation using Python type hints
- **[jsonschema](https://github.com/python-jsonschema/jsonschema)** - JSON Schema implementation for Python
- **[cerberus](https://github.com/pyeve/cerberus)** - Lightweight and extensible data validation library

## Data Visualization

Libraries for visualizing data:

- **[matplotlib](https://github.com/matplotlib/matplotlib)** - Python 2D plotting library
- **[bokeh](https://github.com/bokeh/bokeh)** - Interactive web plotting for Python
- **[seaborn](https://github.com/mwaskom/seaborn)** - Statistical data visualization using Matplotlib
- **[plotly](https://plotly.com/python/)** - Interactive graphing library

## Database

### Database Drivers

#### MySQL
- **[mysqlclient](https://github.com/PyMySQL/mysqlclient)** - MySQL connector with Python 3 support
- **[pymysql](https://github.com/PyMySQL/PyMySQL)** - Pure Python MySQL driver

#### PostgreSQL
- **[psycopg](https://github.com/psycopg/psycopg)** - Most popular PostgreSQL adapter for Python

#### NoSQL
- **[pymongo](https://github.com/mongodb/mongo-python-driver)** - Official Python client for MongoDB
- **[redis-py](https://github.com/redis/redis-py)** - Python client for Redis

### ORM

- **[SQLAlchemy](https://www.sqlalchemy.org/)** - Python SQL Toolkit and Object Relational Mapper
- **[Django Models](https://docs.djangoproject.com/en/dev/topics/db/models/)** - Django ORM
- **[peewee](https://github.com/coleifer/peewee)** - Small, expressive ORM

## Deep Learning

Frameworks for neural networks and deep learning:

- **[tensorflow](https://github.com/tensorflow/tensorflow)** - Most popular deep learning framework by Google
- **[pytorch](https://github.com/pytorch/pytorch)** - Tensors and dynamic neural networks with strong GPU acceleration
- **[keras](https://github.com/keras-team/keras)** - High-level neural networks library
- **[pytorch-lightning](https://github.com/Lightning-AI/pytorch-lightning)** - Deep learning framework built on PyTorch

## DevOps Tools

Software and libraries for DevOps:

### Configuration Management
- **[ansible](https://github.com/ansible/ansible)** - Radically simple IT automation platform
- **[saltstack](https://github.com/saltstack/salt)** - Infrastructure automation and management system

### Monitoring
- **[psutil](https://github.com/giampaolo/psutil)** - Cross-platform process and system utilities module

## Distributed Computing

Frameworks for distributed computing:

- **[dask](https://github.com/dask/dask)** - Flexible parallel computing library
- **[PySpark](https://github.com/apache/spark)** - Apache Spark Python API
- **[Ray](https://github.com/ray-project/ray/)** - Parallel and distributed Python framework

## Documentation

Libraries for generating project documentation:

- **[sphinx](https://github.com/sphinx-doc/sphinx/)** - Python documentation generator
- **[pdoc](https://github.com/mitmproxy/pdoc)** - Auto-generate API documentation for Python libraries

## GUI Development

Libraries for creating graphical user interfaces:

- **[PyQt](https://doc.qt.io/qtforpython/)** - Python bindings for Qt framework
- **[kivy](https://kivy.org/)** - Library for creating NUI applications
- **[tkinter](https://wiki.python.org/moin/TkInter)** - Python's standard GUI package
- **[DearPyGui](https://github.com/RaylockLLC/DearPyGui/)** - GPU-accelerated Python GUI framework

## HTTP Clients

Libraries for working with HTTP:

- **[requests](https://github.com/psf/requests)** - HTTP Requests for Humans
- **[httpx](https://github.com/encode/httpx)** - Next-generation HTTP client for Python
- **[urllib3](https://github.com/urllib3/urllib3)** - HTTP library with thread-safe connection pooling

## Image Processing

Libraries for manipulating images:

- **[pillow](https://github.com/python-pillow/Pillow)** - Friendly PIL fork
- **[scikit-image](http://scikit-image.org/)** - Python library for scientific image processing
- **[opencv](https://opencv.org/)** - Open Source Computer Vision Library

## Machine Learning

Libraries for machine learning:

- **[scikit-learn](http://scikit-learn.org/)** - Most popular machine learning library for Python
- **[xgboost](https://github.com/dmlc/xgboost)** - Scalable gradient boosting library
- **[LightGBM](https://github.com/microsoft/LightGBM)** - Fast gradient boosting framework

## Natural Language Processing

Libraries for working with human languages:

- **[spacy](https://spacy.io/)** - Industrial-strength natural language processing
- **[nltk](http://www.nltk.org/)** - Leading platform for building NLP programs
- **[gensim](https://github.com/RaRe-Technologies/gensim)** - Topic modeling for humans
- **[transformers](https://github.com/huggingface/transformers)** - State-of-the-art NLP library

## Package Management

Libraries for package and dependency management:

- **[pip](https://pip.pypa.io/en/stable/)** - Package installer for Python
- **[poetry](https://github.com/sdispater/poetry)** - Python dependency management and packaging
- **[uv](https://github.com/astral-sh/uv)** - Extremely fast Python package manager written in Rust

## RESTful API

Libraries for building REST APIs:

### Django
- **[django-rest-framework](https://github.com/encode/django-rest-framework)** - Powerful toolkit for building web APIs

### Flask
- **[flask-restful](https://github.com/flask-restful/flask-restful)** - Quickly build REST APIs for Flask

### Framework Agnostic
- **[fastapi](https://github.com/tiangolo/fastapi)** - Modern, fast web framework for building APIs
- **[falcon](https://github.com/falconry/falcon)** - High-performance framework for building cloud APIs

## Science

Libraries for scientific computing:

- **[NumPy](http://www.numpy.org/)** - Fundamental package for scientific computing
- **[SciPy](https://www.scipy.org/)** - Python-based ecosystem for mathematics and science
- **[SymPy](https://github.com/sympy/sympy)** - Library for symbolic mathematics
- **[astropy](http://www.astropy.org/)** - Community Python library for astronomy

## Testing

Libraries for testing code:

### Testing Frameworks
- **[pytest](https://docs.pytest.org/en/latest/)** - Mature full-featured Python testing tool
- **[unittest](https://docs.python.org/3/library/unittest.html)** - Python standard library unit testing framework
- **[hypothesis](https://github.com/HypothesisWorks/hypothesis)** - Advanced property-based testing library

### Mock
- **[mock](https://docs.python.org/3/library/unittest.mock.html)** - Python standard library mocking and patching
- **[responses](https://github.com/getsentry/responses)** - Utility library for mocking out the requests library

### Test Runners
- **[tox](https://github.com/tox-dev/tox)** - Auto builds and tests in multiple environments

## Web Crawling

Libraries for automating web scraping:

- **[scrapy](https://github.com/scrapy/scrapy)** - Fast high-level web crawling framework
- **[beautifulsoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)** - Pythonic idioms for parsing HTML/XML
- **[selenium](https://pypi.org/project/selenium/)** - Python bindings for Selenium WebDriver

## Web Frameworks

Traditional full-stack web frameworks:

### Synchronous
- **[django](https://github.com/django/django)** - Most popular web framework in Python
- **[flask](https://github.com/pallets/flask)** - Microframework for Python
- **[pyramid](https://pylonsproject.org/)** - Small, fast, down-to-earth web framework

### Asynchronous
- **[tornado](https://github.com/tornadoweb/tornado)** - Web framework and asynchronous networking library
- **[fastapi](https://github.com/tiangolo/fastapi)** - Modern, fast framework for building APIs

## Contributing

Contributions are welcome! Please review the [contribution guidelines](https://github.com/vinta/awesome-python/blob/master/CONTRIBUTING.md) before submitting.

## Resources

Looking to discover more Python resources? Check out these learning platforms and communities:

- Python Package Index (PyPI)
- Python.org Documentation
- Real Python Tutorials
- Python Weekly Newsletter

## License

This curated list is inspired by [awesome-php](https://github.com/ziadoz/awesome-php) and maintained by the community.

---

**Connect**: Questions or suggestions? Contact [@VintaChen](https://twitter.com/VintaChen) or open an issue on GitHub.
