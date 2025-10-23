# Verificación y Validación — Proyecto GameHub

## Objetivo
Identificar y documentar casos de uso, requisitos no funcionales, y criterios de validación que aseguren la calidad del sistema antes de su desarrollo.

---

## Validación de Requisitos
**1.** Verificar que cada historia de usuario sea completa y consistente

**2.** Validar que los criterios de aceptación sean claros y medibles

---

## Características 
- El catálogo avanzado de videojuegos y consolas con filtros por género, plataforma y ESRB.
- El sistema de recomendaciones basandose en el historial de compras y preferencias del usuario.
- La gestión de preventas con notificaciones automáticas al usuario.
- El carrito de compras con integración de pagos.
- Comunidad integrada: perfiles de usuario, reseñas, listas de deseos.
- Un panel administrativo completo para gestión de productos, categorías, inventario, pedidos y usuarios.

---

# Casos identificados 
## 1. Registro de Usuario
Actor: Usuario nuevo
Descripción: El nuevo usuario se registra en la plataforma con email y contraseña para acceder a todas las funcionalidades.
Criterios de aceptación:

- Validar formato de email y fortaleza de contraseña.
- Guardar usuario en la base de datos con encriptación de contraseña.
- Enviar email de confirmación.
- Redireccionar al catálogo tras registro exitoso.

## 2. Búsqueda y Filtrado de Productos
Actor: Usuario registrado
Descripción: El usuario busca y filtra videojuegos por género, plataforma, rating ESRB y otros criterios.
Criterios de aceptación:

- Mostrar resultados en tiempo real mientras se aplican filtros.
- Permitir combinación de múltiples filtros simultáneos.
- Mostrar productos con imagen, nombre, precio, plataforma y rating.
- Ordenar resultados por relevancia, precio o popularidad.
  
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
