# RECEPTOR-6CM4-LIGAND-GMJ-MOECULAR-DOCKING-WITH-AUTODOC-VINA-PYMOL
# Molecular Docking of 6CM4 Receptor with GMJ Ligand using AutoDock Vina & PyMOL

## Overview
This project focuses on the molecular docking analysis of the **6CM4 dopamine receptor** with the **GMJ ligand** using **AutoDock Vina**. The docking results are analyzed and visualized using **PyMOL**.

## Tools & Software Used
- **AutoDock Vina** – Molecular docking tool
- **PyMOL** – Visualization and analysis
- **OpenBabel** – File format conversion
- **MGL Tools** – Preparing receptor and ligand files

## Dataset Information
- **Receptor:** 6CM4 (Dopamine receptor) FROM  (https://www.rcsb.org/structure/6CM4)
- **Ligand:** GMJ (Haloperidol derivative) from (https://www.rcsb.org/ligand/GMJ)
- ## Workflow
1. **Preparation of Receptor & Ligand**
   - Download **6CM4** structure from RCSB PDB
   - Prepare ligand using **OpenBabel**
   - Remove water molecules and add polar hydrogens

2. **Docking using AutoDock Vina**
   - Convert receptor and ligand to **PDBQT** format
   - Define grid box parameters
   - Run **AutoDock Vina** for docking

3. **Analysis & Visualization**
   - Extract binding affinity and interaction details
   - Visualize docking pose in **PyMOL**

## Results
- **Binding affinity:** _X kcal/mol_ (Replace with actual value)
- **Best docking pose**: Shown in PyMOL visualization

- ## How to Reproduce
1. Clone the repository:
   ```bash
   git clone https://github.com/SWAROOP-KUMAR18/RECEPTOR-6CM4-LIGAND-GMJ-MOECULAR-DOCKING-WITH-AUTODOC-VINA-PYMOL.git
   ```
2. Install dependencies:
   ```bash
   pip install pymol openbabel
   ```
3. Run docking script:
   ```bash
   bash run_docking.sh
   ```
4. Visualize results in **PyMOL**

## References
- [AutoDock Vina Documentation](http://vina.scripps.edu/)
- [PyMOL User Guide](https://pymol.org/)
- 
- ## Acknowledgment
We acknowledge the **RCSB Protein Data Bank (PDB)** for providing structural data for:
- **6CM4 Dopamine Receptor** ([6CM4 PDB Entry](https://www.rcsb.org/structure/6CM4))
- **GMJ Ligand**

## Author
**Swaroop Kumar Ponnaganti**

## License
This project is open-source under the **MIT License**.
