# An introduction to geodata in Python

### Level: Beginner

### Presentation: [An introduction to geodata in Python](workshop/an_introduction_to_geodata_in_python.pdf)

## Workshop description

In this workshop, you will learn the basics of geospatial data theory, covering raster, vector, and related concepts. You will also be introduced to Python libraries for geospatial data and gain hands-on experience working with satellite imagery through a Jupyter notebook exercise.

## Requirements

- your GitHub account
- [miniconda](https://docs.conda.io/en/latest/miniconda.html) or [anaconda](https://www.anaconda.com/products/individual)

### How to install miniconda

#### For Linux users

```bash
mkdir -p ~/miniconda3
wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh -O ~/miniconda3/miniconda.sh
bash ~/miniconda3/miniconda.sh -b -u -p ~/miniconda3
rm -rf ~/miniconda3/miniconda.sh
```

After installing, initialize your newly-installed Miniconda. The following commands initialize for bash shell:

```bash
~/miniconda3/bin/conda init bash
```

#### For MacOs users

```bash
mkdir -p ~/miniconda3
curl https://repo.anaconda.com/miniconda/Miniconda3-latest-MacOSX-arm64.sh -o ~/miniconda3/miniconda.sh
bash ~/miniconda3/miniconda.sh -b -u -p ~/miniconda3
rm -rf ~/miniconda3/miniconda.sh
```

After installing, initialize your newly-installed Miniconda. The following commands initialize for bash shell:

```bash
~/miniconda3/bin/conda init bash
```

#### For Windows user

```bash
curl https://repo.anaconda.com/miniconda/Miniconda3-latest-Windows-x86_64.exe -o miniconda.exe
start /wait "" miniconda.exe /S
del miniconda.exe
```

## Usage

### Before the workshop

* Clone this repository

* Navigate to cloned repository via terminal (use "Anaconda Prompt (miniconda3)" program for Windows/anaconda users)

* ```bash
  cd geodata-in-python-oct2023
  ```

* Create conda enviroment 

  ```bash
  conda env create -f conda_environment.yml
  ```

* Activate conda environment

  ```bash
  conda activate geodata_in_python
  ```

* Add the created conda environment to Jupyter Lab

  ```bash
  python -s -m ipykernel install --user --name=geodata_in_python
  ```

* Start Jupyter Lab

  ```bash
  jupyter lab
  ```

### After the workshop

If you would like to clean up the conda environment after the workshop, run the following lines in your terminal (use "Anaconda Prompt (miniconda3)" program for Windows/anaconda users):

```bash
jupyter kernelspec uninstall geodata_in_python
conda deactivate
conda env remove --name geodata_in_python
```

## Video record

Re-watch [this YouTube stream](https://www.youtube.com/live/9RqFBbQGq_Y?feature=shared)

## Credits

This workshop was set up by @pyladiesams, @amridderikhoff and @AmberMulder
