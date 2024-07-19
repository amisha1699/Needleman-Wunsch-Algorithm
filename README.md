# Needleman-Wunsch-Algorithm

This repository features a basic implementation of the Needleman-Wunsch algorithm in Python. The Needleman-Wunsch algorithm, a pioneering application of dynamic programming in bioinformatics, is used to align protein or nucleotide sequences. It is extensively used for optimal global alignment, especially when the precision of the alignment is crucial. The algorithm evaluates every possible alignment by assigning scores, aiming to identify all alignments with the highest score.

## Features

* Aligns two sequences using the Needleman-Wunsch algorithm.
* Allows for customized match, mismatch, and gap penalties.
* Aligned sequences with formatting and alignment score returned as output.

## Requirements

* Python 3.x
* NumPy

## Usage
1. Clone this repo:
```
git clone https://github.com/amisha1699/Needleman-Wunsch-Algorithm.git
cd Needleman-Wunsch-Algorithm
```

2. Input Data
Please make sure the input data is in the same format as provided in `data/seq.txt`