# Progressive_web_aplication_PWA


Progressive Web Apps

Acerca de myjson


El servicio myjson permite almacenar información en formato JSON para poder acceder a ella desde cualquier cliente HTTP.

Tareas


En primer lugar, para no repetir el código de lectura/escritura en myjson a lo largo de la aplicación, debe implementar este código en las funciones getAPI y updateAPI. Debe completar estas funciones para que hagan lo siguiente (se recomienda hacer uso de la función fetch de JavaScript):

getAPI: Realiza una petición asíncrona a la URL almacenada en localStorage.URL y devuelve la información recibida.

updateAPI: Realiza une petición asíncrona a la URL almacenada en localStorage.URL y escribe la información que se le pasa en el argumento "peliculas"

Una vez implementadas estas funciones, se pide modificar el código proporcionado para completar las cinco funcionalidades que faltan. Haga uso de las funciones getAPI y updateAPI. Como se ha dicho, puede reutilizar todo el código que considere conveniente de su solución de la entrega 2:

Show: Mostrar información sobre la película.

New: Mostrar el formulario de añadir una nueva película.

Create: Añade una nueva película al modelo.

Delete: Elimina una película del modelo. Debe pedir la confirmación del usuario.

Reset: Restaura el modelo al estado inicial, guardando las tres películas iniciales en localStorage.

Objetivos


Transformar una aplicación web en una PWA. Entender la potencia de las PWA y todas las posibilidades que ofrecen.

Arrancar la aplicación web El fichero server.js contiene un servidor muy simple que tan solo sirve archivos estáticos que se encuentren en la carpeta "public" y redirige el tráfico http a https (condición indispensable para las PWAs). Para ejecutar dicho servidor y poder ver nuestra aplicación web funcionando ejecutamos:

$ npm start
