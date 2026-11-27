# Week 1: Optimization, Linear Regression and Gradient Descent

## Learning goals

By the end of this week you should be able to:

- Describe an optimization problem and solve a small linear program graphically
- Explain why convexity matters
- Derive the closed-form solution for linear regression
- Connect squared error to maximum likelihood
- Implement gradient descent and choose a learning rate
- Use NumPy and Matplotlib for basic numerical work

## Contents

| File | What it is |
|---|---|
| [`reading/week1_notes.pdf`](reading/week1_notes.pdf) | Reading notes with practice problems and answers |
| [`notebooks/01_numpy_matplotlib_primer.ipynb`](notebooks/01_numpy_matplotlib_primer.ipynb) | NumPy and Matplotlib primer |
| [`notebooks/02_line_fitting.ipynb`](notebooks/02_line_fitting.ipynb) | Closed form vs gradient descent |

## Suggested plan (about 6 hours)

| Step | Task | Time |
|---|---|---|
| 1 | Python tools: tutorials below and the primer notebook | 1.5 h |
| 2 | Notes sections 1–4 and the linear programming video | 1 h |
| 3 | Notes sections 5–6 and the regression videos | 1.5 h |
| 4 | Notes section 7 and the gradient descent video | 0.5 h |
| 5 | Line-fitting notebook and exercises | 1.5 h |

## Videos

**Linear algebra refresher (optional, not included in the time above)**
- [3Blue1Brown: Essence of Linear Algebra](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab)

**Optimization**
- [Linear Programming: maximization and corner points](https://www.youtube.com/watch?v=0TD9EQcheZM)

**Linear regression**
- [StatQuest: Fitting a line to data (least squares)](https://youtu.be/PaFPbb66DxQ)
- [StatQuest: Linear Regression](https://youtu.be/7ArmBVF2dCs)
- [StatQuest: Maximum Likelihood](https://youtu.be/XepXtl9YKwc)

**Gradient descent**
- [StatQuest: Gradient Descent, Step-by-Step](https://youtu.be/sDv4f4s2SB8)

## Learn NumPy and Matplotlib

- [NumPy: the absolute basics for beginners](https://numpy.org/devdocs/user/absolute_beginners.html)
- [NumPy quickstart](https://numpy.org/devdocs/user/quickstart.html)
- [Matplotlib quick start guide](https://matplotlib.org/stable/users/explain/quick_start.html)

## Further reading

- [Mathematics for Machine Learning](https://mml-book.github.io/)

## Setup

Run locally:

```bash
pip install numpy matplotlib notebook
jupyter notebook
```

Or upload the notebooks to Google Colab, which needs no installation.

## Checklist

- [ ] Read the notes and attempt the practice problems before checking the answers
- [ ] Complete the primer exercises
- [ ] Run the line-fitting notebook and complete its exercises
