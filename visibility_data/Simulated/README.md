# Simulated visibility data


## ref_1.1_uniform.uvfits

Contains simulation outputs from pyuvsim. Simulated array has an MWA-like layout
using uniform beams.
processed/edited by pyuvdata: Yes
Simulated observation date: Decemeber 10, 2017
Simulation date: unknown, before October 2018

## refsim1.1_fhd

Contains simulation outputs from pyuvsim processed and written out by FHD.
Simulated array has an MWA-like layout using uniform beams.
processed/edited by pyuvdata: Yes
Simulated observation date: Decemeber 10, 2017
Simulation date: unknown, after May 2019

## fewant_randsrc_airybeam_Nsrc100_10MHz.uvfits

Contains simulation outputs from pyuvsim version: 0.2.1.
Simulated array has a HERA-like layout with 19 antennas and Airy beams.
Simulated observation date: Decemeber 22, 2017
Simulation date: unknown, before May 2019
Notes: used for testing redudancy operations because it has perfect redundancy
by construction.

## simulated_bda_file.uvh5

Contains simulation outputs from RimeZ for a HERA-like array. Baseline dependent
averaging applied. Downselected and written out with pyuvdata.
Simulated observation date: Decemeber 18, 2017
Simulation date: unknown, before July 2019
Notes: used for testing handling of data with BDA applied.