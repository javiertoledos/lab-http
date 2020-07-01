# Laboratorio 1 - HTTP

El laboratorio consiste en revisar varias de las características de HTTP 
utilizando **Nginx** como servidor y **httpie** como cliente.

## Prerequisitos

* docker 19 o superior
* docker-compose 1.3 o superior
* Mac OS/Linux/Windows con WSL2
* Terminal bash o zsh

## Práctica

### Instalando un cliente de consola
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

La línea de status indica la versión de protocolo y el codigo de la respuesta,
en este caso, el código 200 representa una respuesta de éxito. Las líneas de
header representan metainformación de la respuesta como el tipo de contenido
e información de caché. Finalmente el contenido de la respuesta puede ser
cualquier información arbitraria, en este caso en específico es un documento
html.