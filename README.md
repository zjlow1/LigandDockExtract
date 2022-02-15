# LigandDockExtract
Extraction of least energetic pose of each docked ligand 

Created to extract least energetic pose of each docked ligand from a list of poses generated from a molecular docking simulation. 
Molecular docking is performed using PyRx, a virtual screening software that uses AutoDock as a docking software. 

Installation: 
Download PyRx (https://pyrx.sourceforge.io/) and install in designated directory
Download AutoDock Vina and AutoDock (https://ccsb.scripps.edu/projects/docking/) and install in designated directory

Software setup:
Run PyRx, under Preferences, select directories of AutoDock Vina, AutoDock 4, and Autogrid accoridngly. Create new folder as workspace directory for storage of ligands and proteins (macromolecules)

Import protein structure:
Identify suitable structure file of protein target from PDB or AlphaFold database and download as .cif file.
Import .cif file via File>Load molecule option.Loaded molecule will be displayed on 3D scene pane of PyRx software.
To split ligand from protein, under "Molecules" pane, expand protein, select ligand, right-click and choose Autodock>Make Ligand option. 
To classify protein as macromolecule, right-click and choose Autodock>Make Macromolecule option

