# DIVA-DRAM

This repository provides characterization data collected over 96 DDR3 SO-DIMMs, related to the following papers.

**Lee et al.**, "[_Design-Induced Latency Variation in Modern DRAM Chips: Characterization, Analysis, and Latency Reduction Mechanisms_](https://people.inf.ethz.ch/omutlu/pub/DIVA-low-latency-DRAM_sigmetrics17-paper.pdf)
", **SIGMETRICS 2017**

**Lee et al.**, "[_Understanding and Exploiting Design-Induced Latency Variation in Modern DRAM Chips_](https://arxiv.org/abs/1610.09604)", **arXiv:1610.09604**

### SPICE_MODEL
- This directory contains the SPICE model of a DRAM array, which is used for the simulation data in APPENDIX B of the SIGMECTRISC 2017 paper. The tool used for the simulation is [LTspice](http://www.linear.com/designtools/software/). 

### PROFILE_DATA
- This directory contains the data collected from our experiments.
- **vendor/summary**: contains a quick overview of how many error bits are observed at different DRAM test conditions.
- **vendor/rawdata**: contains detailed error information or the evaluated DIMMs, which is used for Sections 5 and 6 of the SITMECTRIC 2017 paper.
- **vendor/analysis**: contains the collected and analyzed data for the papers.
