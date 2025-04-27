## project setup

1- clone project
```shell
git clone https://github.com/mohammad-pooladi/flask-chat-application.git
```
```shell
cd flask-chat-application
```

2- SetUp venv
``` shell
virtualenv -p python3.12 venv
source venv/bin/activate
```

3- install Dependencies
``` shell
pip install -r requirements_dev.txt
pip install -r requirements.txt
```

4- create your env
``` shell
cp .env.example .env
```

5- Create tables
```shell
python manage.py migrate
```

6- spin off docker compose
```shell
docker compose -f docker-compose.yml up -d
```

7- run the project
```shell
python app.py
```
