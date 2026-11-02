BACK END EN NODE.JS
tenemos uyb con autenticacion y ENDPINTS protegidos 

Para iniciar abrimos la terminal y ejecutamos con NPM 
np_install

luego se inicia el servidor con npm start

POST /api/users Crear usuario (crearUser) No
POST /api/users/login Iniciar sesión y devolver el JWT (loginUser) No
GET /api/users/datos Datos del usuario dueño del token (datosUser) Sí
GET /api/tareas Listar solo las tareas del usuario logueado (getTareas) Sí
POST /api/tareas Crear una tarea asignada al usuario logueado
(createTareas)
Sí
PUT /api/tareas/:id Modificar una tarea propia (updateTareas) Sí
DELETE /api/tareas/:id Eliminar una tarea propia (deleteTareas) Sí