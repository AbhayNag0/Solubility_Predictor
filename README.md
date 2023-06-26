# Solubility_Molecule_Maker
I have made a jupyter notebook that uses a Recurrent Neural Network Model to generate molecules. From those molecules, there is a solubility predictor which seperates out the soluble molecules and 
hence, we can generate soluble molecules.

Dependencies: 
1. Pytorch
2. Pycaret
3. Rdkit
4. Selfies

To use this repo, run

`python sample.py -result_dir your_output_dir` 
where `your_output_dir` will be your working directory.

After that, you can run the jupter notebook sampled_mols.ipynb.
