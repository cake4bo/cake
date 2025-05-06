# Official code repository for "Kernel Design for Bayesian Optimization Is a Piece of CAKE"

## Setup

1. Create a `secrets.txt` file and provide the OpenAPI key
2. Set up a Conda environment:
```
git clone https://github.com/cakes4bo/cake.git
conda create -n cake python=3.9
conda activate cake
```

3. Install the requirements:
```
pip install -r requirements.txt
```

## Reproducing Results

To reproduce results, execute the following Python scripts:
- To run optimization benchmark: ```python exp.py```
- To run HPOBench benchmark: ```python hpobench_exp.py```
