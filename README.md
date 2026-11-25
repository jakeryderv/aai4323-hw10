# AAI and DSAI 4323/5323 Lesson 10
## University of Oklahoma

This repository contains the files for the instruction and assignment for _Lesson 10: Exploratory Data Analysis for Fairness_.
The file I walked through in class is included here for you to run. It is _instructional_eda.ipynb_. This is a Jupyter notebook
you can run to see how the EDA routines work.

The second file is the code skeleton required to complete the assignment. It is _eda_homework.ipynb_.

__Assignment instructions:__
In this assignment, you will conduct a full fairness EDA on a dataset containing information on communities and crime.  You can use the EDA notebook from class as a guide.  Use the Jupyter notebook _instructional_eda.ipynb_.  The notebook gets you started by importing libraries for the work and to get the dataset.  It then reads in the data and sets up some variable sets.  You will enter code blocks to conduct the EDA.  Read through the entire notebook before beginning your work.

There are seven questions at the bottom of the notebook you must answer from your analysis.  The questions contain some tips on how to structure certain elements of your EDA.  There are also some hints to get started in the first open code block.

Save your notebook as _aai4323_hw10_<your name>.ipynb_.  Upload your completed notebook as a submission to this assignment.  It will be run for accuracy to check your code and your questions will be graded.  This assignment is worth 200 points.

## Local setup with uv

From the repository root, install the locked dependencies and open the working notebook:

```bash
uv sync --locked
uv run jupyter lab src/aai4323_hw10_Jake_Van_Slyke.ipynb
```

The project uses Python 3.12 and preserves the assignment's NumPy 1.26.4 and
pandas 2.1.4 pins. `pyproject.toml` declares the dependencies and `uv.lock`
records their resolved versions. `ucimlrepo` is installed in advance so the
starter notebook's import check does not need to install it at runtime.
Loading the dataset requires internet access.

In VS Code, select the repository's `.venv/bin/python` as the notebook kernel.
The original notebooks and Conda/devcontainer files are retained as supplied;
the uv setup above is the local workflow.
