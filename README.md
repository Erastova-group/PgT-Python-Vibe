# Python for Chemists: PgT Vibe Coding Session

This repository contains teaching material for a 3-hour introductory Python session for Chemistry postgraduate taught students.

The session is designed to help students read, run, adapt, and critically evaluate Python code in chemistry contexts. It also introduces "vibe coding": using an AI assistant to generate code, then testing, editing, and checking that the output makes chemical and computational sense.


## Session Overview

The notebook is structured as three blocks of approximately one hour each:

| Block | Topic | Focus |
| --- | --- | --- |
| 1 | Python fundamentals | Variables, data types, lists, loops, functions, imports, and plotting |
| 2 | Vibe coding with AI | Prompting an AI assistant, running generated code, debugging errors, and checking outputs |
| 3 | Mini-project | Applying Python and AI-assisted coding to a small chemistry problem |

Examples and exercises use chemistry-relevant problems such as:

- converting mass to moles
- classifying pH values
- plotting Beer-Lambert calibration curves
- using the ideal gas law
- generating titration curves
- processing calibration data with `pandas`


## Intended Audience

This material is aimed at Chemistry PgT students who may be new to programming. The goal is not to memorise Python syntax, but to build enough confidence to:

- run code in a notebook
- recognise the main parts of a Python script
- adapt examples for chemistry problems
- ask an AI assistant for useful code
- debug common errors
- evaluate whether results are chemically reasonable


## Recommended Environment

The notebook was developed for use in the Edina VS Code Notebook environment with a Python 3 kernel.

You can also run it locally if you have:

- Python 3.10 or later
- Jupyter Notebook, JupyterLab, or VS Code with notebook support
- the Python packages listed below


## Python Packages Used

The notebook uses common scientific Python libraries:

- `numpy`
- `matplotlib`
- `pandas`

If running locally, install them with:

```bash
python -m pip install numpy matplotlib pandas notebook
```

## How to Use the Notebook

1. Open `chemistry_python_intro.ipynb` in a notebook environment.
2. Select a Python 3 kernel if prompted.
3. Run cells with `Shift + Enter`.
4. Read the markdown instructions before running each code cell.
5. Edit the code cells as you work through the exercises.
6. For AI-assisted sections, paste the provided prompts into the AI helper and copy the useful code back into the notebook.
7. Check outputs carefully, especially units, assumptions, and chemical meaning.


## Working with AI-Generated Code

The AI-assisted parts of the session are built around a simple workflow:

1. Prompt the AI clearly.
2. Paste generated code into the notebook.
3. Run the code.
4. Read the result and any error messages.
5. Ask the AI to explain or fix problems.
6. Modify the code until it matches the chemistry question you actually want to answer.

Students are encouraged to treat AI output as a draft, not as a final answer. Code should be checked for:

- correct units
- sensible variable names
- appropriate equations
- realistic values
- readable plots
- accurate interpretation of results


## Suggested Teaching Use

For a 3-hour session, a possible rhythm is:

- 10 minutes: orientation and notebook setup
- 50 minutes: Block 1, Python fundamentals
- 10 minutes: short break
- 50 minutes: Block 2, AI-assisted coding tasks
- 10 minutes: short break
- 50 minutes: Block 3, student mini-projects and discussion

The notebook is intentionally editable. Students should copy, change, break, and repair code during the session.


## Development Notes

This repository is intentionally lightweight. The main teaching material lives in the notebook rather than in a Python package.

When updating the notebook:

- keep examples beginner-friendly
- prefer chemistry contexts over abstract programming examples
- include units in variable names or output where helpful
- keep AI prompts explicit and easy to copy
- avoid adding heavy dependencies unless they are essential for the teaching goal


## Author

Developed by Valentina Erastova, University of Edinburgh, June 2026.

Contact: valentina.erastova@ed.ac.uk
