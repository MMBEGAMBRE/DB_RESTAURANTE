# DB_RESTAURANTE
Autores:

1: MAILETH BEGAMBRE(aprendiz sena)
2:LILIANA PANESSO(aprendiz sena)
3:JUAN DIEGO MEJIA(aprendiz sena)

Descripción del proyecto:

Esta API REST permite gestionar la información de un restaurante, incluyendo categorías de platos y los platos asociados. Está construida con Node.js, Express y SQLite3, siguiendo una arquitectura modular y aplicando operaciones CRUD completas.
El proyecto incluye documentación de endpoints, ejemplos de uso y pruebas realizadas con la  herramienta  Thunder.


Tecnologías utilizadas:

Node.js

Express

SQLite3

Thunder Client

Instalación y ejecución:

1 Clonar el repositorio

git clone https://github.com/LPAMENDEZ/DB_RESTAURANTE.git
cd DB_RESTAURANTE

2 Instalar dependencias
npm install

3 Ejecutar el servidor
node server.js

La base de datos se genera automáticamente en:
/database/restaurante.db

estructura del proyecto
 
 DB_RESTAURANTE 
 database| db.js | restaurante.db
 node_modules
 routes| routes_categoria.js| routes_platos.js
 package-lock.json
 package.json
 pruebas.http
 README.md
 server.js

Endpoints de la API
metodo: GET
Endpoints: /api/categorias
descripcion: Obtener todas las categorías

Endpoints de la API
metodo: GET
Endpoints: /api/categorias/:id
descripcion: Obtener categoría por ID

Endpoints de la API
metodo: POST
Endpoints:/api/categorias
descripcion: Crear categoría

Endpoints de la API
metodo: PUT
Endpoints: /api/categorias/:id
descripcion: Actualizar categoría

Endpoints de la API
metodo: DELETE
Endpoints: /api/categorias/:id
descripcion: Eliminar categoría por ID

Endpoints de la API
metodo: DELETE
Endpoints: /api/categorias
descripcion: Eliminar todas las categorías

Endpoints de la API
metodo: GET
Endpoints: /api/platos/
descripcion: obtener todos los platos

Endpoints de la API
metodo: GET
Endpoints: /api/platos/:id
descripcion: Obtener un plato por ID

Endpoints de la API
metodo: GET
Endpoints: /api/platos/categoria/:id
descripcion: Obtener platos por categoría

Endpoints de la API
metodo: POST
Endpoints: /api/platos
descripcion: Crear plato

Endpoints de la API
metodo: PUT
Endpoints: /api/platos/:id
descripcion: Actualizar plato

Endpoints de la API
metodo:DELETE
Endpoints: /api/platos/:id
descripcion: Eliminar plato por ID

Endpoints de la API
metodo: DELETE
Endpoints: /api/platos
descripcion: Eliminar todos los platos


CATEGORIAS

Obtener todas

Obtener por ID

Crear

Actualizar

Eliminar

PLATOS

Obtener todos

Obtener por ID

Obtener por categoría

Crear

Actualizar

Eliminar
