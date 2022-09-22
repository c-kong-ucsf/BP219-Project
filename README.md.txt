# Uni-tagger: UCSF Programming Project

Uni-tagger is a project that looks at observing RMSD scores of proteins tags appended to a native/novel protein. Current implementation utilizes four tags:
- 6x His
- Calmodulin binding protein (CBP)
- Chitin binding domain (CBD) + 3 Glycine
- mNEONGreen (mNG) + 5 Glycine

This project utilizes the AlphaFold2 [ColabFold project](https://github.com/sokrypton/ColabFold) as the project uses structure prediction from user-input sequences. The sequences are then aligned, and the RMSD values are compared to determine how tagged variants deviate from the native conformational structure. 

WARNING: This is a proof of concept, there may still many bugs as well as the results may deviate from experimental data. 

## Installation

No installation required! Just utilize the following link to utilize the tool via Google Colab.

### [Uni-tagger](google.com)

## Instructions

Once you open the Notebook, make sure to run the code in order as many of the function calls are dependent on previously imported statements/packages. Below is the order in which cells should be run.

```python
1. Install Dependencies
2. Import Packages/Modules
3. Run ColabFold Functionality
4. Run RMSD Functionality
5. Load User Interface
6. (optional) Open Public URL
```
## References

* Mirdita M, Schütze K, Moriwaki Y, Heo L, Ovchinnikov S and Steinegger M. ColabFold: Making protein folding accessible to all.
    Nature Methods (2022) doi: 10.1038/s41592-022-01488-1
* Jumper et al. "Highly accurate protein structure prediction with AlphaFold."
    Nature (2021) doi: 10.1038/s41586-021-03819-2
* Evans et al. "Protein complex prediction with AlphaFold-Multimer."
    biorxiv (2021) doi: 10.1101/2021.10.04.463034v1
* Minkyung et al. "Accurate prediction of protein structures and interactions using a three-track neural network."
    Science (2021) doi: 10.1126/science.abj8754
