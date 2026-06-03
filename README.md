<div align="center">

# JD KING SPOTIFY


<img width="377" height="395" alt="Captura de pantalla 2026-06-03 103107" src="https://github.com/user-attachments/assets/19568ffa-36c3-44bf-97a8-e03d01138e21" />


</div>
<br>
<br> 

## DESCRIPCIÓN DE LA APLICACIÓN

He creado una aplicación de música similar a Spotify para tratar de escuchar las canciones que yo quiera. Para crear esta aplicación he necesitado configurar la autenticación oAuth con las APIs de Google y de Spotify. Además, he implementado una base de datos con PHPMyadmin en el que almaceno las canciones, artistas, álbumes, playlists, etc... Este proyecto lo he realizado tanto en móvil con la aplicación de Termux como en el ordenador. Espero que os guste este proyecto y lo podáis replicar. 


<br>


## CREACIÓN DE LA APLICACIÓN

<br>

- Primero, descargamos Termux en nuestro dispositivo móvil.

<br>

<img width="377" height="470" alt="Captura2" src="https://github.com/user-attachments/assets/ea1e93fb-6e0d-4e29-9b1f-f6f0aaf4e20c" />


<br>
<br>

- Una vez entrado a la aplicación usamos los mismos comandos que en Linux. Primero, actualizo los repositorios y después instalo Apache, MariaDB y MySQL.

 ```bash
#  Actualizo los repositorios y después instalo Apache, MariaDB y MySQL.

 sudo apt update
 sudo apt install apache2 php php-apache mariadb -y

```

