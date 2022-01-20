# Visualization of Public Transit Users' Patterns

This repository aims to develop effective visualization technique for public transit users' patterns
Based on [Unfolded](https://www.unfolded.ai/), spatiotemporal movements of transit users' are represented with their estimated qualitative attributes (e.g., trip purposes and socioeconomic factors)


## Overview

Spatiotemporal patterns of transit users' trips according to activity duration and trip purposes are visualized. Trip purposes of smart card data are esitimated using [DF-CGAN](https://github.com/Eui-Jin/CGAN-DF)
<img width="80%" src="https://user-images.githubusercontent.com/97636336/150331088-cdba9bc0-420c-4d14-b45f-13c4539b50ad.gif"/>

## Getting Started

### Dependencies
* Python 3.6.10, Jupyter lab 3.3.0

### Components

#### Dataset
* 'Data' contains the sampled smart card data with trip purposes 'ActivityPattern.csv'
* Other dataset is used to generate the 'ActivityPattern.csv' using 'DataPreprocesing.ipynb' and 'DF-CGAN-Output.ipynb'. More details are provided in [DF-CGAN](https://github.com/Eui-Jin/CGAN-DF)

##### DataPreprocessing.ipynb
* DataPreprocessing transforms the trip-chain attributes into sequential ndarray to use for Tensorflow
* Detailed descriptions are provided in the notebook files.

##### Visualization_Unfolded.ipynb
* Step-by-step implementation of visualization using unfolded
* Spatial and time-line analysis are presented 
* Need to be updated...

##### 'DataPreprocesing.ipynb' and 'DF-CGAN-Output.ipynb'
* This code generates the 'ActivityPattern.csv'. Please refer [DF-CGAN](https://github.com/Eui-Jin/CGAN-DF)

## Authors

[@Eui-Jin Kim](https://sites.google.com/view/euijinkim)


## License

This project is licensed under the MIT License - see the LICENSE.md file for details

## Acknowledgments
* [DF-CGAN](https://github.com/Eui-Jin/CGAN-DF)
* [Unfolded](https://github.com/UnfoldedInc)
