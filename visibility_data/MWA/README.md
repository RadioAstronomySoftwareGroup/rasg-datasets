# MWA visibility data

## 1061316296.uvfits

Observation date: August 23, 2013
processed/edited by pyuvdata: yes
Notes: Written to MWA correlator FITS files by the MWA correlator (legacy).
Converted to a uvfits by Cotter. Downselected and written out using pyuvdata.

### 1061316296_nearfield_w.npy

A small numpy file holding the nearfield phased w's for 1061316296.uvfits used
for testing the nearfield phasing code.


## fhd_vis_data

Observation date: August 23, 2013
processed/edited by pyuvdata: maybe
Notes: Written to MWA correlator FITS files by the MWA correlator (legacy).
Converted to a uvfits by Cotter. Possibly downselected using pyuvdata, then
processed and written out with FHD. Contains some extra, modified copies of files
with various changes for code coverage.

## 1090008640_birli.ms

Observation date: July 21, 2014
processed/edited by pyuvdata: No
Notes: Written to MWA correlator FITS files by the MWA correlator (legacy).
Converted to a measurement set by birli.

## 1102865728_small.ms

Observation date: December 17, 2014
processed/edited by pyuvdata: No
Notes: Written to MWA correlator FITS files by the MWA correlator (legacy).
Converted to a measurement set by Cotter.

## 1133866760.uvfits

Observation date: December 11, 2015
processed/edited by pyuvdata: yes
Notes: Written to MWA correlator FITS files by the MWA correlator (legacy).
Converted to a uvfits by Cotter. Downselected and written out using pyuvdata.

## 1133866760_rephase.uvfits

Observation date: December 11, 2015
processed/edited by pyuvdata: yes
Notes: Written to MWA correlator FITS files by the MWA correlator (legacy).
Converted to a uvfits by Cotter. Downselected and written out using pyuvdata.
The same data as in 1133866760.uvfits but phased to a different phase center in
Cotter. Used to validate our phasing code (our phasing is actually more accurate
than Cotter phasing, but this was used as an early test so we continue to test
against it).

## mwa_corr_fits_testfiles

Contains raw MWA correlator files from several observation dates (file names start
with the GPS second of the beginning of the observation):
processed/edited by pyuvdata: No

### 1061315448

Observation date: August 23, 2013
Notes: Written to MWA correlator FITS files by the MWA correlator (legacy).

### 1131733552

Observation date: November 16, 2015
Notes: Written to MWA correlator FITS files by the MWA correlator (legacy).

### 1320409688

Observation date: November 08, 2021
Notes: Written to MWA correlator FITS files by the MWA correlator (MWAX).
