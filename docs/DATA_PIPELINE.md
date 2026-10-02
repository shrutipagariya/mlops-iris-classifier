# MLOps Data Pipeline

## Overview

This project implements an end-to-end data pipeline using Python and DVC.

The pipeline contains four stages:

1. Collect
2. Preprocess
3. Features
4. Validate

The stages are connected using DVC dependencies and outputs.

## Pipeline Flow

```text
Collect
   ↓
Preprocess
   ↓
Features
   ↓
Validate