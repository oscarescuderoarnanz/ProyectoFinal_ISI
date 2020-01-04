# ProyectoFinal_ISI
Para realizar las pruebas antes de hacer un pull request he realizado
un despliegue auxiliar en travis, por tanto, la forma que he encontrado
para hacer esto es:

1) Creamos las funcionalidades en la rama funcionalidad

2) Una vez creada, copiar el contenido de esta rama en:
	https://github.com/oscarescuderoarnanz/DespliegueAux.git
	
3) Comprobar que funciona correctamente en travis (creo que al ser
mi cuenta solo puedo verlo yo si ha habido error, pues no vamos a 
usar pull request)

4) si todo okey se hace pull request 

URL despliegue: https://appauxpruebas.herokuapp.com/

Conexion a postgresql de travis desde terminal:
	heroku pg:psql -a appauxpruebas
