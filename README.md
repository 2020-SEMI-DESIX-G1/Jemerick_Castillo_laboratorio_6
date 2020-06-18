# Jemerick Castillo - Laboratorio #6

###  Objetivos

* Demostrar que el estudiante puede ejecutar código de NPM al instalar ExpressJS.

* Demostrar que el estudiante puede escribir endpoints usando ExpressJS.

* Demostrar que el estudiante puede consumir endpoints usando Postman.

#  Escribir un API que contemple las peticiones tipo GET, POST, PUT y DELETE usando ExpressJS sobre la entidad "Estudiantes".

### Las rutas deben ser las siguientes:

* [GET] /estudiantes/  (Retorna la lista completa de estudiantes almacenados)

* [POST] /estudiantes/ (Crea un nuevo estudiante y lo agrega a la lista de estudiantes)

* [GET] /estudiantes/<id> (Retorna a un estudiante específico basado en el id recibido)

* [PUT] /estudiantes/<id> (Actualiza uno o más campos de un estudiante específico basado en el id recibido)

* [DELETE] /estudiantes/<id> (Elimina un estudiante de la lista de estudiantes basado en el id recibido)


###  Notas

* No se debe utilizar base de datos de ningún tipo. La almacenación de los datos ha de ser en un arreglo básico de javascript. Esto implica que luego de que se apague el servidor, tendrán que llenar todo nuevamente de cero.

* El código ha de ser ejecutado usando docker (No docker-compose, solo docker)

* Se debe probar usando Postman, curl o similar.

* Docker debe ser ejecutado dentro de la máquina virtual con la que hemos trabajado hasta el momento.

* El proyecto es individual.