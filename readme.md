create env
```bash
conda create -n BackOrder python=3.7 -y
```
activate env
```bash
conda activate BackOrder
```
created a req file

install the req
```bash
pip install -r requirements.txt
```
```bash
git init
```
```bash
dvc init
```
```bash
dvc add data_given/BBC News Train.csv
```
```bash
git add .
```
```bash
git commit -m "first commit"
```
```bash
git remote add origin https://github.com/JEEVANARANDE/NEWARTICLES.git
```
```bash
git add . && git commit -m "Update_Readme.md" && git push -u origin main
```