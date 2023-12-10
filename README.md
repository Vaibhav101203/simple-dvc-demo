ECHO is on.

create env 

''' conda 
conda create -n wineq python=3.7 -y
'''

activate env
''' bash 
conda activate wineq
'''

create a requirements file 

'''install
pip install -r requirements.txt 
'''
download the data from 

https://drive.google.com/drive/folders/18zqQiCJVgF7uzXgfbIJ-04zgz1ItNfF5

conda install git

git init 

conda config --add channels conda-forge
conda config --set channel_priority strict

dvc init 

dvc add data_given/winequality.csv
