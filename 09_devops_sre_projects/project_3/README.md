# Project: Canary Deployment Validator

## Description
Compare baseline and canary version metrics to automate deployment decisions.

## Key Features:
- Pull Prometheus metrics for baseline and canary
- Perform statistical comparison (t-test, error budget)
- Approve/abort rollout via webhook or CLI

## Tech Stack:
- Python, Prometheus API, NumPy, argparse
