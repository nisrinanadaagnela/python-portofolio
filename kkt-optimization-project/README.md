# KKT Optimization Project (Coffee Production Case Study)

A group project applying the Karush-Kuhn-Tucker (KKT) method to optimize coffee production costs, consisting of two components: an interactive KKT solver tool, and a project scheduling analysis for the team's own workflow.

## What's in this folder

### 1. `kkt_solver_gui.ipynb` — KKT Optimization Solver with GUI

An interactive desktop application (built with Tkinter) that solves general constrained optimization problems using the KKT method. Allowing users to input their own objective function, variables, and constraints through a graphical interface, rather than solving one hardcoded problem.

Key features:
- Dynamic input fields for variables and constraints
- Symbolic computation of gradients and the Lagrangian using SymPy
- Automatic classification of constraints (equality vs. inequality)
- Displays the optimal solution and objective function value

This tool was used to solve our team's coffee production cost optimization case, but the solver itself is generalized and not limited to that use case.

**Note:** this uses Tkinter, which requires a local display to run. It works in a locally-run Jupyter Notebook, but will not run in Google Colab (no display access). Run it with Jupyter Notebook installed locally.

### 2. `pert_cpm_scheduling.ipynb` — Project Scheduling with PERT/CPM

A small utility using PERT (Program Evaluation and Review Technique) and CPM (Critical Path Method) to visualize and analyze our own team's task schedule for this project, and identify the critical path (the sequence of tasks where any delay would delay the entire project).

This was used practically to plan and visualize our team's task allocation and timeline, using our own tasks and team members as the input data.

## Tech stack

- Python
- Tkinter (GUI)
- SymPy (symbolic mathematics for solving KKT conditions)
- pertchart & graphviz (PERT diagram generation and visualization)

## How to run

- `kkt_solver_gui.ipynb` — open with a locally-installed Jupyter Notebook (not Colab) and run all cells; the GUI window will open separately.
- `pert_cpm_scheduling.ipynb` — can be run in Google Colab or Jupyter Notebook.

## Note

This was a group project built as part of an Optimization course.
