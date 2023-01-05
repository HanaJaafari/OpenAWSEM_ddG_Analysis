# OpenAWSEM_ddG_Analysis
Comparison of experimental (from ProTherm) and predicted (using OpenAWSEM) ddG values

The ProTherm database compiles experimental ddG values, i.e. folding free energy changes between native proteins and their mutants. 
We use the 2005 version of the database, which has been widely used in the literature to benchmark predictive mutational stability algorithms.

We compare experimental ddG values with those predicted by the OpenAWSEM algorithm (Wei, L. et al., 2021). We assume that 
native and mutated unfolded or globular states have identical free energy values, so our predicted free energy change
is AWSEM_folded,mutated-AWSEM_folded,native.

We process the ProTherm data in different ways (such as averaging ddG values for entries associated with the same mutation and 
similar experimental conditions) that have been employed in the literature. We only use experimental ddG values for monomeric proteins 
whose folding is described by two-state models.
