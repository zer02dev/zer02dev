---
title: BimmerDaten
tags: python pyqt6 bmw ediabas reverse-eng
status: active
repo: https://github.com/zer02dev/bimmerdaten
---

# BimmerDaten

PyQt6 desktop tool for parsing and analysing BMW NCS Expert, EDIABAS jobs files and decoding SA/FA codes.

Lets you browse coding data, module parameters, ECU definitions, code modules and decode SA/FA without needing to run BMW Tools itself.

## features

- Parse and display NCS Expert job files
- Browse EDIABAS .prg / .grp definitions
- Code modules like GM5, IHKA etc.
- And more - see github repo :)

## tech

- Python 3.11+
- PyQt6
- Custom EDIABAS parser

## status

Active development. Used daily for E36/E46 coding sessions.

## install

Download the latest [realese](https://github.com/zer02dev/bimmerdaten)

```bash
git clone https://github.com/zer02dev/bimmerdaten
cd bimmerdaten
pip install -r requirements.txt
python main.py
```
