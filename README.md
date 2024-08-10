# Bachelor project by Nynne West Kristensen, supervised by Thomas Hamelryck, August 2024, The University of Copenhagen
 
The title of the project is: Bayesian modelling of protein dihedral angles in the probabilistic programming
language Numpyro.

The Bachelor_vm_cumsum_psi_(the_final_code).ipynb file utilizes the univariate von Mises distribution. This final code serves as the foundation for the analysis and results presented in my report. 

The Bachelor_ssbvm_mixture.ipynb file explores an alternative approach by using the sine bivariate von Mises distribution. This method aimed to capture the relationship between multiple angles simultaneously, offering a more complex and potentially more informative model. However, this approach encountered several technical challenges, particularly related to numerical stability and convergence issues. Despite these difficulties, the code is included in my work to provide insight into the full scope of the modeling process and the experimentation that was undertaken.


The Bachelor_filter_outliers_created_by_Thomas_Hamelryck.py script was designed by my supervisor, Thomas Hamelryck. It systematically identifies and removes data points that fall outside the expected range of values, ensuring that the dataset from the protein database used in the analysis is clean and representative of typical protein structures. By filtering out these anomalies, the script enhances the reliability of the subsequent modeling process.
