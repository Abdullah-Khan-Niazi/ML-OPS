# MLOps Architectures

A collection of hands-on MLOps implementations covering pipeline automation,
experiment tracking, and continuous integration. Each repository demonstrates
a focused MLOps concept applied to a real machine learning workflow.

---

## Table of Contents

- [Overview](#overview)
- [Repositories](#repositories)
  - [Makefile Automation](#makefile-automation)
  - [Experiment Tracking with MLflow](#experiment-tracking-with-mlflow)
  - [CI/CD with GitHub Actions](#cicd-with-github-actions)

---

## Overview

This repository serves as a navigation hub for three standalone MLOps projects.
Together they cover the core pillars of a production-ready ML workflow: reproducible
pipeline automation, experiment versioning and model registry management, and
automated testing through continuous integration. Each project is self-contained
with its own codebase, dependencies, and documentation.

---

## Repositories

### Makefile Automation

[ML-OPS-Makefile-Automation](https://github.com/Abdullah-Khan-Niazi/ML-OPS-Makefile-Automation)

An end-to-end reproducible machine learning pipeline for Titanic survival
prediction, controlled entirely through GNU Make. The pipeline automates every
stage from data ingestion through preprocessing, feature engineering, model
training, prediction, and evaluation. Running a single command executes the
complete workflow, ensuring full reproducibility across environments.

**Key concepts:** Pipeline automation, reproducibility, GNU Make, Scikit-learn.

---

### Experiment Tracking with MLflow

[ML-OPS-MLFLOW](https://github.com/Abdullah-Khan-Niazi/ML-OPS-MLFLOW)

A complete MLflow experiment lifecycle implementation using the Iris dataset.
Covers multi-run experiment tracking across Logistic Regression and Random
Forest classifiers, artifact logging, model comparison, payload validation
before inference, and model registration in the MLflow Model Registry.

**Key concepts:** Experiment tracking, artifact logging, model registry,
model selection, MLflow.

---

### CI/CD with GitHub Actions

[ML-OPS-Github-Actions](https://github.com/Abdullah-Khan-Niazi/ML-OPS-Github-Actions)

A Python library implementing basic math operations with a fully automated
testing and continuous integration workflow. Every push and pull request
triggers a GitHub Actions pipeline that runs the pytest test suite, ensuring
code correctness is verified automatically on every change.

**Key concepts:** Continuous integration, automated testing, GitHub Actions,
pytest.

---

## Tech Stack

| Tool | Purpose |
|---|---|
| GNU Make | Pipeline automation and reproducibility |
| MLflow | Experiment tracking and model registry |
| GitHub Actions | Continuous integration and automated testing |
| Python | Implementation language across all projects |
| Scikit-learn | Machine learning models and evaluation |
| pytest | Unit testing |
