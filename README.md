# Docker 🐳


La esencia y punto fuertie de Docker radica en su capacidad para aislar aplicaciones, asegurando que estas funcionen de manera consistente en diferentes sistemasoperativos o entornos, resolviendo así la clásica situación de "en mi máquina sí funciona".


## Comandos Docker 

1. Hacer Pull a imagen 

```bash
docker pull <nombre_image>
```

2. Desplegar imágenes que hay

```bash
docker images
```

3. Correr imagen 

```bash
docker run <id_imagen>
```

4. Ver Contenedores

```bash
docker container ls -a
```

5. Borrar contenedor

```bash 
docker container rm <id_container>
```

6. Obtener Documentación

Ejemplo:

```bash
docker container --help
``` 
