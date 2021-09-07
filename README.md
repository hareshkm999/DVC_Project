created conda environment
--conda create -n DVC_Project python=3.7 -y

Activated Environment using

--conda activate DVC_Project

Created Requirements.txt file

download the data from

https://drive.google.com/drive/folders/18zqQiCJVgF7uzXgfbIJ-04zgz1ItNfF5?usp=sharing

git init

dvc init 

dvc add data_given/winequality.csv

git commit -m "first commit"

oneliner updates for readme

git add . && git commit -m "update Readme.md"


git remote add origin https://github.com/hareshkm999/DVC_Project.git
git branch -M main
git push origin main

git add . && git commit -m "adding get_data function"
git push origin main

