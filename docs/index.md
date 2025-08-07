# Hello-World Project Documentation

Welcome to the documentation for the hello-world project.

## Overview
This project is a simple Python package demonstrating best practices for project structure, packaging, and testing.

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/dsparthiban/hello-world.git
   cd hello-world
   ```
2. Create and activate a virtual environment:
   ```sh
   python -m venv .venv
   # On Windows PowerShell
   .venv\Scripts\Activate.ps1
   # On Unix or macOS
   source .venv/bin/activate
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Usage
Run the main module:
```sh
python src/hello_world/main.py
```

## Project Structure
```
hello-world/
│   README.md
│   pyproject.toml
│   requirements.txt
│   ...
├── src/
│   └── hello_world/
│       ├── __init__.py
│       └── main.py
├── tests/
│   └── hello_world/
│       └── test_main.py
└── docs/
    └── index.md
```

## Running Tests
From the project root, run:
```sh
python -m unittest discover -s tests
```

## Contributing
See the [CONTRIBUTING.md](../CONTRIBUTING.md) file for guidelines.
