# AlignSubs: Alignment Substitution Analyzer (for nucleotide and aminoacid substitutions)

This project is a Python script that allows researchers to analyze multiple sequence alignments (MSA, as FASTA or Clustalw Files) and generate substitution statistics for nucleotide and protein sequences. This tool is particularly useful for researchers and bioinformaticians studying sequence variation and evolutionary relationships.

DOI/Cite:

Karagol, A., & Karagol, T. (2024). An Evolutionary Statistics Toolkit for Simplified Sequence Analysis on Web with Client-Side Processing. bioRxiv, 2024-08. doi: https://doi.org/10.1101/2024.08.01.606148


### Installation

- Option 1 (RECOMMENDED, for all platforms): You can install the package via pip (if you have Python 3.x on your system), and use the command AlignSubs directly:
```
pip install AlignSubs  
```
```
AlignSubs
```


- Option 2 (for all platforms): You can run the script directly from Google Colab: [AlignSubs.ipynb on Google Colab](https://colab.research.google.com/github/karagol-taner/Alignment-Substitution-Analyzer/blob/main/AlignSubs_Alignment_Substitution_Analyzer.ipynb)
  

- Option 3 (for all platforms): This tool is also available on web: [www.tanerkaragol.com/alignment-substitution-analyzer](https://www.tanerkaragol.com/alignment-substitution-analyzer)

Latest version on PyPI:

[![PyPI version](https://badge.fury.io/py/AlignSubs.svg)](https://badge.fury.io/py/AlignSubs)

### Features

1. **Cross-Platform:** Supports Windows, Mac, and Linux. Compatible with HPC environments.

2. **CSV Outputs:**
 - **Directional List:** Each protein/nucleotide pair is analyzed, listing substitutions sorted by highest count first. Includes positions and optional hydropathy changes.
 - **Substitution Summary:** Aggregates substitution counts across all pairs, sorted by total occurrences.

3. **Property changes**
 - Protein: Hydropathy changes and pI changes can optionally be calculated and included in CSV outputs.
 - Additional protein/nucleotide property analyses will be included in upcoming versions.
   
4. **Input Files:** Supports FASTA and Clustal alignment formats, also as text.

5. **Review and Save:** Users choose the paths to save CSV outputs. Substitutions and counts are clearly organized.


### Requirements
If you want to run the script natively on your local computer (Option 1), ensure you have Python 3.x installed on your system. 

If Biopython is not already installed, the script will prompt you to install it automatically. 
If the script fails to automatically install Biopython, you can install it manually using the following steps:

- Open a terminal or command prompt after installing Python.
- Run the following command to install Biopython using pip:
  
   ```
   pip install biopython
   ```


### Questions
If you have any questions or encounter issues, don't hesitate to reach out.

### License
This project is licensed under the  GPL-3.0 License - see the LICENSE file for details.
