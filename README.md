# PepSS

PepSS is a sequence based secondary structure predictor for peptides.

It takes a list of peptides in Fasta format and provides 3 state secondary structure predictions for each residue - Helix, Strand and Other.

It is very fast as it doesn't use evolutionary information. Instead just amino acid identity, isoelectric point, hydrophibicity and values from the TOP-IDP scale are used to make the predictions.

This makes it suitable for proteomic datasets where there may be many thousands of peptides present.

## Instructions
Click [here](https://colab.research.google.com/github/elliot-drew/pepss-ed/blob/main/pepss.ipynb) to open the notebook on Google Colab.
Follow the instructions on the notebook to make your predictions.
