# DTI Assignment 2: Define Stage (Group 10)

Define Stage report for the IIITA Registration Experience project (Design Thinking, BTech V Semester).

## Contents

- `source/`: Python generator for the report (`a2.py`), shared styles and helpers (`common.py`, `ai_section.py`), and the build pipeline (`build.py`, `render.sh`, `pdftext.swift`)
- `visual-artifacts/`: customer journey maps for the four personas (Ananya, Kabir, Meera, Rohan)
- `report/`: the rendered report PDFs

## Building

Needs Python 3, Google Chrome and Swift (macOS).

```bash
python3 source/build.py a2
```

The output is written to `source/build/a2.pdf`.
