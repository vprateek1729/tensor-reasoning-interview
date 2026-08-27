# Tensor Puzzles Interview

A candidate-ready PyTorch notebook containing 21 tensor broadcasting and
indexing exercises. Each exercise includes an imperative specification,
generated examples, an implementation stub, and a property-based test.

## Open in Google Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/vprateek1729/tensor-reasoning-interview/blob/main/Tensor%20Puzzlers.ipynb)

Run the first two notebook cells before starting. They install the notebook
dependencies and download `lib.py` from this repository.

## Run on a desktop

```bash
git clone https://github.com/vprateek1729/tensor-reasoning-interview.git
cd tensor-reasoning-interview
python3 -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
jupyter notebook "Tensor Puzzlers.ipynb"
```

When running from a clone, `lib.py` is already present. The setup cell may still
be run to ensure dependencies are installed and the helper file is current.

## Candidate rules

1. Solve each exercise with broadcasting and indexing.
2. Keep each solution to one line of fewer than 80 characters.
3. You may use `@`, arithmetic, comparison, `shape`, indexing, `arange`,
   `where`, and functions completed in earlier exercises.
4. Do not use tensor convenience operations such as `view`, `sum`, `take`,
   `squeeze`, or `tensor` in exercise solutions.

See `LICENSE` for licensing information.
