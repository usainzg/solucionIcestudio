# solucionIcestudio
## Solucion temporal a introducir constantemente la pass en mac:

La solucion es muy sencilla, se trata de crear un applescript que ejecute la app con permisos de root. Sin necesidad de meter la contraseña en ningun momento ( solo al crear el script ).

Subo el archivo necesario, donde tendreis que sustituir los datos del *username* y la *passsword*.

Para editar estos datos:

* Descargar la aplicacion "ñapaFPGA".
* Boton derecho.
* Mostrar el contenido del paquete.
* Resources/Scripts.
* Abrir "main.scpt" con Editor de Scripts.
* Donde pone **unaisainz**, poned vuestro *username*
* Donde pone **mofeta**, poned vuestro *password*
* Guardar.
* Ahora solo tendreís que ejecutar la aplicación "ñapaFPGA", que es como ejecutar Icestudio con permisos de root. Y no deberia de pediros nunca la mas la password.


