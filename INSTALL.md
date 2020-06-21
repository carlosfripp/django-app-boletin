## Instalacion

Para instalar este mini proyecto, primero debemos crear nuestro entorno virtual, ejecutando el siguiente comando:

~~~
virtualenv pd110 
~~~

Luego de crear nuestro entorno virtual, activamos el mismo ingresando al directorio del proyecto pd110 y desde ahi ejecutamos el siguiente comando:

~~~
pd110\Scripts\activate
~~~

 Y ya estaremos dentro de nuestro entorno virtual.

Desde el directorio del proyecto, clonamos el proyecto:

~~~
git clone https://github.com/carlosfripp/django-app-boletin.git
~~~

Para que el proyecto funcione, debemos instalar las siguientes librerias:

* Django
  
  ~~~
  pip install django==1.10.6
  ~~~

* Forms Crispy

  ~~~
  pip install django-crispy-forms
  ~~~

* Django - Registration - Redux

  ~~~
  pip install django-registration-redux==1.4
  ~~~

## Rutas

En este proyecto contamos con las siguientes rutas:

* Admin
    
    Ruta para administrar las cuentas de los usuarios.

* Contact

    Ruta para poder resgistrar un comentario.

* About

    Ruta de prueba, donde describe un poco acerca de este boletin.

* Accounts

    Ruta donde podemos registrarnos y loguearnos.