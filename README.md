# AlasDePapel
Repositorio para el proyecto Alas de Papel

Proyecto para la materia de Infraestructura y Desarrollo Web. Grupo 10-11AM. Instituto Tecnológico de Tepic.
Integrantes:
Alfonso Aldair Rangel Cantabrana  17401056
Omar Oswaldo Rivera Flores	      17401062
Keiry Yoseli Rodriguez Gonzalez   17401066
Ximena Verdín Carreño             17401092

Para correr el proyecto:
  Primero hacer un npm install y nmp start a la carpeta libreria-alasdepapel-api-master, desde la terminal de VisualStudioCode.
  Posteriormente hacer un npm install y npm start a la carpeta libreria-alasdepapel-web-master, desde la terminal de VisualStudioCode.
  Acceder a http://localhost:4200/inicio

Comandos en Postman
  Para la creación del usuario:
    En el método POST, con la dirección: http://localhost:3002/api/v1/user/signup, Body:raw y tipo JSON:
        {
          "name":"nombre del usuario",
          "email":"email con dominio",
          "password":"contraseña de 7+ digitos"
        }
   
    Para la creación de las categorías:
    En el método POST, con la dirección: http://localhost:3002/api/v1/category/create, Body:raw y tipo JSON:
        {
          "name":"nombre de la categoria",
        }
    
