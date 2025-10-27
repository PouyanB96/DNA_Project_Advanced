# DNA Analyzer

This project reads DNA sequences from a FASTA file and analyzes their nucleotide composition (A, T, C, G) and GC content.  
It also visualizes the GC percentage for each sequence using bar charts.

## How to use
1. Open the notebook `analyzer.ipynb` in Jupyter Notebook or JupyterLab.  
2. Make sure you have a FASTA file (e.g. `example.fasta`) in the same folder.  
3. Run all cells to see results and plots.

## Requirements
You need these Python packages:
- pandas  
- biopython  
- matplotlib  

To install them, run:
```
pip install pandas biopython matplotlib
```

##  Output
- Table of nucleotide counts and GC% per sequence  
- Bar chart of GC content
## Example Output

![GC Content Plot](result.png)
