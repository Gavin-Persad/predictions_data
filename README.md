# predictions_data

This repository contains data and analysis for the football score predictions app. The goal is to explore the historical predictions and results collected by the app and produce interesting, shareable statistics and visualisations for the community (for example, for weekly newsletters and an end-of-season trivia recap).

## What this project is for

- Collect, clean, and explore the predictions and results data exported from the app.
- Produce visualisations and summary statistics to share in weekly newsletters and at season-end.
- Provide an open-source place for others to reproduce the analyses or run the competition with their own group.

## Repository structure

- `CSV/` — raw or exported CSV files from the app (predictions, match results, user metadata, etc.).
- `Notebooks/` — exploratory and production Jupyter notebooks that load the CSVs, run analyses, and create visuals for the newsletter.

## Tech stack

- Python 3.11
- pandas, numpy — data handling and processing
- matplotlib, seaborn — plotting and visualisation
- Jupyter Notebook / JupyterLab — interactive analysis and figure generation

## Quick start (Windows PowerShell)

1. Create and activate a virtual environment (optional but recommended):

```powershell
python -m venv .venv
.\.venv\Scripts\Activate
```

2. Install the main packages used in the project (or use an existing `requirements.txt` if present):

```powershell
pip install pandas numpy matplotlib seaborn jupyter
# or, if you have a requirements.txt:
pip install -r requirements.txt
```

3. Launch Jupyter and open notebooks in `Notebooks/`:

```powershell
jupyter notebook
# or
jupyter lab
```

4. Run the notebooks to reproduce analysis and export figures to share in the newsletter.


## Contributing

Contributions are welcome. If you'd like to propose changes or add analyses:

1. Fork the repo and create a feature branch.
2. Add or update notebooks under `Notebooks/` and keep large generated images out of Git where possible (commit them to releases or an outputs folder if necessary).
3. Open a pull request describing the new analysis or visualisation and include sample outputs.

This project is open-source; the app is also on GitHub — feel free to play the competition with your own group and submit interesting statistics back to this repo.
