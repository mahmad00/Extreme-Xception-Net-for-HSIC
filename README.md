# Extreme-Xception-Net-for-HSIC

## Reference

This code is used for our research paper in IEEE Transactions on Geoscience and Remote Sensing:
> U. Ghous, et.al., "*(2+1)D Extreme Xception Net for Hyperspectral Image Classification*," submitted to IEEE Transactions on Geoscience and Remote Sensing, 2023.


## Requirements

This tool is compatible with Python 2.7 and Python 3.5+ and executed over Colab.

## Hyperspectral datasets

Several public hyperspectral datasets are available on the [EHU]([http://www.ehu.eus/ccwintco/index.php?title=Hyperspectral_Remote_Sensing_Scenes](https://www.ehu.eus/ccwintco/index.php/Hyperspectral_Remote_Sensing_Scenes)). Users can download those beforehand or let the tool download the dataset for them. 

At this time, the tool automatically downloads the following public datasets:
  * Indian Pines

An example dataset folder has the following structure:
```
Datasets
├── Botswana
│   ├── Botswana_gt.mat
│   └── Botswana.mat
├── IndianPines
│   ├── Indian_pines_corrected.mat
│   ├── Indian_pines_gt.mat
├── Salinas
│   ├── Salinas_gt.mat
│   └── Salinas.mat
├── PaviaU
│   ├── PaviaU_gt.mat
│   └── PaviaU.mat
```

### RESEARCH AND NON-COMMERCIAL PURPOSES
