# Mark Minervini Stock Screener
Mark Minervini's 8 principles stock scanning


### (Miniconda) Conda installation 

see installation details detail for miniconda  [here](https://docs.conda.io/projects/conda/en/latest/user-guide/install/)

#### MacOS and Ubuntu 

```
# MacOS:
wget https://repo.anaconda.com/miniconda/Miniconda3-latest-MacOSX-x86_64.sh 

# Linux 
wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
```

#### Window install 

Download exe from [here](https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh)


## Installing the app

```
## clone the repo
git clone https://github.com/icedevil2001/mark_minervini_stock_screener.git

cd mark_minervini_stock_screener 
conda env create -f environment.yaml

```

## How to run:
```
conda activate stock-screener

streamlit run stock_screener.py

```

