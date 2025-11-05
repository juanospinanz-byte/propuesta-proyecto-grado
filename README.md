# Gamehub
Autor: Juan Esteban Ospina Pinzón

---

## Objetivo
Diseñar y desarrollar una plataforma web especializada en videojuegos que permita a los usuarios descubrir, gestionar y comprar productos a través de un catálogo avanzado con un sistema de recomendaciones personalizado, mientras se proporcionan a los administradores herramientas completas para gestionar el inventario, los pedidos y los usuarios.

---

## Caracteristicas
- El catálogo avanzado de videojuegos y consolas con filtros por género, plataforma.
- El sistema de recomendaciones basándose en el historial de compras y preferencias del usuario.
- La gestión de preventas con notificaciones automáticas al usuario.
- El carrito de compras con integración de pagos.
- Un panel administrativo completo para gestión de productos, categorías, inventario, pedidos y usuarios.

---

## Caracteristicas especificas

- Implementar un catálogo avanzado de videojuegos y consolas con filtros por género, plataforma.
- Desarrollar un sistema de recomendaciones inteligente basado en historial de compras y preferencias del usuario.
- Gestionar reservas y preventas con notificaciones automáticas a los usuarios.
- Proporcionar un carrito de compras con metodo de pago seguro.
- Ofrecer un panel administrativo completo para gestión de productos, categorías, inventario, pedidos y usuarios.

--- 

## Como estara hecho
- Frontend: React
- Backend: Node.js
- Base de datos: MySQL
- Diseño: CSS

## Historias de usuario
### HU01: Búsqueda y filtrado de productos en el catálogo
Como usuario registrado o invitado quiero poder buscar y filtrar videojuegos y consolas por género, plataforma y clasificación para encontrar rápidamente productos que se ajusten a mis preferencias

Criterios de aceptación:

- Debe haber una barra de búsqueda por texto.
- Los filtros deben incluir: género, plataforma.
- Los resultados deben actualizarse en tiempo real sin recargar la página completa.

### HU02: Recomendaciones personalizadas
Como usuario registrado con historial de compras quiero que el sistema me muestre recomendaciones de videojuegos basadas en mis compras anteriores y preferencias para descubrir títulos afines a mis gustos

Criterios de aceptación:

- Las recomendaciones deben aparecer en la página de inicio una vez el usuario ha iniciado sesión.
- El sistema debe considerar géneros, plataformas de juegos comprados o valorados.
- Cada recomendación debe incluir al menos: imagen, título, precio y enlace a la ficha del producto.

### HU03: Reserva en preventa con notificación
Como usuario interesado en un lanzamiento futuro quiero poder reservar un videojuego en preventa y recibir una notificación cuando esté disponible para asegurarme de obtenerlo el día de lanzamiento

Criterios de aceptación:

- El botón "Reservar" debe estar disponible en la ficha de productos en preventa.
- Al reservar, se debe solicitar confirmación y método de pago.
- El usuario debe recibir un email automático cuando el producto esté disponible para enviarse o para descargar dependiendo si se pidio el juego digital o en disco.

### HU04: Proceso de  pago seguro
Como usuario con productos en el carrito quiero completar el proceso de compra con un método de pago seguro y múltiples opciones para finalizar mi pedido de forma rápida y confiable

Criterios de aceptación:

- El proceso debe incluir: revisión del carrito, datos de envío, método de pago y confirmación.
- Debe soportar al menos 3 métodos de pago como tarjeta, PayPal, transferencia.
- Validación de datos de tarjeta y dirección antes del pago.
- Generación automática de comprobante de compra PDF que se le llega al correo.

### HU05: Gestión de Lista de Deseos
Como usuario que quiere planificar futuras compras quiero poder agregar productos a una lista de deseos y moverlos posteriormente al carrito para organizar mis intereses y facilitar la compra posterior

Criterios de aceptación:

- Debe existir un botón "Añadir a lista de deseos" en cada producto.
- La lista de deseos debe ser accesible desde el perfil del usuario.
