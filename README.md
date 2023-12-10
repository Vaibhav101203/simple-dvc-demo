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

git add .

git commit -m "first commit"

onliner updates for readme 
git add . && git commit -m "update Readme.md"

git remote add origin https://github.com/Vaibhav101203/simple-dvc-demo.git

git branch -M main

git push origin main 