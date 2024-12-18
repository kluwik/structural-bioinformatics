# Structural Bioinformatics

Useful tools for working with protein structures.

## 1. 3D structure prediction

- AlphaFold - [github](https://github.com/deepmind/alphafold) | [colab (official)](https://colab.research.google.com/github/deepmind/alphafold/blob/main/notebooks/AlphaFold.ipynb) | [ColabFold](https://colab.research.google.com/github/sokrypton/ColabFold/blob/main/AlphaFold2.ipynb)
- [Robetta-server](http://robetta.bakerlab.org/) - Roseta ab initio, comparative modeling, RoseTTAFold)
- [I-TASSER](https://seq2fun.dcmb.med.umich.edu//I-TASSER/)
- [SWISS-MODEL](https://swissmodel.expasy.org/)

## 2. Structural alignment

**Lists:**

- [Protopedia](https://proteopedia.org/wiki/index.php/Structure_superposition_tools)

**Aggregators:**

- [PDB alignment tools](https://www.rcsb.org/alignment)

**Tools:**

- [TM-align](https://zhanggroup.org/TM-align/) 
- [FATCAT](http://fatcat.godziklab.org/)

## 3. Seconadary structure prediction

**Aggregators:**

- [Quick2D](https://toolkit.tuebingen.mpg.de/tools/quick2d)

**Tools:**

- [PSIPRED](http://bioinf.cs.ucl.ac.uk/psipred)
- [PSSpred](https://zhanggroup.org/PSSpred/)
- [Jpred](https://www.compbio.dundee.ac.uk/jpred4/index.html) 

**Visualizers:**

- [2dss](http://genome.lcqb.upmc.fr/2dss)

## 4. Seconadary structure assignment

- [DSSP](https://swift.cmbi.umcn.nl/gv/dssp)
- [Stride](https://webclu.bio.wzw.tum.de/stride/)

## 5. Prediction of functionally important protein regions

**Lists:**

- [molbiol-tools.ca](https://molbiol-tools.ca/Protein_secondary_structure.htm)

### Transmembrane domains

- [TMHMM](https://dtu.biolib.com/DeepTMHMM)
- [Phobius](https://phobius.sbc.su.se/) 

### Disordered regions

- [PONDR](http://www.pondr.com)
- [DISOPRED3](http://bioinf.cs.ucl.ac.uk/psipred/) 

### Signal peptides, cleavage sites, and subcellular localization

- [SignalP](https://services.healthtech.dtu.dk/service.php?SignalP) 

### Specificity-Determining Positions (SDPs)

- [SDPpred](http://bioinf.fbb.msu.ru/SDPpred/) 

## 6. Molecular visualization

- [Jmol](https://jmol.sourceforge.net/)
- [Protein Imager](https://3dproteinimaging.com/protein-imager/)
- [VRMol](https://vrmol.net/)
- [LiteMol](https://www.litemol.org/)
- [Mol*](https://molstar.org/)

## 7. Jupyter Notebooks

[Biopython for working with PDB files](https://colab.research.google.com/github/kluwik/structural-bioinformatics/blob/main/Biopython_for_working_with_PDB_files.ipynb) - standard routine with PDB structures (download from PDB, open/save structures, parse sections, retrieve sequence).

[Molecular graphics in Jupyter](https://colab.research.google.com/github/kluwik/structural-bioinformatics/blob/main/Molecular_graphics_in_Jupyter.ipynb) - static and interactive visualization of protein structures in Jupyter.

[DSSP in Biopython](https://colab.research.google.com/github/kluwik/structural-bioinformatics/blob/main/DSSP_Biopython.ipynb) - get/parse DSSP annotation using Biopython with or without DSSP installed.
