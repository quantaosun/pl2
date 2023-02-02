# pdbfixer_binder

Try the binder version for a quick and straightforward fix on protein only.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/quantaosun/pdbfixer_binder/HEAD?labpath=pdbfixer_binder.ipynb)

For more advanced use, like fixing the protein-ligand complex and showing the interaction, try the Colab version. 

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/quantaosun/pdbfixer_online/blob/main/pdbfixer_colab.ipynb#scrollTo=9NMNSGndkqPV)

![image](https://user-images.githubusercontent.com/75652473/215966394-871081e6-f213-4704-8e1e-2aa6082e4317.png)

## This notebook is primarily designed to use with PDB bank structures, with minimal change it can be applied to docked local pdb structure as well. Just read the receptor and ligand from ```Prepare protein``` and ```prepare ligand``` section.

# Protein Ligand Interaction Diagram Generator

## Essentially, this is a free protein preparation process, and at last, you will get the prepared structure named as 
```complex_prepared.pdb``` 
## while the 2D interaction is just inside this online notebook, you can copy and paste it anywhere you want.

- This workflow allows you to input a PDB bank protein-ligand co-crystal structure.
- The structure will be split and prepared separately
- The prepared structures then combined again
- The 2D interaction is a draw based on the merged structure
- The user is expected to provide the PDB ID and the ligand name as per in the PDB database, which is listed on the small molecule section of the PDB main page of the corresponding structure

### After the protein prepared, the ```complex_prepared.pdb``` has the readily compatable format that can be uploaded and be recognized by Charmm Gui web server, from there molecular dynamic input can be generated easily.
