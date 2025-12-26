---
output: github_document
---

# Data Science with Python <img src="assets/cover.png" align="right" width="150"/>

<!-- badges: start -->
[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
[![Python Version](https://img.shields.io/badge/Python-3.11+-blue.svg)](https://www.python.org/)
[![Quarto](https://img.shields.io/badge/Quarto-1.4+-orange.svg)](https://quarto.org/)
<!-- badges: end -->

> **Data Analysis and Prediction Algorithms with Python**
> 
> By Daniel Paredes Inilupu

## 📖 Read Online

**[https://dparedesi.github.io/Data-Science-with-Python-book/](https://dparedesi.github.io/Data-Science-with-Python-book/)**

## 📚 What You'll Learn

| Part | Topics |
|------|--------|
| **I. Fundamentals** | Python objects, functions, data structures, pandas |
| **II. Visualization** | matplotlib, seaborn, Gapminder case study |
| **III. Statistics** | Probability, distributions, inference with scipy |
| **IV. Data Wrangling** | Importing data, text processing |
| **V. Machine Learning** | scikit-learn, classification, regression, clustering |
| **VI. Applied Cases** | Real estate analysis, Google Analytics |
| **VII. Generative AI** | LLM APIs, embeddings, RAG |
| **Appendix** | Ethics checklist, OOP introduction |

## ✨ Key Features

- **Modern Python**: Uses pandas method chaining and modern best practices
- **scikit-learn**: Full ML chapters using the scikit-learn framework
- **Real-World Cases**: Includes case studies with real datasets
- **GenAI Integration**: Covers using LLMs and APIs in Python
- **Ethics**: Dedicated sections on algorithmic bias and ethics checklist

## 🛠️ Technical Stack

- **Python**: 3.11+
- **Framework**: [Quarto](https://quarto.org/)
- **ML**: [scikit-learn](https://scikit-learn.org/)
- **Visualization**: [matplotlib](https://matplotlib.org/), [seaborn](https://seaborn.pydata.org/)

## 🚀 Quick Start

```bash
# Create virtual environment
python -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Preview the book
quarto preview

# Build the book
quarto render
```

The output will be generated in the `docs/` folder.

## 📂 Datasets

All datasets used in this book are hosted directly in this repository and served via GitHub Pages. You can browse them in the [`docs/data/`](docs/data/) directory.

To access them in Python:

```python
import pandas as pd
url = "https://dparedesi.github.io/Data-Science-with-Python-book/data/student-grades.csv"
grades = pd.read_csv(url)
```

## 📁 Structure

```
├── 01-introduction/      Python & VS Code Setup
├── 02-fundamentals/      Objects, Functions, Data Structures
├── 03-visualization/     matplotlib, seaborn, Gapminder
├── 04-statistics/        Probability and Inference
├── 05-wrangling/         Data Import, Text Processing
├── 06-machine-learning/  Supervised & Unsupervised Learning
├── 07-real-cases/        Applied Case Studies
├── 08-genai/             Generative AI with Python
├── 09-appendix/          Ethics Checklist, OOP
```

## 📝 Citation

If you use this book in your work, please cite:

```bibtex
@book{paredes2025datasciencepython,
  author = {Paredes Inilupu, Daniel},
  title = {Data Science with Python: Data Analysis and Prediction Algorithms},
  year = {2025},
  edition = {1st},
  publisher = {GitHub},
  url = {https://dparedesi.github.io/Data-Science-with-Python-book/}
}
```

## 💰 Support This Work

Over 700 hours went into creating this resource. If you find it valuable, consider purchasing the PDF on [Leanpub](https://leanpub.com/data-science-with-python). Your purchase includes:

- Future updates at no extra cost
- Three months of direct Q&A access with the author
- Support for keeping the web version free for everyone

You can also ⭐ star the repository and share it with others!

## 🤝 Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on how to report errors, suggest improvements, or submit fixes.

## 📄 License

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">
<img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" />
</a>
<br />
This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.

## 📧 Contact

Questions or suggestions? Email: dparedesi@uni.pe
