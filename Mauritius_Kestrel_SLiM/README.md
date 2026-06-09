# Mauritius kestrel SLiM simulations

This repository contains the SLiM v5 script used for the Mauritius kestrel forward-in-time simulations described in the manuscript.

Main script:
- `MAU_kestrel_slim5_V6.slim`

The model implements an age-structured non-Wright-Fisher simulation with sex-specific monogamous pairing, historical demographic trajectories, a four-individual bottleneck, conservation scenarios, managed releases, and genomic outputs including heterozygosity, ROH and genetic load summaries.

Input files such as the life table, demographic trajectories, genomic feature map and recombination map should be placed in the same project directory or the `basePath` variable in the script should be edited accordingly.
