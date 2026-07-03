# Topic: - Nucleotide K-mer Analysis
A Python-based bioinformatics notebook for analyzing DNA sequences from FASTA files. It performs sequence validation, nucleotide composition analysis, GC content calculation, complement/reverse complement generation and k-mer frequency visualization.

# Overview
This Google Colab notebook performs comprehensive analysis of DNA sequences obtained from NCBI GenBank via FASTA File, focusing on nucleotide composition and k-mer frequency patterns. It includes visualization tools for understanding sequence characteristics using Bio Python and various data visualization libraries.

# Features
## 1. Sequence Validation
-Validates DNA sequences against standard nucleotide bases (A, T, G, C)
-Identifies invalid bases in sequences
-Calculates GC content percentage
-Provides comprehensive sequence statistics
## 2. Nucleotide Composition Analysis
- Counts individual nucleotides (A, T, G, C)
- Calculates percentage composition for each base
- Displays total sequence length
- Generates detailed composition reports
## 3. Sequence Transformation
- Generates complement sequences
- Computes reverse complement sequences
- Essential for understanding DNA structure and replication
## 4. K-mer Analysis
- Flexible k-mer frequency counting (any k value)
- Identifies most frequent k-mers in sequences
- Supports analysis of subsequence patterns
- Ranks k-mers by frequency
## 5. Visualization
- Bar plots for top k-mer frequencies
- Heatmaps for k-mer abundance patterns
- Clustered heatmaps for hierarchical k-mer analysis
- Publication-quality figures with customizable styling

# Installation
pip install biopython pandas numpy matplotlib seaborn

# Dependencies
Python
- Bio (BioPython)
- pandas
- numpy
- matplotlib
- seaborn
- collections

# Example Data
The notebook includes analysis of:
- Sample: Homo sapiens DNA sequence (L08562.1)
- Length: 241 bp
- Sequence Type: Alpha-satellite repeat
- GC Content: 41.08%

# Output Visualizations
K-mer Frequency Bar Chart: Top 15 most frequent 3-mers
Clustered Heatmap: Hierarchical clustering of k-mer abundance
Nucleotide Composition: Breakdown of A, T, G, C percentages
Statistical Summary: Sequence validity and base composition metrics

# Notes
-Handles case-insensitive sequence input (converts to uppercase)
-Supports multiple sequences in FASTA files
-Invalid bases are identified and reported
-GC content is calculated as (G + C) / Total bases * 100




