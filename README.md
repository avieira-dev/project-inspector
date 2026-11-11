<div align="center">
    <h1>Project Inspector</h1>
    <p>A command-line tool for inspecting and analyzing software project structures and contents.</p>
    <p>
        <img src="https://img.shields.io/badge/version-v0.1.0-4c1?style=flat-square"/>
        <img src="https://img.shields.io/badge/status-in%20development-orange?style=flat-square"/>
        <img src="https://img.shields.io/badge/platform-Linux%20%2F%20macOS-FCC624?style=flat-square"/>
        <img src="https://img.shields.io/badge/language-Rust-000000?style=flat-square&logo=rust&logoColor=white"/>
        <img src="https://img.shields.io/badge/license-MIT-6e7781?style=flat-square"/>
    </p>
</div>

---

## Overview

**Project Inspector** is a command-line tool designed to inspect and analyze software project directories, providing useful insights into their structure, files, directories, and contents.

The goal is to help developers better understand their projects through organized reports, relevant metrics, and configurable analysis options.

---

## Table of Contents

- [Features](#features)
- [Installation](#installation)
    - [Clone the repository](#1-clone-the-repository)
    - [Build the project](#2-build-the-project)
    - [Run the application](#3-run-the-application)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Roadmap](#roadmap)
- [Author](#author)
- [License](#license)

---

## Features

- Identifies the **total count** and **detects empty directories**.
- Analyzes **file counts** and pinpoints the **largest and smallest files**.
- Calculates **directory sizes** to find the largest and smallest ones.
- Groups files by **extension** with quantity statistics.
- Calculates the **total size** of the analyzed root directory.
- Detects **Git version control** integration.
- Supports **custom exclusions** via `inspignore.txt`.
- Displays results via **formatted terminal reports** (tables, colors, and indicators).

---

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/avieira-dev/project-inspector.git
cd project-inspector
```

### 2. Build the project

```bash
cargo build --release
```

### 3. Run the application

```bash
cargo run
```

---

## Usage

> [!NOTE]  
> Usage instructions and available commands will be documented as the CLI interface is implemented.

---

## Project Structure

```text
project-inspector/
├── src/
│   └── main.rs
├── .gitignore
├── Cargo.lock
├── Cargo.toml
├── LICENSE
└── README.md
```

---

## Roadmap

| Feature                                    | Status                    |
|:-------------------------------------------|:--------------------------|
| Project directory inspection               | ░░░░░░░░░░░░░░░░░░░░ `0%` |
| File and directory statistics              | ░░░░░░░░░░░░░░░░░░░░ `0%` |
| File extension statistics                  | ░░░░░░░░░░░░░░░░░░░░ `0%` |
| Directory size analysis                    | ░░░░░░░░░░░░░░░░░░░░ `0%` |
| Empty directory detection                  | ░░░░░░░░░░░░░░░░░░░░ `0%` |
| Git version control detection              | ░░░░░░░░░░░░░░░░░░░░ `0%` |
| Content analysis                           | ░░░░░░░░░░░░░░░░░░░░ `0%` |
| Custom exclusions through `inspignore.txt` | ░░░░░░░░░░░░░░░░░░░░ `0%` |
| Organized terminal reports                 | ░░░░░░░░░░░░░░░░░░░░ `0%` |
| JSON report export                         | ░░░░░░░░░░░░░░░░░░░░ `0%` |
| TXT report export                          | ░░░░░░░░░░░░░░░░░░░░ `0%` |

---

## Author

**Alexandre Vieira**  
GitHub: [@avieira-dev](https://github.com/avieira-dev)

---

## License

Distributed under the [MIT License](LICENSE). See `LICENSE` for details.