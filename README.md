# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

# Acerca de

Este proyecto es una primera toma de contacto con REACT. 
Es un carrito de compras el cual fue realizado utilizando componentes basados en clases. 
Adicionalmente se integra Docker para poder levantar el proyecto en un contenedor de Node.

# INSTALACION

- <a href="https://docs.docker.com/engine/install/" target="_blank">Docker</a>
- <a href="https://docs.docker.com/compose/install/" target="_blank"> Docker Compose </a>
- <a href="https://git-scm.com/book/en/v2/Getting-Started-Installing-Git" target="_blank">Git</a>

Una vez instalado Docker y Git se debe ejecutar el siguiente comando:<br>
- <b>git clone https://github.com/guilleMontiel/carritocompraReact.git</b>
<br>
Al finalizar se debe abrir una terminal y navegar hasta el directorio donde se encuentra el proyecto clonado. Luego ejecutar:<br><br>
- <b> docker-compose run --rm carritocompraReact npm install (por primera vez)</b><br>
- <b> docker-compose up (para levantar el servidor con el proyecto)</b><br>
<br>
Es importante no cerrar la terminal ya que el servidor dejara de funcionar. <br>
Para detener el contenedor, simplemente ejecutar en la misma terminal donde esta corriendo el servidor la combinacion <b>CTRL+C</b> 

# ENTRAR AL SISTEMA

http://localhost:3000
