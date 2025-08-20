# grn2ode

Simplest model for simulating a GRN

Given a GRN file, generate a simulatable ODE model in antimony. 

There exist a number of projects generating ODEs from a GRN, notably GeneNetWeaver ([repo](https://github.com/tschaffter/genenetweaver), [article](https://academic.oup.com/bioinformatics/article/27/16/2263/254752)), however, they are mostly based on yeast and bacteria. 

Here we aim to create a dynamical ODE system from a GRN in a highly customisable way, focusing on arabidopsis as the target species. 

# Progress:

- :white_check_mark: Generate valid antimony from an input network [notebooks/build-antimony.ipynb]
- :black_square_button: Improve ODE functions
- :white_check_mark: Estimate gene and rna length distributions for arabidopsis [notebooks/nucleic-acid-lengths.ipynb]
- :black_square_button: Find/generate estimates and distributions for the rest of the parameters
- :black_square_button: Generate parameters from distributions
- :black_square_button: Read in parameters from a file to inject into the antimony 
