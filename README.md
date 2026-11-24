<!-- título del repo: cambia por tus nombres reales -->
# U3p2 — Pesqueira Gamez Manuel Angel

<!-- sección con los pasos para correr el proyecto en otra computadora -->
## Cómo correrlo localmente
<!-- paso 1: el entorno virtual -->
1. Crear y activar un entorno virtual
<!-- paso 2: instalar los paquetes de requirements.txt -->
2. pip install -r requirements.txt
<!-- paso 3: crear el .env a partir del ejemplo -->
3. Copiar .env.example a .env y completar con credenciales propias de Aiven
<!-- paso 4: crear las tablas en MySQL -->
4. python manage.py migrate
<!-- paso 5: arrancar el servidor -->
5. python manage.py runserver

<!-- sección con la evidencia de la práctica -->
## Evidencia

Se evidencio que la aplicacion esta corriendo de manera local, la base de datos esta siendo hosteada por medio de Aiven y manejada/manipulada por medio de DBeaver.

<!-- sección con la URL pública de Render -->
## Demo en vivo (producción)
<!-- tu dirección real de Render -->
https://u3p2-pesqueira-gamez-manuel-angel-rec.onrender.com/

<!-- sección con la URL del panel de administración -->
## Panel de administración
<!-- misma dirección + /admin -->
https://u3p2-pesqueira-gamez-manuel-angel-rec.onrender.com/admin

<!-- resumen de lo que hiciste esta semana -->
## Semana 4 — Modelos y despliegue dinámico
<!-- primera línea del resumen -->
Modelo Servicio migrado a MySQL, Web Service publicado en Render,
<!-- segunda línea del resumen -->
5 registros reales cargados desde /admin.

<!-- ## : subtítulo con lo que se hizo esta semana -->
## Semana 5 — CRUD completo con ModelForms
<!-- primera línea de la descripción de la práctica -->
Crear, editar y eliminar un Servicio desde pantallas propias
<!-- segunda línea de la descripción de la práctica -->
(sin usar /admin), con validacion personalizada en el precio.

## Semana 6 - Autenticacion y Seguridad
<!-- primera línea de la descripción de la práctica -->
Registro/login/logout propios; cada usuario ve y edita solo
<!-- segunda línea de la descripción de la práctica -->
sus propios servicios (probado con usuario_a y usuario_b).

<!-- ## : subtítulo de la sección con la prueba de aislamiento -->
## Prueba de aislamiento
<!-- reemplaza el texto entre corchetes por la descripción de tu prueba -->
Se creo un aislamiento de los servicios por medio de el usuario logueado, con esto cada usuario puede eliminar, ediatr o crear sus propios servicios sin poder hacer tales acciones para los servicios de otros usuarios.