# invasivemammal_dungbeetle
"Invasive mammals disrupt native dung beetle community coexistence."Code of Akashi et al. 2024 

## Description of the data and file structure

This code is the simulation file for Ryo Akashi, Ryo Yamaguchi, Shinji Nakaoka "Invasive mammals disrupt native dung beetle community coexistence".

## Files and variables

"Akashi et al. 2024 code.ipynb" is the simulation file for creating result and figure.
The resulting diagrams, .pickle files and other results obtained running the code are stored in . /output. If you get an error, create /output in the current directory.

## Code/software

We used ‘Anaconda’ to create the python environment used in this study.
https://www.anaconda.com/download

Go to the site above and install Anaconda.
The environment can then be set up by running the following commands.
Then, using jupyternotebook, select py3912 Kernel and run the code.
please use anaconda to set the environment.

conda create --name py3912 python=3.9.12
conda activate py3912

conda install matplotlib=3.6.2
conda install jupyter=1.0.0
conda install tqdm=4.64.1
conda install pandas=1.5.2
