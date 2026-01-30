# IMDb Analytics Pipeline

Movie genre prediction project using NLP and machine learning. Pipeline includes IMDb data scraping, exploratory data analysis, and training multi-label classification models.

## Project Structure

```
├── data/                    # Data (movies, SBERT embeddings)
├── models/                  # Trained models and metrics
├── src/
│   ├── loaders/            # Scripts for data acquisition and preparation
│   ├── analysis/           # Exploratory data analysis (EDA)
│   ├── model_experiments.ipynb          # Model experiments with different embeddings
│   └── models_with_sbert_embedding.ipynb # Training models with SBERT embeddings
├── report.ipynb            # Final report with results
```

## Dependencies:

```bash
uv sync
```

