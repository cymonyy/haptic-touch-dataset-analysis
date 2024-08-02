# Contributing to haptic-touch-dataset-analysis

First, thank you for taking the time to contribute to our project! This guide will help you start contributing to our project.

## Code of Conduct

By participating in this project, you agree to abide by our [Code of Conduct](CODE_OF_CONDUCT.md). Please read it to understand the behavior expectations in our community.

## Getting Started

To get started, you'll need to fork the repository, clone your fork, and set up your local development environment.

### Fork the Repository

1. Navigate to the main repository on GitHub.
2. Click the "Fork" button in the upper right corner of the repository page.

### Clone Your Fork

```
git clone https://github.com/your-username/your-forked-repo.git
cd your-forked-repo
```

### Install and Open Notebook
Install [Jupyter Lab](https://jupyterlab.readthedocs.io/en/stable/getting_started/installation.html)

Open through either
- [command line](https://jupyterlab.readthedocs.io/en/stable/getting_started/starting.html) or the
- [Anaconda Navigator](https://www.anaconda.com/download).

## How to Contribute

### Reporting Bugs
If you find a bug, please report it by creating an issue in the tracker. Please include as much detail as possible.

### Suggesting Enhancements
We'd like to hear suggestions for new features or improvements. Please submit these as issues in the issue tracker.

### Contributing Code
1. **Check for existing issues:** Before you start working on a feature or bug, check if an issue is already addressed. If there is, and you want to contribute, please feel free to comment on the issue so we know you're working on it.
2. **Create a new branch:** Create a new branch for your work:

```git checkout -b develop/your-feature-name```

4. Write and test your code: Make changes to the Jupyter Notebook and ensure it runs without errors. Please make sure to document your changes as necessary.

### Style Guidelines
- **Jupyter Notebooks:** Please make sure that the notebooks are clean and organized. Please remove any unnecessary cells or outputs before committing.
- **Code Quality:** Follow PEP 8 guidelines for Python code. You can use meaningful variable names and include comments where necessary.
- **Documentation:** Update the README.md and any relevant documentation with details of changes to the interface, new features, or new usage instructions.

### Commit Message Guidelines
- Keep your commit messages concise but descriptive.
- Reference issues and pull requests in your commit messages when applicable (e.g., "Fixes #123").

### Pull Request Process
1. Ensure that your branch is up to date:
```
git fetch origin
git rebase origin/main
```
2. Push to your branch:
```
git push origin develop/your-feature-name
```
3. **Create a pull request:** Go to the repository on GitHub and create a pull request from your branch. Fill out the pull request template and provide a clear description of what you have done.
4. **Address Feedback:** Be prepared to make changes based on reviewer feedback.

## Thank you for your contributions!
