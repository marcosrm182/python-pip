# Game project

Para correr el juego debes de seguir las siguientes instrucciones en la terminal.

```sh
cd game
python3 main.py
```

# Pie and Bar project

Para correr este programa debes seguir las siguientes instrucciones en la terminal.

```sh
cd app
source venv/bin/activate
pip3 install -r requirements.txt
python3 main.py
```

Para jecutarlo en docker

```sh
docker-compose build
docker-compose up -d
docker-compose ps  -> Para ver los contenedores que están correindo
docker-compose exec app-csv bash  -> Para entrar en el contenedor en ejecución
exit  -> Para salir del contenedor
docker-compose down  -> Para parar el contenedor
```

# App project

Para correr este programa debes seguir las siguientes instrucciones en la terminal.

```sh
git clone
cd app
python3 -m venv venv
source venv/bin/activate
pip3 install -r requirements.txt
python3 main.py
```

Para jecutarlo en docker

```sh
docker-compose build
docker-compose up -d
docker-compose ps  -> Para ver los contenedores que están correindo
docker-compose exec app-csv bash  -> Para entrar en el contenedor en ejecución
exit  -> Para salir del contenedor
docker-compose down  -> Para parar el contenedor
```