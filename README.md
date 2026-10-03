# digital-pcr
Dig-PCR project (CB2330) by Aditi Shinkhede and Marleen Roomet (MSc Molecular Biotechnology and Bioinformatics, KTH)

This project develops a small stochastic model inspired by Vogelstein and Kinzler's 1999 paper "Digital PCR". The paper describes a method for detecting rare mutant DNA by distributing DNA into many wells, amplifying the DNA and comparing fluorescence signals from two probes.

The goal of this project is not to reproduce the experiment exactly, but to build a simplified model that captures some of the important sources of randomness in digital PCR.

The model was used to simulate a 384 well experiments. Because DNA molecules are randomly distributed between wells, repeated experiments with the same parameters do not produce exactly the same results.
We additionally ran many virtual experiments to investigate this variation. 

The simulation is contained in project.ipynb. The notebook is designed to run from top to bottom.
