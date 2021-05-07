# Data analysis
- Document here the project: Movie_Industry_Kaggle
- Description: Analyse Kaggle's movie industry dataset to extract insights on how to maximize profit.
- Data Source: https://www.kaggle.com/danielgrijalvas/movies
- Type of analysis: Exploratory



# Startup the project

The initial setup.

Create virtualenv and install the project:
```bash
sudo apt-get install virtualenv python-pip python-dev
deactivate; virtualenv ~/venv ; source ~/venv/bin/activate ;\
    pip install pip -U; pip install -r requirements.txt
```

Unittest test:
```bash
make clean install test
```

Check for Movie_Industry_Kaggle in gitlab.com/{group}.
If your project is not set please add it:

- Create a new project on `gitlab.com/{group}/Movie_Industry_Kaggle`
- Then populate it:

```bash
##   e.g. if group is "{group}" and project_name is "Movie_Industry_Kaggle"
git remote add origin git@github.com:{group}/Movie_Industry_Kaggle.git
git push -u origin master
git push -u origin --tags
```

Functionnal test with a script:

```bash
cd
mkdir tmp
cd tmp
Movie_Industry_Kaggle-run
```

# Install

Go to `https://github.com/{group}/Movie_Industry_Kaggle` to see the project, manage issues,
setup you ssh public key, ...

Create a python3 virtualenv and activate it:

```bash
sudo apt-get install virtualenv python-pip python-dev
deactivate; virtualenv -ppython3 ~/venv ; source ~/venv/bin/activate
```

Clone the project and install it:

```bash
git clone git@github.com:{group}/Movie_Industry_Kaggle.git
cd Movie_Industry_Kaggle
pip install -r requirements.txt
make clean install test                # install and test
```
Functionnal test with a script:

```bash
cd
mkdir tmp
cd tmp
Movie_Industry_Kaggle-run
```
