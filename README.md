# micrograd (minimal)

A compact educational implementation of automatic differentiation and a tiny neural network (micrograd).

This repository contains:

- engine.py — small autodiff Value implementation
- nn.py — simple Neuron / Layer / MLP classes using Value
- test.ipynb, micrograd.ipynb — example notebooks demonstrating features and an interactive drawing demo

Quick start

1. Create and activate a Python environment (recommended):

   python -m venv .venv
   .\.venv\Scripts\activate # Windows

2. Install dependencies:

   pip install -r requirements.txt

   If you prefer manual installs:
   pip install numpy matplotlib ipywidgets

3. Open the example notebook in Jupyter or JupyterLab and run the cells:

   jupyter lab

   # or

   jupyter notebook

   Then open `micrograd.ipynb` or `test.ipynb`.

Running the small tests

The `test.ipynb` notebook runs a handful of checks (value arithmetic, gradient checks, a tiny MLP training loop) — run it to verify the implementation.

Interactive drawing demo

`test.ipynb` contains an interactive drawing + fitting demo. For best interactivity install ipympl:

pip install ipympl

and use a notebook server that supports widgets (JupyterLab with the ipywidgets extension or classic notebook).

Contributing

This is an educational repo — contributions and improvements are welcome. Please open issues or pull requests with small focused changes.

License

MIT License.
