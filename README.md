# Large Language Model-based Human-Agent Collaboration for Complex Task Solving
This repository is based on our paper: "Large Language Model-based Human-Agent Collaboration for Complex Task Solvin". It contains the human-computer collaboration dataset we generated, as well as demo code for our fine-tuned human-agent collaboration policy model.   
<div  align="center">    
<img src="./pic/pic4.png" width = "600" height = "400" alt="pic" align=center />
</div>

## Overview
- Task
  - dataset collected in `data_produce/`
  - train data in `data/`
  - start training by `scripts/run.sh`
  - local test environment is in `test_data/`
- Human-Agent Collaboration Dataset in `dataset/`

## Usage
### Prepare
You can use following scripts to install related python package through pip:
```
git clone https://github.com/XueyangFeng/ReHAC.git
cd ReHAC
pip install -r requirements.txt
```
### Training and Test
```
cd hotpotqa/scripts
sh run.sh
```
We will automatically test this in training through a local simulation environment with callback functions.

## Results
