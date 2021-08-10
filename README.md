# Github Actions

Realizar un proyecto DevOps con GitHub Actions.

# Primer Paso

Vamos a crear los secretos, para poder hacer el push a nuestro Docker Regestry. En esta caso Docker Hub. El el proyecto GitHub vamos a Settings->Secrets.

Agregamos DOCKERHUB_USERNAME y DOCKERHUB_TOKEN. Para conseguir nuestro Token de Docker Hub, lo haremos en la Web en el apartado Account Settings->Security.

Deberia quedarnos, asi.

### Token Docker Hub

<p align="center">
<img src="screenshots/Token_DockerHub.png" width="800" >
</p>

### Secrets GitHub

<p align="center">
<img src="screenshots/Secrets_Github.png" width="800" >
</p>

### Secrets Okteto

Vamos a utilizar un cluster free, como Okteto, para jugar. Descargamos la configuracion y creamos el secreto. Primero vamos a pasarlo a Base64 y luego cargarlo.

<p align="center">
<img src="screenshots/Base64.png" width="800" >
</p>

Agregamos el Output

<p align="center">
<img src="screenshots/Okteto.png" width="800" >
</p>

