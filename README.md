# Rust CI

This repository contains the configuration for a Continuous Integration (CI) pipeline for Rust projects. The pipeline is designed to ensure that the code is checked for compilation errors, follows best coding practices, builds successfully, and passes automated tests.

## Using This Action in Your Workflow

To use this CI configuration in your workflow, include it as follows in your CI file:

```yaml
name: CI

on:
  - push

jobs:
  rust-ci:
    name: Rust CI
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      - uses: actalog/rust-ci@main
```
