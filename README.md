SolidWorks Parts & STL Models

> A collection of mechanical part files in native SolidWorks format and STL format, with project documentation.

![Project type](https://img.shields.io/badge/Project-3D%20Models-526B66?style=flat-square)
![CAD](https://img.shields.io/badge/CAD-SolidWorks-DF806A?style=flat-square)
![Formats](https://img.shields.io/badge/Formats-SLDPRT%20%7C%20STL-26313B?style=flat-square)

## Contents

- [Project overview](#project-overview)
- [Repository structure](#repository-structure)
- [File formats](#file-formats)
- [Getting started](#getting-started)
- [Documentation](#documentation)
- [Notes](#notes)

## Project overview

This repository organizes the project's 3D part files in two formats: editable SolidWorks part files (`.SLDPRT`) and STL mesh files (`.STL`). The documentation folder contains the project PDF.

> Add a short description here explaining what the parts are for and how they fit into the overall project.

## Repository structure

```text
.
├── 01_SolidWorks_Parts/
│   ├── Part_1.SLDPRT
│   ├── Part_2.SLDPRT
│   ├── Part_5.SLDPRT
│   ├── Part_6.SLDPRT
│   └── Part_Extra.SLDPRT
├── 02_STL_Models/
│   ├── Part_1.STL
│   ├── Part_2.STL
│   ├── Part_3.STL
│   ├── Part_4.STL
│   └── Part_5.STL
└── 03_Documentation/
    └── CNC_PCB_Machine.pdf
```

## File formats

| Format | Use |
|---|---|
| `.SLDPRT` | Native SolidWorks part file. Use it to inspect or edit the model and its features. |
| `.STL` | 3D mesh export, commonly used in slicers, mesh tools, and 3D printing workflows. |
| `.PDF` | Project documentation and reference material. |

## Getting started

1. Open a `.SLDPRT` file in SolidWorks to view or edit its model.
2. Open an `.STL` file in a compatible mesh viewer or slicer to inspect the exported geometry.
3. Read [`CNC_PCB_Machine.pdf`](03_Documentation/CNC_PCB_Machine.pdf) for the project reference.

## Documentation

The project reference document is available at [`03_Documentation/CNC_PCB_Machine.pdf`](03_Documentation/CNC_PCB_Machine.pdf).

## Notes

- The folder and file names above follow the project structure shown in the supplied reference.
- Confirm that each STL export matches its intended SolidWorks part before manufacturing or sharing it.
- Add model-specific details such as units, dimensions, print orientation, or material when those requirements are known.

---

*Update this README as the model set and project documentation grow.*
