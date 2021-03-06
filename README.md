# MathGameBot
Game for training math skills based on Telegram Bot API.
The bot asks you math tasks and you have to solve them.
## Bot link
Math Train Bot [@mathtrainbot](https://t.me/mathtrainbot)
## Features
- Using Aiogram Bot API
- SQLAlchemy ORM + SQLite
- Redis for fast cache
- Dockerized using Docker-Compose
- Three difficulty levels to choose

## How to run locally

#### 1) Download project
```bash
$ git clone https://github.com/MagzKr/MathGameBot/
```
#### 2) Set Token
Open file config.py in project folder and set the token you received from [@BotFather](https://t.me/botfather)

#### 3) Build and run app in docker
```bash
$ docker-compose build
$ docker-compose up
```

