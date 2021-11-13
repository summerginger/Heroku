# Heroku
### 1st part step create the new enviornment base
conda create -n pet_pals python=3.8.5
conda activate pet_pals
clear
### 2nd part install all the things 
pip install flask
pip install flask-sqlalchemy
pip install pandas
pip install gunicorn (# productive server)
pip install psycopg2 (# because usinig database)
clear
### 3rd part open terminal in vscode
pip freeze > requirement.txt
### run the python initdb.py in terminal
python initdb.py
./run.sh (if denied) then
chmod a-x run.sh
./run.sh
4 - open api route api/pals to see the json file automatically recorded
5- create procfile is to tell heroku how to run the application