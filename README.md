# KOA-Final-Year-Research

## Accessing the Repository

To clone the repository and access all source files, run the following commands in a terminal with Git installed:

```bash
git clone https://github.com/DmAsnaff/KOA-Final-Year-Research.git
cd KOA-DualStream-DeepLearning
```

---

# Implementation Instructions and Setup Guide

This guide provides step-by-step instructions for setting up the development environment and running the experiments.

---

## Step 1 - Prepare the Dataset

This study uses the **OAI Knee Osteoarthritis Severity Grading Dataset** distributed by Chen et al. (2018) through Mendeley Data.

### Dataset Access

- Access the dataset at:  
  https://data.mendeley.com/datasets/56rmx5bjcr/1


---

## Step 2 - Install Requirements

It is recommended to create a virtual environment before installing dependencies.

Install all required packages using:

```bash
pip install -r requirements.txt
```

---

## Step 3 - Run the What Stream Experiments

1. Open **Jupyter Notebook** or **JupyterLab** from the repository root.
2. Navigate to:

```text
what_stream/
```

3. Run the notebooks in the provided order to reproduce the **What Stream** experiment results.

---

## Step 4 - Run the Where Stream Experiments

1. Navigate to:

```text
where_stream/
```

2. Run the notebooks in order to reproduce the **SE-ResUNet progressive experiment** results.

---

## Step 5 - Run the Fusion Experiment

Run the following notebook to test the dual-stream fusion model:

```text
Two_Stream_Fusion_3.ipynb
```

This notebook performs the final image-based fusion evaluation using outputs from both the What Stream and Where Stream models.

---
