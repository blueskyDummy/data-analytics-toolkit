# CSCI 4047 — Data Analytics Toolkit (Python Starter)

A guided, hands-on path from "I've never written Python" to "I can load, clean, and explore real data." Built for this course, so it is small, ordered, and free of the giant datasets and extra chapters you don't need yet.

You do not need to read this whole file. Just go to **`00-quickstart/`** and open `hello_data.ipynb`. You'll be analyzing real data in about ten minutes.

---

## Who this is for

You, if any of these are true:
- You're taking CSCI 4047 and want extra practice outside class.
- You've seen Python once and it didn't stick.
- You can run a notebook cell but don't really know what each line does.

No prior programming is assumed. Every module explains the *why*, not just the *what*.

---

## How to use it

Each numbered module has two notebooks:

- **`learn.ipynb`** — read it top to bottom and run each cell. Short explanations sit between the code, so you always know what you're looking at.
- **`practice.ipynb`** — your turn. Blank cells with hint comments. Try each one before peeking.

Answers to every practice notebook live in **`SOLUTIONS/`**. Use them to check yourself, not to skip the thinking.

The golden rule: **run every cell, change a number, run it again, and see what happens.** You learn this by breaking it, not by reading it.

---

## The learning path

Work top to bottom. Each module builds on the one before.

| # | Module | You'll be able to... | Time |
|---|--------|----------------------|------|
| 00 | **Quickstart** | Load a real dataset and get your first insight | ~10 min |
| 01 | **Python Basics** | Use variables, types, conditions, and loops | ~45 min |
| 02 | **Data Structures** | Work with lists, dictionaries, and comprehensions | ~45 min |
| 03 | **NumPy** | Do fast math on whole arrays of numbers at once | ~45 min |
| 04 | **pandas Intro** | Hold data in DataFrames and select what you need | ~60 min |
| 05 | **Data Loading** | Read CSV, Excel, and other files into pandas | ~30 min |
| 06 | **Data Cleaning** | Handle missing values, duplicates, and messy labels | ~60 min |

By the end you can take a raw, messy CSV and turn it into clean data you can actually analyze, which is most of what real data work is.

---

## Setup (do this once)

You need **Miniconda** and **VS Code** with the Python and Jupyter extensions. If you set these up for class already, you're done, just use the same `analytics` environment.

**Build the environment** (from this folder, in Anaconda Prompt on Windows or Terminal on Mac):

```
conda env create -f environment.yml
conda activate analytics
```

Then open any notebook in VS Code and pick the **analytics** kernel in the top-right.

**No install? Use the browser instead.** Every notebook runs on [Google Colab](https://colab.research.google.com) with nothing to install: upload the notebook and the `data/` files, and go. Handy if your laptop is giving you trouble.

---

## A note on file paths

Notebooks read data with a path like `../data/tips.csv`. The `..` means "go up one folder" (out of the module folder) and then into `data/`. Keep the folder layout as-is and the paths just work, on any computer. Always use forward slashes `/`, even on Windows.

---

## Credits and license

The example code and the `tips.csv` dataset are adapted from **"Python for Data Analysis, 3rd Edition" by Wes McKinney** (O'Reilly), used under the MIT License. The full book is available free at <https://wesmckinney.com/book/>, and it's an excellent next step once you finish here.

Teaching narrative, exercises, and course structure are original material for CSCI 4047. See `LICENSE` for full terms.
