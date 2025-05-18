# Charting the Future: Harnessing LLMs for Quantitative Finance
<img src="https://github.com/user-attachments/assets/90b06215-28b1-4b4b-b34e-8474154b5ca0" alt="Charting the Future Book Cover" width="300" align="right"/>

## About the Book

"Charting the Future: Harnessing LLMs for Quantitative Finance" explores the intersection of large language models and quantitative finance, offering practical insights, case studies, and implementable strategies for financial professionals. The book provides both theoretical foundations and hands-on examples of applying LLMs to financial analysis, risk management, trading strategies, and more.

## Official Companion Code Repository 

This repository contains all code examples featured in the book "Charting the Future: Harnessing LLMs for Quantitative Finance." Whether you're reading the printed edition or e-book, this repository gives you access to fully functional, runnable code that accompanies each chapter.

### Repository Structure

The code is organized by chapter, with each folder containing:

- Complete implementations of all code listings referenced in the book
- Additional helper functions and utilities
- Sample data files where applicable
- Chapter-specific README files mapping code to book sections
- Chapter-specific dependency management with `pyproject.toml` and lock files

```
📂 chapter01/
  📄 README.md - Guide to Chapter 1 code examples
  📄 pyproject.toml - Dependencies for Chapter 1
  📄 uv.lock - Lock file for exact dependency versions
  📄 listing_a1.py - Full implementation of Listing A.1
  📄 listing_a2.py - Full implementation of Listing A.2
  ...

📂 chapter02/
  ...
```

### How to Use This Repository

1. **Find the code you need**: Each chapter in the book references code examples as "Listing A.X". Navigate to the corresponding chapter folder and find the same listing number.

2. **Install dependencies**: Each chapter has its own dependency management. Navigate to the chapter directory and run `uv sync`.

3. **Run the examples**: Each Python file is self-contained and can be executed with `uv run`.

4. **Experiment and extend**: The code is designed to be modified and expanded upon. Use it as a starting point for your own projects.

### Dependencies

Most examples require Python 3.9+ and common data science libraries. We use `uv` for dependency management.

#### Installing `uv`

**macOS/Linux:**
```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```

**Windows:**
```bash
powershell -c "irm https://astral.sh/uv/install.ps1 | iex"
```

For more installation options, visit: https://github.com/astral-sh/uv

#### Installing Dependencies

To install dependencies for a specific chapter:

```bash
cd chapter01
uv sync
```

This will automatically set up a virtual environment and install all required dependencies defined in the chapter's `pyproject.toml` file.

#### Running Examples

To run any Python file using `uv`:

```bash
cd chapter01
uv run python listing_a1.py
```

### License

All code in this repository is available under the MIT License. See [LICENSE.md](LICENSE.md) for details.

### Feedback and Contributions

Found a bug or have a suggestion? Please open an issue or submit a pull request. We welcome contributions that improve the code or documentation.

---

*This repository complements the book by providing complete code implementations for all examples discussed in the text. While the book contains key code snippets, this repository offers the full, executable source code.*
