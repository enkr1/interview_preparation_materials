# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

This is a **personal interview preparation and study materials library** - not a software project. It contains technical books, PDFs, and reference materials for computer science topics.

## Structure

| Directory | Content |
|-----------|---------|
| Root | Core CS books (System Design, DDIA, Cracking the Coding Interview, DDD, etc.) |
| `Discrete/` | Discrete mathematics, graph theory, combinatorics, logic |
| `Computer Graphics/` | OpenGL and computer graphics textbooks |
| `Cryptography and network security/` | Cryptography fundamentals (Stallings, Forouzan) |
| `Database Internals.pdf` | Database implementation details |
| `image processing/` | Digital image processing textbooks |
| `Machine learning (dawood sir)/` | Pattern recognition, ML fundamentals |
| `System programming/` | UNIX/Linux system programming (APUE) |
| `Theory of computation and complexity theory/` | Automata, computability |
| `Wireless and Mobile communication/` | Wireless networking (Rappaport) |
| `Qt programming/` | Sample Qt4 signal/slots code |
| `UnixShellScripts/` | Basic shell script examples |

## Code Samples

### Qt Programming
Compile on Linux with Qt4:
```bash
cd "Qt programming"
qmake-qt4 -project main.cpp
qmake-qt4 hello.pro
make
./hello
```

### Shell Scripts
Located in `UnixShellScripts/` - basic examples (factorial, primality, area calculation).

## Adding New Books

1. **Add file** to correct folder (or root for core books)
2. **Update `index.html`** - add entry under the right category:
   ```html
   <span class="item"><a href="https://github.com/enkr1/interview_preparation_materials/blob/master/FOLDER/FILENAME.pdf">Display Name</a></span>
   ```
   - URL-encode spaces as `%20` and special chars
3. **Commit & push**

## GitHub Pages

Library page: `https://enkr1.github.io/interview_preparation_materials/`

Settings: repo → Settings → Pages → Source: master branch, root folder

## Working with This Repo

- Primary use: Reference lookup and study
- When asked about interview topics, relevant PDFs can be read for context
- Code samples are educational examples, not production code
