# Contributing to Daily-System-Tools

Thanks for wanting to contribute! This repo is a collection of small, repeatable **system-programming tools** in **C and C++**, designed for learning real OS fundamentals (I/O, filesystems, processes, signals, networking, threading, etc.).

The golden rule: **small tools, clear docs, repeatable tests**.

---

## What you can contribute

- **New tool** (preferred): one focused utility that teaches one concept well.
- **Bug fixes**: correctness, edge cases, error handling, portability.
- **Docs**: improve tool READMEs, examples, syscall notes, diagrams.
- **Tests**: add missing test cases, improve repeatability.
- **Build improvements**: CMake/Makefile tweaks, CI improvements, sanitizers.

---

## Repo principles

- **One tool = one concept** (keep scope tight).
- **No heavy dependencies** (stick to standard C/C++ + OS APIs).
- **Good errors**: validate inputs, check return codes, print useful messages.
- **Repeatable**: every tool should have quick tests.
- **Readable**: clarity > cleverness.

---

## Project layout (recommended)

Tools live under `tools/` grouped by topic:
