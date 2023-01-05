# Subir contenedor

Una vez modificado nuestro contenedor a nuestra conveniencia podemos subirlo a docker hub para distribuirlo de formo cómoda.

Primero accedemos a docker hub mediante la aplicación de escritorio o la terminal.

Despues convertimos el contenedor a una imagen que se guardará en la maquina local, usando la nomenclatura de docker, mediante el comando en terminal

```
docker commit CONTAINER ID Usuario/imagen:tag
```

Tanto el CONTAINER ID como el Usuario/imagen:tag dependerá de cada caso y generalmente será diferente.

Una vez creada la imagen localmente la subimos a docker hub con el siguiente comando

```
docker push Usuario/imagen:tag
```

Corroboramos que la imagen este en nuestra cuenda de docker hub