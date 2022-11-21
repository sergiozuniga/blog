# Blog
Una plataforma de blogs web de código abierto construida con Python y Django.

## Características

* Tablero para Autores
* Editor WYSIWYG
* Verificación de la cuenta
* Inicio de sesión del autor
* Restablecimiento de contraseña de autor
* API para Clientes
* Lista de categoría
* Lista de artículos de categoría
* Envío de nueva categoría
* Artículos relacionados
* Comentarios
* Búsqueda de artículos
* Compartir artículo en redes sociales
* Minuto de artículo leído
* Número de artículo de palabras
* Artículo Número de Vistas
* Etiquetas de artículos
* Etiquetar artículos relacionados
* Soporte de rebajas
* Sensible en todos los dispositivos
* Paginación
* Código limpio
* 90% de cobertura de prueba


## Tecnologías
* Python 3
* Javascript
* Jquery
* PrismJS
* Django 3
* HTML5
* CSS3 
* Bootstrap 4
* Ion Icons
* Font awesome
* CKEditor
* MySQL


## Configuración

Para ejecutar esta aplicación, deberá seguir estos 3 pasos:


#### 1. Requerimientos

  - Un computador

  - Editor de Texto o IDE (pej. VScode, PyCharm)
  
  - Git instalado
  
  - Python instalado
  
  - Pip instalado


#### 2. Configuración local y ejecución en Windows, Linux y Mac OS

  # Clone este repositorio en el directorio de su elección
  $ git clone https://github.com/sergiozuniga/blog.git

  # Mover a la carpeta del proyecto
  $ cd blog

  # Inicializar un nuevo entorno virtual
  $ python3 -m venv .env

  # Activar el entorno virtual
  $ source .env/bin/activate

  # Instalar paquetes de python
  $ pip3 install -r requirements.txt
  
  # Ejecutar el cliente mysql
  $ mysql -u root -p

  # Crear base de datos en MySQL
  mysql> create database mydb;
  
  # Crear tablas de base de datos
  $ python3 manage.py migrate
  
  # Crear una cuena de super usuario
  $ python3 manage.py createsuperuser

  # Iniciar servidor
  $ python3 manage.py runserver
  
  # Copiar la dirección IP provista una vez que su servidor haya completado la construcción del sitio. (Dirá algo como >> Sirviendo en 127.0.0.1....).
  
  # Abrir la dirección en el navegador.
  >>> http://127.0.0.1:XXXX
  
  # Iniciar sesión en Tablero para escribir artículos
  >>> http://127.0.0.1:8000/author/dashboard/home/
  
  # Django Admin
  >>> http://127.0.0.1:XXXX/admin/
  

## Licencia

Este proyecto está autorizado según los términos de la licencia **MIT**.


