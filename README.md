# CitiTraining

# quick installation start

git init

git remote add upstream git@github.com:Jay-Keww/CitiTraining.git

py -m venv venv

venv\Scripts\activate

pip install -r requirements.txt

# commands to write for setting up

python3 -m venv venv

# start the virtual environment

venv\Scripts\activate

# to deactivate the virual environment

deactivate

# command to update the dependency used

python -m pip freeze > requirements.txt

# github work flow

## how to get changes from JQ's repo

git fetch upstream

git merge upstream/main
