---
layout: default_3dgi18
title: Pre-conference workshop (preparation instructions) | 3D GeoInfo 2018
permalink: /workshop-instructions
---

<!-- <a name="workshop" style="display: block; position: relative; top: -50px; visibility: hidden;"></a> -->

<!-- <div class="alert alert-blue text-center" role="alert">
	The pre-conference workshop is now full. Thank you for your interest!
</div> -->

## Automated reconstruction of 3D City Models and using them in urban applications

### Preparation

A list of software is required in order to follow the workshop. You may find detailed instructions on how to find and install software for your computer prior to the workshop. The list consists of:

- [3dfier](workshop-instructions.html#3dfier)
- [MeshLab](workshop-instructions.html#meshlab)
- [QGIS 3](workshop-instructions.html#qgis3)
- [azul](workshop-instructions.html#azul)
- [val3dity](workshop-instructions.html#val3dity)
- [GDAL](workshop-instructions.html#gdal)
- [Python & cjio](workshop-instructions.html#python-cjio)

<a name="3dfier" style="display: block; position: relative; top: -70px; visibility: hidden;"></a>

#### 3dfier & example data

[3dfier](https://github.com/tudelft3d/3dfier) will be used for the creation of a 3D city model. You have to download the software as well as the example data.

The software can be downloaded from the following links:
- For **Windows 7/8/10 64-bit** you can download [3dfier 1.0.2](https://github.com/tudelft3d/3dfier/releases/download/v1.0.2/3dfier-windows-x64-v1.0.2.zip)
- For **macOS** you can download [3dfier 0.9.7](https://github.com/tudelft3d/3dfier/releases/download/v0.9.7/3dfier-OSX-0.9.7.zip)
- For **Linux** or other versions of Windows you can follow the instruction on the 3dfier [wiki](https://github.com/tudelft3d/3dfier/wiki).

The example data is included in the Windows package. If you downloaded the macOS package, you will find the example data as an individual archive [here](https://github.com/tudelft3d/3dfier/releases/download/example_data/example_data.zip).

<a name="meshlab" style="display: block; position: relative; top: -70px; visibility: hidden;"></a>

#### Meshlab

For simple geometric visualisation we will need a simple 3D viewer. [Meshlab](http://www.meshlab.net/#download) is strongly recommended as it is available for **Windows**, **macOS** and **Linux**.

<a name="qgis3" style="display: block; position: relative; top: -70px; visibility: hidden;"></a>

#### QGIS 3

For the visualisation of datasets and inspection of the data you have to install QGIS version 3.

QGIS 3 is available for all platforms (Windows/macOS/Linux etc.) through the [download page](https://qgis.org/en/site/forusers/download.html) of its website.

- For **Windows** users its suggested that you install through the OSGeo4W Network installer. Download the  [64-bit](http://download.osgeo.org/osgeo4w/osgeo4w-setup-x86_64.exe) or [32-bit](http://download.osgeo.org/osgeo4w/osgeo4w-setup-x86.exe), choose ```Desktop Express Install``` and select ```QGIS```.
- For **macOS** users who use ```homebrew```, you can install QGIS 3 through the ```qgis3``` formula of the [osgeo4mac](https://github.com/OSGeo/homebrew-osgeo4mac) tap. You will have to use the ```--with-3d``` option in order to enable the 3D viewing capabilities of QGIS 3.

*In case you are currently using QGIS 2, you may install QGIS 3 alongside it.*

<a name="azul" style="display: block; position: relative; top: -70px; visibility: hidden;"></a>

#### azul

The [azul](https://github.com/tudelft3d/azul) 3D viewer will be used for the visualisation of 3D city models on macOS. You may download it through the App Store [here](https://itunes.apple.com/nl/app/azul/id1173239678?l=en&mt=12).

<a name="val3dity" style="display: block; position: relative; top: -70px; visibility: hidden;"></a>

#### val3dity

For the validation of the 3D geometries we will use [val3dity](http://geovalidation.bk.tudelft.nl/val3dity/docs/).

There is no need to download it as you may use its online version from [here](http://geovalidation.bk.tudelft.nl/val3dity/).

<a name="gdal" style="display: block; position: relative; top: -70px; visibility: hidden;"></a>

#### GDAL

[GDAL](https://www.gdal.org) will be used for the manipulation and transformation of *CityGML* data. Binaries can we found through it's [download page](https://trac.osgeo.org/gdal/wiki/DownloadingGdalBinaries).

In order to simplify the process, we would suggest the following:
- For **Windows** better use the OSGeo4W Network installer suggested before. As soon as you have installed QGIS 3 through it, there is no need for further action here.
- For **macOS** you can download the package from [here](http://www.kyngchaos.com/software:frameworks) or install it through ```homebrew```. In case ```homebrew``` was used to install QGIS3, GDAL 2 must be already installed.

<a name="python-cjio" style="display: block; position: relative; top: -70px; visibility: hidden;"></a>

#### Python & cjio

[Python](https://www.python.org/) will be used for the manipulation of data through programming. Python is, also, a requirement for [cjio](https://github.com/tudelft3d/cjio), which will be used for the manipulation of *CityJSON* data.

You can download Python 3.5.6 or 3.7 from [here](https://www.python.org/downloads/) and install it according to your operation system. **macOS** users who use ```homebrew``` are encouraged to install the ```python``` formula instead.

After installing Python, you may install cjio with the following command ```pip install cjio```.