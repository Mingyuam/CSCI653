# Potential Energy Surface Calculation with Active Learning 



## Problem Description

Using machine learning method to calculate interatomic potentials often requires thousands of first principles calculations. With active learning algorithm, the internal uncertainty of a Gaussian process regression model is used to decide whether to perform a first principle calculation, or just accept the model prediction. This method significantly accelerate the training process. This project aims to apply the active learning package in Ref. [1,2] and start from reproducing the results in the papers to get some insight on active learning approaches. 

## DeePMD Workflow
  - Prepare data
  - Train a model
  - Freeze the model
  - MD runs with the model (Native MD code or LAMMPS)  
  

## Water Molecule PES by DeePMD

As a warm up, we applied active learning method to calculate PES of water molecule as function of O-H bond length and bond angle. We will update the details of training process later. 
  
Here we show the PES of water molecule by DeepMD.
![](water.PNG)



## Expected Results

- calculate PES of aluminum with FLARE and Quantum Espresso  
- calculate PES of Mg-Al alloys with DeePMD  



## Reference 
[1] Jonathan Vandermause, Steven B. Torrisi, Simon Batzner, Yu Xie, Lixin Sun, Alexie M. Kolpak, and Boris Kozinsky. On-the-fly active learning of interpretable Bayesian force fields for atomistic rare events. https://arxiv.org/abs/1904.02042  
[2] Linfeng Zhang, De-Ye Lin, Han Wang, Roberto Car, and Weinan E, Phys. Rev. Materials 3, 023804 – Published 25 February 2019




