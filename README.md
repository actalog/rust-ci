# Rust CI

![GitHub Actions](https://img.shields.io/github/actions/workflow/status/actalog/rust-ci/ci.yml?branch=main)
![License](https://img.shields.io/github/license/actalog/rust-ci)

A GitHub Action to streamline Continuous Integration (CI) for Rust projects. This Action ensures code quality, builds, and tests your Rust project, maintaining high standards in Rust development.

---

## 🚀 **Features**

- **Automatic Builds:** Ensures your code compiles without issues.
- **Code Quality Checks:** Verifies adherence to Rust standards.
- **Automated Testing:** Runs tests to validate your project's functionality.
- **Plug-and-Play:** Easy to integrate into your existing Rust projects.

---

## 📦 **How to Use**

Add the following to your `.github/workflows/ci.yml`:

```yaml
name: CI

on:
  - pull_request
  - push

jobs:
  rust-ci:
    name: Rust CI
    runs-on: ubuntu-latest
    steps:
      uses: actions/checkout@v4
      uses: actalog/rust-ci@v1
```

---

## 🌟 **Why Use Rust CI?**

- Simplifies your CI/CD setup.
- Optimized for Rust projects.
- Saves time and enforces best practices.
- Continuously improves based on community feedback.

---

## 📜 **License**

This project is licensed under The Unlicense. See the [LICENSE](./LICENSE) file for details.
