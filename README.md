🚀Instrucciones para inciar el server🚀

1 - Instalar Node
Se va a necesitar nodejs. Puedes comprobar si ya se encuentra instalado en tu sistema mediante el comando

node -v

En el caso de no tenerlo instalado, descargar e instalar nodeJS.

2 - Clonar proyecto e instalación de dependencias

Clonar el proyecto de Github: https://github.com/assr1998/proyecto3

3 - Creación e inicializacion base de datos

Descargar e instalar XAMPP

Ejecutar XAMPP u otro programa de MySQL y Apache.

Importar la base de datos "database.sql" que se está dentro de la carpeta "database" en la raiz del proyecto (contiene la creacion de tablas en mysql 
y la insercion de datos de prueba para la verificacion del correcto funcionamiento del API)

Abrir una consola en la carpeta donde se clono el repositorio

instalar las dependecias del proyecto en node js, con el comando npm install

Para configurar los datos de acceso a la base de datos abrir el archivo config.js dentro de /src/config y 
verificar que los datos de acceso a la base de datos sean correctos

4 - Iniciando el servidor

Iniciar el proyecto con el comando npm run start para iniciar el servidor o con el comando npm run dev para iniciarlo en modo desarrollo

Se muestra en la consola el mensaje "server on port 3000"

El servidor se encuentra corriendo en la direccion: http://localhost:3000

5 - Test API 

En la carpeta "postman_collection" se encuentra el archivo de exportacion de la coleccion de peticiones de postman con las pruebas de las peticiones que se pueden realizar al API, este archivo puede ser importado en postman para verificar el correcto funcionamiento de la misma.

En la raiz del proyecto se encuentra el archivo spec.yml en donde se encuentra la documentacion del API en Open API.

**Endpoints**
· El archivo "spec.yaml" contiene la documentación sobre los endpoints de la aplicación y sus respuestas.

· El archivo "postman_collection.json" contiene los JSON's necesarios para realizar las pruebas dentro de Postman.

/productos

/pedidos

/usuarios
