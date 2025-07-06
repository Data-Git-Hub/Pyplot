# P3: Employ Matplotlib, Pyplot & Engage

[P3: Employ Matplotlib, pyplot & Engage ](https://github.com/Data-Git-Hub/Pyplot)

## Introduction
This project demonstrates foundational data visualization techniques using Python’s Matplotlib library, specifically the pyplot module. Through a series of guided tasks, I create and compare different types of visual charts—including scatter plots and line plots—by generating random data points with Python's random module or NumPy. These visualizations help reinforce core concepts in chart construction, data presentation, and the customization options available in Matplotlib. The project is executed in a Jupyter Notebook environment, using clean code and Markdown headings to document each step and response. The goal is to build both technical fluency in Matplotlib and an understanding of how to effectively present data in a visual format that is clear, accurate, and engaging. 

## Windows Setup Instructions

Open a PowerShell terminal in VS Code. 
Create local project virtual environment, activate it, and install packages. 
When asked to use the new .venv click yes. 

Important: Install from requirements first with scikit-learn commented out. 
Then remove the leading hashmark (around line 187) and re-run the command to install scikit-learn.
See requirements.txt for more information. 


```shell
py -m venv .venv
.\.venv\Scripts\activate
py -m pip install --upgrade pip setuptools wheel
py -m pip install -r requirements.txt
```
### Remove "#" TBD. from requirements.txt

```shell
py -m pip install -r requirements.txt
```

---

## macOS/Linux Setup Instructions

Open a default terminal in VS Code. 
Create local project virtual environment, activate it, and install packages. 
Important: Install from requirements first with scikit-learn commented out. 
Then remove the leading hashmark (around line 187) and re-run the command to install scikit-learn.
See requirements.txt for more information. 

```zsh
python3 -m venv .venv
source .venv/bin/activate
python3 -m pip install --upgrade pip setuptools wheel
python3 -m pip install -r requirements.txt
```

### Remove "#" TBD. from requirements.txt

```zsh
py -m pip install -r requirements.txt
```

---

## Tell VS Code to use .venv

Open the Command Palette: Press Ctrl + Shift + P (Windows) or Cmd + Shift + P (Mac/Linux)
Then type: Python: Select Interpreter
Press Enter.

Look for the interpreter with .venv in the path.
Click on that interpreter to select it.
Confirm it's selected: You should see the Python version and .venv path in the lower-left status bar of VS Code.

---

## Working on the Project

Open the .ipynb Jupyter notebook file in VS Code. 
Run the entire notebook before you start to edit. 
As you make progress, use Git to add, commit, and push your work to your GitHub repo.

```shell
git add .
git commit -m "describe the change here"
git push -u origin main
```

---

Export Using Jupyter Menu via VS Code was utilized for HTML exports.

---

### Introduction

### Imports

### Tasks

### Section 1. Character Frequency Visualization

### Section 2. Visualizing a Sequence of Random Prime Numbers

### Section 3. Restyled Scatter and Line Plots of Random Prime Numbers

### Section 4. Comparing Sorting Algorithm Performance

---

## Python Data Structures and Notebooks

Complete the tasks in the Python Notebook in this repository.
To be submitted for credit, all changes must be committed and pushed to this repository (do not create your own repository unless instructed to on the course website).

## Rubric

Each question is worth two points: 

* Data plotted as described by the question (1 pt)
* Plot contains required elements (title, axis labels, axis titles, legend if required)

---

## Authors

Contributors names and contact info <br>
@github.com/Data-Git-Hub <br>

---

## Version History
- P3 Finl - 0.0 - Create pyplot.html; Modify README.md
- P3 Sect - 4.0 - Modify pyplot.ipynb. README.md
- P3 Sect - 3.0 - Modify pyplot.ipynb. README.md
- P3 Sect - 2.0 - Modify pyplot.ipynb. README.md
- P3 Sect - 1.0 - Modify pyplot.ipynb. README.md
- P3 Init - 0.0 - Create pyplot.ipynb, requirements.txt; Modify README.md 
## Test History
- P3 Test - 1.0 - Execute pyplot.ipynb 