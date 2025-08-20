# Initial Commits

This repository is a curated collection of initial commits from classic open-source projects including Golang, Python, PHP, and more. It serves as a tribute to these foundational projects and provides developers with the opportunity to start their own repositories from the same humble beginnings as these legendary codebases.

## Purpose

Many great open-source projects started with a simple, clean initial commit. This repository preserves those historical first steps, allowing developers to:

- Learn from the foundational architecture of classic projects
- Start new projects with the same clean slate as industry-standard software
- Pay homage to the open-source pioneers
- Study the evolution of software development through these initial codebases

## Available Projects

The initial commits of classic projects are organized in separate branches:

- **Hello World**: The first commit of `hello, world`
  - Branch: [`hello-world`](https://github.com/aahl/initial-commit/tree/hello-world)
- **Golang**: The first commit of the Go programming language
  - Branch: [`golang`](https://github.com/aahl/initial-commit/tree/golang)
- **Python**: The initial commit of the Python programming language
  - Branch: [`python`](https://github.com/aahl/initial-commit/tree/python)
- **NodeJS**: The first commit of the NodeJS programming language
  - Branch: [`nodejs`](https://github.com/aahl/initial-commit/tree/nodejs)
- **PHP**: The first commit of the PHP programming language
  - Branch: [`php`](https://github.com/aahl/initial-commit/tree/php)

## How to Use

### Starting a New Project from a Classic Initial Commit

1. **Clone the specific branch** of your desired classic project:
   ```bash
   git clone -b golang https://github.com/aahl/initial-commit.git my-go-project
   cd my-go-project
   ```

2. **Remove git remote**:
   ```bash
   git remote remove origin
   git remote add origin <your-new-repo-url>
   ```

3. **Initialize your new project**:
   ```bash
   git checkout -b main
   git add .
   git commit -m "Your initial commit"
   ```

### Browsing Historical Initial Commits

Switch between branches to explore different starting points:
```bash
git checkout golang
git checkout python
git checkout nodejs
git checkout php
```

## Acknowledgments

This project is a tribute to the countless developers who contributed to these foundational open-source projects. Their work has shaped the software development landscape and continues to inspire new generations of programmers.
