# Tic-Tac-Toe: Intuitive Analysis of Winning Possibilities in Higher Dimensions

An intuitive and combinatorial exploration of Tic-Tac-Toe across higher spatial dimensions ($d$), varying winning line lengths ($n$), and multi-player settings ($m \ge 3$).

## Contents
- `main.tex` — Complete LaTeX source with embedded TikZ diagrams.
- `HigherDimensional_TicTacToe.pdf` — Compiled exposition.
- `VGS_TicTacToe.ipynb` — PySAT (Glucose 4) script verifying $HJ_{\text{geom}}(3,2) = 3$ and $HJ(3,2) = 4$ and benchmarking $n \in \{3,4,5,6,7\}$.
- `hj_hardness_clean.png` — Runtime cliff and state-space growth benchmark plot.

## Interactive Notebook
Run the SAT cutoff benchmarks directly in Google Colab:
[Open in Google Colab](https://colab.research.google.com/drive/19WxN67aKqthGozfOnem2gmbXO08vpfFm?usp=sharing)
