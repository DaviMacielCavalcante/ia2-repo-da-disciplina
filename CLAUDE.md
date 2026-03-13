# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a machine learning course repository (IA2 - Inteligência Artificial 2) focused on neural networks and deep learning using TensorFlow/Keras and scikit-learn.

## Development Commands

```bash
# Install dependencies (uses uv package manager)
uv sync

# Run Jupyter notebook
uv run jupyter notebook

# Run a Python script
uv run python <script.py>
```

## Tech Stack

- **Python 3.12** with uv for dependency management
- **TensorFlow/Keras** for deep learning models
- **scikit-learn** for ML utilities (preprocessing, metrics, train/test splits)
- **SciKeras** for scikit-learn compatible Keras wrappers
- **matplotlib** for visualization
- **Jupyter notebooks** for experimentation

## Architecture

The repository contains Jupyter notebooks for ML experiments. The typical workflow follows:
1. Data loading (e.g., sklearn datasets)
2. Preprocessing with StandardScaler
3. Train/test split
4. Neural network model building with Keras Sequential API
5. Training and evaluation with confusion matrices and classification reports
