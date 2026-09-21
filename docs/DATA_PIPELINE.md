# Data Pipeline Documentation

## Purpose

This pipeline collects the Iris dataset, preprocesses the data,
creates additional features, and validates the final dataset
before it is used for downstream machine learning tasks.

## Pipeline Flow

```text
Collect
   ↓
Preprocess
   ↓
Feature Engineering
   ↓
Validate