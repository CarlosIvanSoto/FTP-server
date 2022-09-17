# FTP-server
A dockerized SVFTPD server

## Requirements

- Docker
- Docker Compose

Comandos
=============
Se puede ejecutarse de forma fácil usando Docker y
Docker-compose. Para ello, ejecutar::

    # Clonar proyecto
    git clone https://github.com/CarlosIvanSoto/FTP-server.git
    cd FTP-server
    # Levantar servicios svftpd del docker-compose. Escuchará en el puerto 21.
    docker-compose up -d

Si el puerto ``21`` esta disponible en la máquina, el proyecto estará disponible en `localhost <http://localhost/>`_.

## Credits

- Carlos Ivan Soto Perez

> Copyright (c) GAMEUE
