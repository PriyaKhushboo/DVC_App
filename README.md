create env

'''bash
conda create -n wineq python=3.7 -y
'''

activate env
'''bash
conda activate wineq
...

create a req file

install the req
'''bash
pip install -r requirements.txt
'''
download the data from

https://drive.google.com/drive/folders/18zqQiCJVgF7uzXgfbIJ-04zgz1ItNfF5?usp=sharing


git init

dvc init

dvc add data_given/winequality.csv

git add .

git commit -m 'first commit'

oneliner updates for readme
git add . && git commit -m 'update Readme.md'

git remote add origin https://github.com/PriyaKhushboo/DVC_App.git
git branch -M main
git push origin main

tox command -
'''bash
tox
'''
for rebuilding -
'''bash
tox -r
'''
pytest command
'''bash
pytest -v
'''

setup commands -
'''bash
pip install -e .
'''

build your own package command -
'''bash
python setup.py sdist bdist_wheel
'''
