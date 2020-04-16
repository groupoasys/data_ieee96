# data_ieee96

## Goals ⚽

The aim of this repository is to provide the details of the medium-size data set used in paper [[3]](https://www.researchgate.net/publication/334390057_Data-driven_Network_Reduction_for_Transmission-Constrained_Unit_Commitment). This article have been developed by some
members of the [OASYS group](https://sites.google.com/view/groupoasys/home) thanks to the funding of the project [Flexanalytics](https://groupoasysflexanalytics.readthedocs.io/en/latest/). We suggest you to visit the related links to know more our research 😉


## Contents 📖

This repository includes the data of the IEEE RTS-96 test system [[1]](https://ieeexplore.ieee.org/abstract/document/780914) modified to accommodate 19 wind farms as proposed in [[2]](https://ieeexplore.ieee.org/abstract/document/7115977). This power systems includes 73 nodes and 120 transmission lines. Each data file is explained below: 

- [thermal_ieee96.csv](thermal_ieee96.csv): data on thermal generators including minimum and maximum outputs, variable cost and ramping limits

- [lines_ieee96.csv](lines_ieee96.csv): data on transmission lines including susceptance and maximum capacity

- [load_ieee96.csv](load_ieee96.csv): data on hourly electricity demand at each node of the system for a whole year

- [wind_ieee96.csv](wind_ieee96.csv): data on hourly wind power generating at each node of the system for a whole year

- [congestion_capx1.csv](congestion(capx1).csv): congestion data of transmission lines for original capacity limits

- [congestion_capx2.csv](congestion(capx2).csv): congestion data of transmission lines if capacity limits are doubled

- [congestion_capx05.csv](congestion(capx05).csv): congestion data of transmission lines if capacity limits are halved

## References 📚

[1] Grigg, C., Wong, P., Albrecht, P., Allan, R., Bhavaraju, M., Billinton, R. and Singh, C. (1999). The IEEE Reliability Test System-1996. A report prepared by the Reliability Test System Task Force of the Application of Probability Methods Subcommittee. IEEE Transactions on Power Systems, 14(3), 1010–1020. https://doi.org/10.1109/59.780914

[2] Pandzic, H., Dvorkin, Y., Qiu, T., Wang, Y. and Kirschen, D. S. (2015). Toward Cost-Efficient and Reliable Unit Commitment Under Uncertainty. IEEE Transactions on Power Systems, PP(99), 1–13. https://doi.org/10.1109/TPWRS.2015.2434848

[3] Pineda, S., Morales, J. M. and Jiménez-Cordero, A. (2020). Data-Driven Screening of Network Constraints for Unit Commitment. IEEE Transactions on Power Systems, doi: 10.1109/TPWRS.2020.2980212. https://doi.org/10.1109/TPWRS.2020.2980212

[4] OASYS, Data IEEE 96, Github repository (https://github.com/groupoasys/data_ieee96) , 2019.

## How to cite the repo and the paper? 📝

If you want to cite paper [[3]](https://ieeexplore.ieee.org/document/9034123) or this repo, [[4]](https://github.com/groupoasys/data_ieee96), please use the following bib entries:

* Article:
```
@article{pineda2020data,
  title={Data-Driven Network Screening of Network Constraints for Unit Commentment},
  author={Pineda, Salvador and Morales, Juan Miguel and Jim\'enez-Cordero, Asunci\'on},
  journal={IEEE Transactions on Power Systems},
  year={2020},
  doi={10.1109/TPWRS.2020.2980212},
}
```
* Repository:
```
@article{IEEE96_2019,
author = {OASYS},
journal = {GitHub repository (https://github.com/groupoasys/data{\_}ieee96)},
title = {{Data IEEE 96}},
url = {https://github.com/groupoasys/data{\_}ieee96},
year = {2019}
}
```

## Do you want to contribute? 🙋‍♂️🙋‍♀️
 
 Please, do it 😋 Any feedback is welcome 🤗 so feel free to ask or comment anything you want via a Pull Request in this repo.
 If you need extra help, you can ask Salvador Pineda (spinedamorente@gmail.com), Juan Miguel Morales (juan.morales@uma.es) or Asunción Jiménez-Cordero(asuncionjc@uma.es).
 
 ## Contributors 🌬☀
 
 * [OASYS group](http://oasys.uma.es) -  groupoasys@gmail.com
 
 ## Developed by 👨‍💻👨‍💻👩‍💻
 * [Salvador Pineda](https://www.researchgate.net/profile/Salvador_Pineda) - spinedamorente@gmail.com
 * [Juan Miguel Morales](https://www.researchgate.net/profile/Juan_Morales25) - juan.morales@uma.es
 * [Asunción Jiménez Cordero](https://www.researchgate.net/profile/Asuncion_Jimenez-Cordero/research) - asuncionjc@uma.es
 
 
 ## License 📝
 
    Copyright 2019 Optimization and Analytics for Sustainable energY Systems (OASYS)

    Licensed under the GNU General Public License, Version 3 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.gnu.org/licenses/gpl-3.0.en.html

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
 
