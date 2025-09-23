# Copilot Instructions for AI Coding Agents

## Project Overview
This project appears to be a Jupyter notebook-based workflow for astronomy data science coursework (ASTR 496). The main artifacts are `.ipynb` files, with code, analysis, and documentation embedded in notebook cells. There is no detected build system, test suite, or conventional Python package structure.

## Key Patterns & Conventions
- **Notebook-centric development:** All code, documentation, and results are maintained in Jupyter notebooks. Python scripts or modules are not present.
- **Cell-based execution:** Code is executed in discrete cells. State is maintained in the notebook kernel. Avoid assumptions about global state outside the notebook.
- **Data analysis focus:** Expect code to use scientific Python libraries (NumPy, pandas, matplotlib, astropy, etc.).
- **Directory structure:** Notebooks are organized by week and topic. Example: `lecture/04/p2/week04.ipynb`.
- **No explicit tests/builds:** There are no test files, CI configs, or build scripts. Validation is manual via notebook cell output.

## AI Agent Guidance
- **When adding code:** Insert new cells rather than editing existing ones unless explicitly asked. Use markdown cells for explanations and context.
- **When refactoring:** Prefer cell-level changes. If restructuring, preserve the logical flow of the notebook.
- **When debugging:** Use print statements or cell outputs for diagnostics. There is no integrated debugger.
- **When installing packages:** Use notebook magic commands (`!pip install ...`) or ensure package installation via notebook tools.
- **When documenting:** Use markdown cells for explanations, equations, and context. Follow the style of existing cells.

## Examples
- To add a new analysis step, insert a Python code cell after the relevant section.
- To explain a concept, insert a markdown cell with a heading and description.
- To visualize data, use matplotlib or similar libraries in a code cell.

## External Dependencies
- Standard scientific Python stack (NumPy, pandas, matplotlib, astropy, etc.).
- No custom modules or external APIs detected.

## Directory References
- Notebooks: `lecture/04/p2/week04.ipynb` (and similar)

---
_If you discover new conventions or workflows, update this file to keep instructions current._
