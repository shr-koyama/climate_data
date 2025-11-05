# ESN implementation and Dataset for 'Assessing the predictability of meteorological variables via spatial correlations using echo state networks'

## Overview
This project implements time series data prediction using Echo State Network.

## Data
The time-series climate datasets used in our paper. The data is averaged over 1-degree grid of ``JRA-55 6-Hourly Model Resolution Land Surface Analysis Fields data''. The original data were obtained from NCAR's website https://rda.ucar.edu .
The file name structure is following:
data/[yyyy]/[city]/[kind]/[kind]_lat[uu]_lon[vv]_[yyyy].csv
- [yyyy]: year of data
- [city]: the name of target city
- [kind]: kind of climatic quantity to predict
- [uu]: latitude of data
- [vv]: longitude of data

## Sample code 
- `prediction.ipynb` is a demonstration of ESN prediction for temperature data. 
For three different observed data in the latitudinal direction. 
Actual data and model prediction are plotted and NRMSE are printed.
- `esn_dts.py` is the python code to use ESN model in `prediction.ipynb`.

## Citation
If you use this code in your research, please cite our paper:
**arXiv preprint**: https://arxiv.org/abs/2406.03061

## Author
Shihori Koyama, Daisuke Inoue, Hiroaki Yoshida<br>
Toyota Central R&D Labs., Inc.<br>
shihori-koyama@mosk.tytlabs.co.jp<br>
Kazuyuki Aihara<br>
The University of Tokyo<br>
Gouhei Tanaka<br>
Nagoya Institute of Technology

## License
This repository is licensed under LICENSE.md.
