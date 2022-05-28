Created env
```bash
conda create -n wineq python=3.8 -y
```

Activate env
```bash
activate wineq
```

Created a requirements.txt file

Installed the requirements
```bash
pip install -r requirements.txt
```

We used template.py to create a cookiecutter structure for our project

Download the dataset from [here](https://drive.google.com/drive/folders/18zqQiCJVgF7uzXgfbIJ-04zgz1ItNfF5?usp=sharing)


Initialize GIT and DVC and add data to DVC for tracking
```bash
git init
dvc init
dvc add data_given/winequality.csv
```

Add the project to git
```bash
git add .
```

Create our first commit
```bash 
git commit -m "first commit"
```

Pushing the project to GitHub
```bash
git remote add origin https://github.com/taeefnajib/Wine_Quality_Prediction.git
git branch -M main
git push -u origin main
```

Whever you get an error- fatal: remote origin already exists. Try the code below:
```git remote remove origin```


