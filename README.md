# wine-notebooks

A small Jupyter notebook showcase built around the `sklearn.datasets.load_wine` dataset.

## Included notebooks

### Static notebooks
- `notebooks/static/01_wine_overview_matplotlib.ipynb` - dataset overview and matplotlib charts
- `notebooks/static/02_wine_relationships_seaborn.ipynb` - seaborn pairplots, heatmaps, and boxplots

### Interactive notebooks
- `notebooks/interactive/03_wine_explorer_plotly_widgets.ipynb` - Plotly charts controlled with `ipywidgets`
- `notebooks/interactive/04_wine_apps_gradio_dash.ipynb` - notebook-friendly Gradio and Dash examples

## Setup

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook
```

Then open any notebook in the `notebooks/` directory.
