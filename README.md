# Act. de Docker

Aquí están las intrucciones de cómo hacer uso de esta imagen de Docker.
En este se imprime un 'Hello World' en ExpressJS.

## Ejecución

Para ejecutarlo debes de correr los siguientes comandos

```bash
docker build -t node-docker .
```
Después este

```bash
docker run -it -p 8000:3000 node-docker 
```
Después abrir http://localhost:8000/
