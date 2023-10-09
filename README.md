Ingresamos en la carpeta "pagina"

docker build . -t cotizacion //ejecutamos este comando

cd .. //luego volvemos a la carpeta raiz

docker swarm init //Convierte una máquina en el líder de un equipo de contenedores. 

docker stack deploy -c cotizacion.yml cotizacion // Le dice al equipo de contenedores qué hacer y cómo trabajar juntos, utilizando las reglas que se encuentran en el archivo llamado cotizacion.yml.

Ingresar a http://localhost:3000 