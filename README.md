# Laboratorio 1 - HTTP

El laboratorio consiste en revisar varias de las características de HTTP 
utilizando **Nginx** como servidor y **httpie** como cliente.

## Prerequisitos

* docker 19 o superior
* docker-compose 1.3 o superior
* Mac OS/Linux/Windows con WSL2
* Terminal bash o zsh

## Práctica

Instala [httpie](https://httpie.org/):

```bash
apt-get install httpie
```

Prueba la instalación ejecutando 

```bash
http https://example.com/
```

El resultado del comando debería ser algo similar a esto:
![](images/http-example-response.png)

