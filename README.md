# Learning Discrete Mathematical Structures Using Python

An interactive, code-first introduction to **discrete mathematics**. Each topic is taught in a Jupyter notebook that pairs the mathematical ideas with runnable Python, so you can read a definition, see it demonstrated, and experiment with it yourself.

Every notebook follows the same rhythm:

1. **Concepts** — the definitions and ideas, written with LaTeX/KaTeX math.
2. **Worked examples** — small problems solved inline with Python (answers shown).
3. **Practice problems** — a numbered set at the end with a code cell to work in and **no answers given**.

Fully worked solutions to the practice problems live in the [`solutions/`](solutions/) folder.

## Notebooks

| # | Notebook | Topic |
| --- | --- | --- |
| 00 | [00_introduction.ipynb](00_introduction.ipynb) | Course overview, topics, and conventions |
| 01 | [01_sets.ipynb](01_sets.ipynb) | Sets, subsets, and set operations |
| 02 | [02_sequences.ipynb](02_sequences.ipynb) | Sequences, series, and recurrence relations |
| 03 | [03_regular_expressions.ipynb](03_regular_expressions.ipynb) | Regular expressions and the `re` module |
| 04 | [04_number_theory.ipynb](04_number_theory.ipynb) | Modular arithmetic, GCD/LCM, bases, ciphers |
| 05 | [05_matrices.ipynb](05_matrices.ipynb) | Matrices and matrix operations |
| 06 | [06_propositional_logic.ipynb](06_propositional_logic.ipynb) | Propositions, logical operators, truth tables |
| 07 | [07_mathematical_induction.ipynb](07_mathematical_induction.ipynb) | Methods of proof and mathematical induction |
| 08 | [08_relations.ipynb](08_relations.ipynb) | Relations, their properties, equivalence and order |
| 09 | [09_functions.ipynb](09_functions.ipynb) | Functions, domain/range, and bijections |
| 10 | [10_algorithms.ipynb](10_algorithms.ipynb) | Searching, sorting, and big-O complexity |
| 11 | [11_trees.ipynb](11_trees.ipynb) | Trees, traversals, Huffman coding, spanning trees |
| 12 | [12_graphs.ipynb](12_graphs.ipynb) | Graphs, traversal (BFS/DFS), shortest paths |
| 13 | [13_finite_state_machines.ipynb](13_finite_state_machines.ipynb) | Finite automata and state machines |
| 14 | [14_regular_languages.ipynb](14_regular_languages.ipynb) | Formal languages and Kleene's theorem |
| 15 | [15_counting.ipynb](15_counting.ipynb) | Combinatorics: permutations, combinations, counting |
| 16 | [16_ml.ipynb](16_ml.ipynb) | Capstone: where discrete math shows up in machine learning |
| 17 | [17_appendix_katex.ipynb](17_appendix_katex.ipynb) | Appendix: math notation (KaTeX) reference |

## Getting Started

You'll need **Python 3** and the packages listed in [`requirements.txt`](requirements.txt) (NumPy, Matplotlib, NetworkX, SymPy, scikit-learn, and Jupyter).

```bash
# 1. Clone the repository and enter it
git clone <repo-url>
cd discrete-structures

# 2. Create a virtual environment and install the dependencies
python3 -m venv .venv
source .venv/bin/activate          # on Windows: .venv\Scripts\activate
pip install -r requirements.txt

# 3. Launch Jupyter and open any notebook
jupyter lab                        # or: jupyter notebook
```

> Prefer [`uv`](https://github.com/astral-sh/uv)? Then `uv venv .venv` and `uv pip install -r requirements.txt`.

Open `00_introduction.ipynb` first, then work through the notebooks in order — each one is self-contained and can be run top to bottom.

## How to Use the Practice Problems

1. Read a notebook's concepts and worked examples.
2. Scroll to the **Practice Problems** section at the end and fill in the empty code cells.
3. Check your work against the matching key in [`solutions/`](solutions/) (for example, `solutions/01_sets_key.ipynb`).

## Repository Layout

```text
discrete-structures/
├── 00_introduction.ipynb ... 17_appendix_katex.ipynb   # the course notebooks
├── solutions/                                           # worked practice solutions (one key per notebook)
├── data/                                                # data files used by some notebooks
├── requirements.txt                                     # Python dependencies
└── README.md
```

## License

This work is licensed under the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). You are free to share and adapt the material — including for commercial use — as long as you give appropriate credit. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to all the contributors and students who helped get this off the ground!
