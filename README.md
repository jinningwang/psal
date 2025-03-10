# Power System Analysis with LTB

[![License: GPL-3.0](https://img.shields.io/badge/License-GPL--3.0-blue.svg)](https://github.com/jinningwang/psal/blob/master/LICENSE)
![Repo Size](https://img.shields.io/github/repo-size/jinningwang/psal)
[![GitHub last commit (master)](https://img.shields.io/github/last-commit/jinningwang/psal/master?label=last%20commit%20to%20master)](https://github.com/jinningwang/psal/commits/master/)
[![HitCount](https://hits.dwyl.com/jinningwang/psal.svg)](https://hits.dwyl.com/jinningwang/psal)

Jinning's personal repository for power system analysing using LTB.

# Table of Content

1. [AMS DCOPF Benchmark](./src/notes/ltb_benchmark/ams_benchmark.ipynb), benchmark of AMS DCOPF.
1. [ANDES PFlow Benchmark](./src/notes/ltb_benchmark/andes_benchmark.ipynb), benchmark of ANDES power flow.
1. [Power Flow Comparasion](./src/notes/pflow_benchmark/pflow_compare.ipynb), compare power flow results cross different solvers.
1. [Frequency Regulation with IBR](./src/notes/agc/agc_ibr.ipynb), from SFR capacity procurement in real-time economic dispatch to detailed AGC action in time-domain simulation.
1. [Discussion 386](./src/notes/discussion/d386.ipynb), details on ANDES Discussion #386, TDS init error.
1. [Discussion 471](./src/notes/discussion/d471.ipynb), details on ANDES Discussion #471, line injected power.

# FAQ

Q: Why are my local running results different from yours?

A: There can be three possible reasons: 1) changes in the case files, 2) changes in the code, 3) differences in the versions of key packages.

# Release Notes

This repository uses setuptools_scm as versioning.
Check [Tags](https://github.com/jinningwang/psal/tags) for more details.

Check the version by running:

```bash
python -m setuptools_scm
```

### v0.0.3
Prepare 2024 LTB demo data.

### v0.0.2
Add two ANDES discussions notes: Discussion #386 and Discussion #471.

### v0.0.1
Initial release.
