# Customer Churn EDA - Hands-On README

This folder contains the files required for the **Customer Churn EDA hands-on exercise**.

## Folder Contents

```text id="f4v90p"
Hands-On/
│
├── customer_churn.csv
│
└── customer_churn_eda_template.ipynb
```

## 1. customer_churn.csv

`customer_churn.csv` is the **dataset** you will use for this hands-on exercise.

The dataset contains the data required to complete the Customer Churn Exploratory Data Analysis (EDA).

Please keep this file in the same working folder as the EDA template so that the notebook can load the dataset correctly.

## 2. customer_churn_eda_template.ipynb

`customer_churn_eda_template.ipynb` is the **hands-on Jupyter Notebook template**.

Open this notebook in **Jupyter Notebook or VS Code** and complete the exercises provided in it.

The notebook contains:

- Instructions for each exercise
- Markdown cells explaining what you need to do
- Variable names that you should use
- Areas where you need to write and execute your Python code

# Important - Use the Variable Names Provided

Throughout the notebook, the **Markdown instructions provide specific variable names** for different tasks.

### Do NOT change these variable names.

For example, if the Markdown instruction asks you to store a result in:

```python id="utw7u8"
churn_rate
```

you should use exactly:

```python id="h5fujj"
churn_rate = ...
```

Do not change it to something like:

```python id="6yeb2u"
rate = ...
```

or:

```python id="yx24vg"
customer_churn_rate = ...
```

### Why Is This Important?

The exercises are designed using the variable names provided in the Markdown instructions.

Using the same variable names will:

- Keep your code consistent with the exercise.
- Make it easier to follow the notebook instructions.
- Ensure later cells can use variables created in earlier steps.
- Prevent errors caused by missing or differently named variables.

> **Important:** Whenever a variable name is mentioned in a Markdown instruction, copy and use that **exact same variable name in your code**.

# How to Start the Hands-On Exercise

### Step 1 - Keep Both Files Together

Make sure you have:

```text id="kekv7d"
customer_churn.csv
customer_churn_eda_template.ipynb
```

in your working folder.

### Step 2 - Open the Notebook

Open:

```text id="db7p03"
customer_churn_eda_template.ipynb
```

using either **Jupyter Notebook** or **VS Code**.

### Step 3 - Read Each Markdown Instruction

Before writing any code, carefully read the Markdown cell above the exercise.

The Markdown cell will explain:

- What analysis you need to perform.
- Which column(s) to use.
- What result is expected.
- Which variable name you should use.

### Step 4 - Write Your Code

Write your solution in the code cell provided below the instruction.

**Use exactly the variable name specified in the Markdown cell.**

### Step 5 - Run and Check Your Code

Run the code cell and check the output before moving to the next exercise.

Some later exercises may depend on variables or results created earlier in the notebook.

# Recommended Workflow

```text id="3akb0q"
Read the Markdown instruction
          ↓
Identify the variable name provided
          ↓
Write your Python/Pandas code
          ↓
Use the SAME variable name
          ↓
Run the cell
          ↓
Check the output
          ↓
Continue to the next exercise
```

# Quick Reference

| File | Purpose |
|---|---|
| `customer_churn.csv` | Dataset for the Customer Churn EDA hands-on exercise |
| `customer_churn_eda_template.ipynb` | Jupyter Notebook template containing the EDA exercises |

# Important Reminders

**Use `customer_churn.csv` as your dataset.**

**Complete your work inside `customer_churn_eda_template.ipynb`.**

**Read the Markdown instructions carefully before writing your code.**

**Do not rename the variables provided in the Markdown cells. Use exactly the same variable names in your code.**

**Run the notebook in sequence from top to bottom**, as later exercises may depend on variables created in earlier cells.

The objective of this hands-on exercise is to practice the EDA concepts covered during the session using a Customer Churn dataset.