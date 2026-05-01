# CPTS350-Adaptive-Quicksort-Project
Experimental Algorithms Project for Reducing Worst-Case Risk Through Pivot Switching Quicksort Approach

**Team:** Brian Gasca & Jacob Draper Gilliam

### Introduction
This project implements **five Quicksort variants** and runs large-scale statistical experiments (10,000 to 50,000 elements) over 5 trials per threshold to compare their performance on adversarial and random inputs.

The main focus is the **Adaptive Quicksort**, which starts with median-of-three pivot selection and automatically switches to random pivot selection after detecting two consecutive poorly balanced partitions.

### Algorithms Included
- **First Pivot Quicksort**
- **Median-of-Three Quicksort**
- **Random Pivot Quicksort**
- **Three-Way Partitioning Quicksort**
- **Adaptive Quicksort**
  
### How to Run

1. Make sure you have Jupyter Notebook and the required packages installed:
   ```bash
   pip install matplotlib numpy
   
2. Open Notebook and run all cells:
   ```bash
   jupyter notebook CPTS350_AdaptiveQuicksort.ipynb
