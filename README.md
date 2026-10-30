# Multi-cancer image CNN

An early TensorFlow convolutional classifier on the ALL subset of a multi-cancer image dataset.

## Notebooks

- [cancer-cnn.ipynb](notebooks/cancer-cnn.ipynb) — [original Kaggle notebook](https://www.kaggle.com/code/thorballer/cancer-cnn)

This uses the ALL subset, not every cancer class. It is an educational classifier, not a clinically validated diagnostic tool.

## Running

Open the original Kaggle notebook, attach its referenced data/models, choose the hardware expected by its setup cells, and run cells in order. Review install, login, and file-writing cells first.

For local use, install `requirements.txt` and adapt `/kaggle/input` paths. Dependencies are inferred from imports, not a tested lockfile; older APIs may need adjustment.

### Referenced Kaggle datasets

- [obulisainaren/multi-cancer](https://www.kaggle.com/datasets/obulisainaren/multi-cancer)

## Status and source

These exports have no saved execution outputs. Training was not rerun, so this archive reports no benchmark scores.

Daniel Goldberg's Kaggle notebooks are preserved with source links and hashes in [PROVENANCE.json](PROVENANCE.json). Documentation was added for this archive.

Original comments, credits, and tutorial links are retained. Datasets and dependencies have their own licenses; no new blanket license is assigned.
