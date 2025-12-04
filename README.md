# Intro to Scientific Data Management with DataLad

**Date**: December 5th, 2025
**Instructor**: Dr. Ole Bialas

## Installation 

**STEP 1: Clone this repository**

```
git clone https://github.com/ibehave-ibots/iBOTS-Intro-to-Scientific-Data-Management-with-DataLad-Dec25.git
cd iBOTS-Intro-to-Scientific-Data-Management-with-DataLad-Dec25
```

**STEP 2: Install the environment**

with pixi:
```
pixi run install-kernel
pixi shell
```
or conda:
```
conda env create -f environment.yml
conda activate ibots-datalad
```

**STEP 3: Test DataLad availability**
```
datalad wtf
```

If you have trouble installing the environment on your machine you can run all notebooks in Google Colab as well (link at the beginning of each notebook).

## Agenda

1. Working with DataLad Datasets
2. Creating a Dataset from Scratch
3. Creating Siblings
4. Running Commands and Pipelines