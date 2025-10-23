# Verificación y Validación — Proyecto GameHub

## Objetivo
Determinar la implementacion de la validacion y verificacion en el proyecto con el fin de que la tienda de videojuegos ofrezca una experiencia de usuario personalizada, segura y eficiente, el sistema busca facilitar el descubrimiento, adquisición y gestión de productos gaming mediante catálogos inteligentes, recomendaciones personalizadas y procesos de compra optimizados

---

## Validación de Requisitos
### 1. Registro de Usuario
- Formato de email válido
- Fortaleza de contraseña
- Email de confirmación enviado

### 2. Lista de Deseos
- Agregar/eliminar productos de la lista
- Compartir lista con otros usuarios
- Notificaciones de descuentos para los productos que estan en lista
  
### 3. Sistema de Recomendaciones  
- Análisis de historial de compras y lista de deseos
- Algoritmo de similitud implementado
- Actualización automática tras cada compra
  
### 4. Proceso de Compra Seguro
- Integración con pasarelas seguras
- Email de confirmación con detalles del pedido
- Validación de stock previa al pago
  
### 5. Gestión de Carrito de Compras
- Agregar/eliminar productos del carrito
- Cálculo automático de total con impuestos y envío
- Manejo de promociones y códigos de descuento

---

## Características 
- El catálogo avanzado de videojuegos y consolas con filtros por género, plataforma y ESRB.
- El sistema de recomendaciones basandose en el historial de compras y preferencias del usuario.
- La gestión de preventas con notificaciones automáticas al usuario.
- El carrito de compras con integración de pagos.
- Comunidad integrada: perfiles de usuario, reseñas, listas de deseos.
- Un panel administrativo completo para gestión de productos, categorías, inventario, pedidos y usuarios.

---

## Casos 
## 1. Registro de Usuario
Actor: Usuario nuevo

Descripción: El nuevo usuario se registra en la plataforma con email y contraseña para acceder a todas las funcionalidades.
Criterios de aceptación:

- Validar formato de email y fortaleza de contraseña.
- Guardar usuario en la base de datos con encriptación de contraseña.
- Enviar email de confirmación.
- Redireccionar al catálogo tras registro exitoso.

## 2. Lista de Deseos
Actor: Usuario registrado

Descripción: El usuario gestiona una lista personal de videojuegos que desea adquirir en el futuro, recibiendo notificaciones sobre cambios de precio y disponibilidad.
Criterios de aceptación:

- Permitir agregar/eliminar productos de la lista de deseos
- Mostrar notificaciones cuando productos en la lista de deseos tengan descuentos
- Alertar al usuario cuando un producto de la lista de deseos vuelva a estar en stock
- Limitar la lista de deseos a un máximo de 50 productos por usuario
  
## 3. Sistema de Recomendaciones
Actor: Usuario registrado

Descripción: El sistema recomienda juegos basándose en el historial de compras y preferencias del usuario.
Criterios de aceptación:

- Analizar historial de compras y juegos guardados en lista de deseos.
- Generar recomendaciones personalizadas usando algoritmo de similitud.
- Mostrar al menos 5 recomendaciones relevantes.
- Actualizar recomendaciones después de cada nueva compra.
  
## 4. Proceso de Compra Seguro
Actor: Usuario registrado

Descripción: El usuario completa la compra mediante integración con Stripe o PayPal.
Criterios de aceptación:

- Integrar pasarela de pago segura.
- Validar stock antes de procesar pago.
- Generar orden con estado "Completada" tras pago exitoso.
- Enviar confirmación de compra por email con detalles del pedido.
- Actualizar inventario tras compra exitosa.

## 5. Gestión de Carrito de Compras
Actor: Usuario registrado

Descripción: El usuario añade videojuegos al carrito, revisa el total y procede al checkout.
Criterios de aceptación:

- Permitir agregar/eliminar productos del carrito.
- Calcular total con impuestos y costos de envío.
- Mantener carrito persistente 
- Validar stock disponible antes de proceder al pago.
