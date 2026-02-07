GET /api/carrito
Devuelve la colección completa de carritos almacenados en memoria.
No requiere cuerpo en la petición.
Respuestas posibles: 200 OK.


POST /api/carrito
Crea un nuevo carrito y lo almacena usando el campo idCarrito como identificador.
Requiere un cuerpo en formato JSON que represente un Carrito.
Respuestas posibles: 201 Created, 400 Bad Request.


GET /api/carrito/{idCarrito}
Devuelve el carrito cuyo identificador coincide con idCarrito.
No requiere cuerpo en la petición.
Respuestas posibles: 200 OK, 404 Not Found.


DELETE /api/carrito/{idCarrito}
Elimina el carrito cuyo identificador coincide con idCarrito.
No requiere cuerpo en la petición.
Respuestas posibles: 204 No Content, 404 Not Found.


PUT /api/carrito/{idCarrito}
Modifica el carrito existente con el identificador indicado.
Requiere un cuerpo en formato JSON que represente un Carrito.
Respuestas posibles: 200 OK, 400 Bad Request, 404 Not Found.
