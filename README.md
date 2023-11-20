# Dyalloc

Dyalloc is an automatic and adaptive resource partitioner 
for spatial accelerators with meta reinforcement learning.
This repository contains the source code for Dyalloc.

### Setup ###
* Download the Dyalloc source code 

* Create virtual environment through anaconda
```
conda create --name DyallocEnv python=3.8
conda activate DyallocEnv
```
* Install packages
   
```
pip install -r requirements.txt
```

* Install [MAESTRO](https://github.com/maestro-project/maestro.git)
```
python build.py
```

### Run Dyalloc ###

* Run Autoalloc on cloud and edge platforms
```
./run_auto_cloud.sh  ./run_auto_edge.sh
```

* Run Adaptalloc on cloud and edge platforms
```
./run_adapt_cloud.sh  ./run_adapt_edge.sh
```

