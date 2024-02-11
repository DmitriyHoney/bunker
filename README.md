## Инициализация
```sh
 git clone https://github.com/DmitriyHoney/bunker.git
```
```sh
 git submodule update --init --recursive
```
 - убедиться, что во frontend, backend, и в корне ветка master
 - Создать в корне файл .env на подобии .env.example
```sh
docker-compose up -d --build
```

- перейти в директорию бекенда
- запустить скрипт через bash ./first_init.sh (генерирует сертификаты) 
- зайти в терминал бекенда из контейнера и провести миграции
```
alembic upgrade head 
```

P.S миграции создавать не нужно, только проводить
