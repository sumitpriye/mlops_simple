1. First Create the env for project
conda create -n wineq python=3.10 -y
location where env is created-environment location: C:\Users\lenovo\Anaconda3\envs\wineq
2. Activate the created env 
conda activate wineq
3. Create requirements.txt file and add the libraries required for this project
echo req > requirements.txt
4. Run the below command for completing the installation of the required libraries
pip install -r requirements.txt
5. Create the template.py file for the folder structure of the project
6. Run the template.py file to craete the required directories as per the template file
7. Download the data from https://drive.google.com/drive/folders/18zqQiCJVgF7uzXgfbIJ-04zgz1ItNfF5
8.  git init
9. dvc init
10. dvc add  data_given\winequality.csv
11. git add.
12. git commit -m "First commit"
13. git remote add origin https://github.com/sumitpriye/mlops_simple.git
14. git branch -M main
15. git push -u origin main
```bash
git 
```

```commandline
Added get_data.py file to read the data
```
build your own package commands-
```bash 
python setup.py sdist bdist_wheel
```

setup commands -
```bash 
pip install -e . 
```

pytest command -
```bash 
pytest -v
```

for rebuilding -
```bash 
tox -r 
```

tox command - 
```bash
tox
```

