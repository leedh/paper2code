# paper2code

> Reproducing and implementing AI/ML research papers, one model at a time.

`paper2code` is a curated collection of reproducible implementations of machine learning and artificial intelligence research papers. Each directory contains code, configurations, and documentation for replicating key ideas from papers.

## 📁 Repository Structure

```bash
paper2code/
├── README.md
├── papers/
│   ├── 2025/
│   │   ├── [TAG]_paper-title/
│   └── ...
├── utils/
│   └── common.py
├── scripts/
│   └── template_generator.py
├── requirements.txt
└── LICENSE
```

Each `papers/YYYY/[Tag]_paper-title/` folder contains:
- `main.py`: runnable implementation
- `README.md`: summary of the paper and implementation notes
- `config.yaml` or `.json`: model/training configs
- `notebooks/`: optional analysis or training logs
- `colab_link.md`: badge to open the project in Colab

## 📃 Included Papers

| Year | Title | Original Paper | Tag | Framework |
|------|-------|----------------|-----|-----------|

> 📌 To suggest new papers, open an [Issue](https://github.com/leedh/paper2code/issues) or submit a [Pull Request](https://github.com/leedh/paper2code/pulls).

## Quick Start

```bash
# Clone the repo
git clone https://github.com/leedh/paper2code.git
cd paper2code

# Install dependencies
pip install -r requirements.txt

# Run an example paper
cd papers/YYYY/[TAG]_TITLE
python main.py
```

## Template Generator

Create new paper folders with a unified structure using the script:

```bash
python scripts/template_generator.py --title "paper-title" --year YYYY --tag TAG
```

## Notebooks

Interactive analysis and training visualizations can be found under `/notebooks/` in each project folder.

## Open in Colab

For supported papers, use the badge below to open in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/leedh/paper2code/)

## License

MIT License. See [LICENSE](./LICENSE) for details.
