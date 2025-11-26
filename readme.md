# Survey Variable Selector & Merge Script Generator

> ⚠️ **Beta Version - Work in Progress**  
> This tool is currently under active development. Features may change and bugs may exist.

A simple, browser-based tool to help researchers and data analysts select variables from a survey data dictionary and generate data merging scripts.

This tool is designed to work with a `lookup.csv` file, which acts as a master data dictionary for a project.

**Note:** Currently, the tool loads **BCS70 (British Cohort Study 1970)** data by default. Future versions could be generalised to support other longitudinal studies (e.g., other CLS cohorts like MCS or NCDS, Understanding Society, etc.).

---

## Demo

![Demo animation](demo.gif)


---

## Core Features

* **Load & Browse:** Upload a `lookup.csv` file to view all available variables in an interactive table.
* **Select & Filter:** Interactively search, filter, and select the specific variables you need for your analysis.
* **Generate Code:** Instantly generate ready-to-use data merging scripts for **Stata, R, and Python**.

---

## How to Use

1. Download the `index.html` file.
2. Open the file directly in your web browser.
3. Click **Choose lookup.csv** to load your lookup.csv and begin.

**Note on Data Structure:**  
The generated scripts assume your datasets are organized into subfolders (e.g., by age, wave, or topic), as specified in your `lookup.csv` file.  
See [CLS Data Handling Documentation](https://cls-data.github.io/docs/intro.html).