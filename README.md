# Project README

## Overview
This project focuses on implementing and running different recommendation models including CFIT4SRec, DuoRec, and CL4SRec. Each model has its own specific requirements and instructions for execution.

## Models

### CFIT4SRec
To run the CFIT4SRec model, execute the following command:
```bash
python main_run.py
```

### DuoRec and CL4SRec
To run the DuoRec or CL4SRec models, use the following shell command:
```bash
python run_seq.py --dataset='ml-1m' --train_batch_size=256 --lmd=0.1 --lmd_sem=0.1 --model='CL4SRec' --contrast='us_x' --sim='dot' --tau=1
```
Replace `'CL4SRec'` with `'DuoRec'` if you want to run the DuoRec model.

## Adding Datasets
To add a new dataset, place your dataset in the `dataset` folder of each model. Ensure that the folder name matches the dataset file name.

## Folder Structure
```
/d:/4th Year/DA626/Project/
│
├── CFIT4SRec/
│   ├── main_run.py
│   └── dataset/
│
├── DuoRec/
│   ├── run_seq.py
│   └── dataset/
│
└── CL4SRec/
    ├── run_seq.py
    └── dataset/
```

## Dataset Link
You can find the dataset for the models from this [link](https://drive.google.com/drive/folders/1c9zz2nLL0M9hjDL0hpRBs6_TQ2Ned4LK?usp=sharing).
