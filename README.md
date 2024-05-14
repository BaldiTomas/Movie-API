# API de Películas 🎥

Esta es una API RESTful que proporciona datos sobre películas. Es la API a la que se conecta mi otro proyecto llamado [React-movie-gold](https://github.com/BaldiTomas/React-movie-gold). 

## Tecnologías Utilizadas

Esta API ha sido construida utilizando las siguientes tecnologías:

- **Java:** Utilizado como lenguaje de programación principal.
- **Spring:** Utilizado como framework para el desarrollo de aplicaciones web.
- **MongoDB:** Utilizado como base de datos NoSQL para almacenar y gestionar los datos de las películas.

## Endpoints Disponibles

La API ofrece los siguientes endpoints para interactuar con los datos de las películas:

### Películas

- `GET /api/peliculas`: Obtiene la lista de todas las películas.
- `GET /api/peliculas/{id}`: Obtiene los detalles de una película específica por su ID.
- `POST /api/peliculas`: Crea una nueva película.
- `PUT /api/peliculas/{id}`: Actualiza los detalles de una película existente.
- `DELETE /api/peliculas/{id}`: Elimina una película existente por su ID.

### Reseñas

- `POST /api/reviews`: Crea una nueva reseña para una película.
  - **Payload:** Se espera un cuerpo de solicitud JSON con las claves "reviewBody" e "imdbId" para la creación de la reseña.

## Instrucciones de Uso

1. Clona este repositorio en tu máquina local.
2. Asegúrate de tener Java y MongoDB instalados en tu sistema.
3. Configura la conexión a tu base de datos MongoDB en el archivo `application.properties`.
4. Ejecuta la aplicación usando tu IDE preferido o mediante la línea de comandos.
5. La API estará disponible en `http://localhost:8080`.

¡Y eso es todo! Ahora puedes comenzar a utilizar la API para obtener y administrar datos sobre películas desde tu proyecto React.

¡Gracias por utilizar la API de Películas! Si tienes alguna pregunta o sugerencia, no dudes en ponerte en contacto conmigo.
