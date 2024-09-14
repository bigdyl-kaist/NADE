# Climate Modeling with Neural Advection-Diffusion Equation
![GitHub Repo stars](https://img.shields.io/github/stars/hwangyong753/NADE)
[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fhwangyong753%2FNADE&count_bg=%230BADED&title_bg=%233B2424&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://hits.seeyoufarm.com)
 
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/climate-modeling-with-neural-advection/weather-forecasting-on-la)](https://paperswithcode.com/sota/weather-forecasting-on-la?p=climate-modeling-with-neural-advection)  [![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/climate-modeling-with-neural-advection/weather-forecasting-on-sd)](https://paperswithcode.com/sota/weather-forecasting-on-sd?p=climate-modeling-with-neural-advection)  [![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/climate-modeling-with-neural-advection/weather-forecasting-on-noaa-atmospheric)](https://paperswithcode.com/sota/weather-forecasting-on-noaa-atmospheric?p=climate-modeling-with-neural-advection)

This repository contains the implementation of NADE (Neural Advection-Diffusion Equation), a novel deep learning approach for climate modeling as described in our paper "Climate Modeling with Neural Advection-Diffusion Equation".

## Overview
<img src="asset/overview_NADE.png" width="600">
NADE combines the advection-diffusion equation with neural networks to model climate systems. Key features include:

- Edge weight learning to model diffusion coefficients and flow velocities
- Neural network-based uncertainty modeling
- Integration with the advection-diffusion equation


# Instructions

### How to Run
```
$ cd model
$ python Run.py
```
## Datasets
We provide experiments on real-world datasets:
- Los Angeles (LA) and San Diego (SD) climate data
- NOAA temperature data

See the `data/` directory for more details.

## Citation
If you use this code in your research, please cite our paper:
```
@article{choi2023climate,
title={Climate modeling with neural advection--diffusion equation},
author={Choi, Hwangyong and Choi, Jeongwhan and Hwang, Jeehyun and Lee, Kookjin and Lee, Dongeun and Park, Noseong},
journal={Knowledge and Information Systems},
volume={65},
number={6},
pages={2403--2427},
year={2023},
publisher={Springer}
}```