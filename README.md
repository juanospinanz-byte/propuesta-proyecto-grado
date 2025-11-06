# GameHub

**Autor:** Juan Esteban Ospina Pinzón  

---

## Introducción 

### Objetivo del Proyecto
Desarrollar una tienda en línea de videojuegos que integre funcionalidades avanzadas como sistema de recomendaciones, gestión de preventas, comunidad de usuarios y panel administrativo completo, con un diseño moderno y centrado en el usuario.

---

## Ciclo de Vida de Desarrollo de Software

### Metodología
- **Enfoque:** Ágil
- **Iteraciones:** Sprints de 2 semanas
- **Entregables:** Incrementos funcionales tras cada sprint

---

## Técnicas de Recolección de Requerimientos Aplicadas

### Técnicas Utilizadas
- Entrevistas
- Análisis de Documentación

--- 

## Requisitos No Funcionales 

### Calidad en Uso
- **Eficiencia:** Tiempo de respuesta rapida para búsquedas
- **Satisfacción:** Interfaz intuitiva con puntuación de usabilidad de 1 a 5 estrellas

### Calidad Externa
- **Rendimiento:** Soporte para 1000 usuarios concurrentes
- **Seguridad:**  cumplimiento para pagos seguros
- **Compatibilidad:** Funcionamiento en los navegadores Chrome, Firefox, Safari, Edge

---

##  Verificación y Validación de Requerimientos
### Plan de Validación
- **Pruebas de Usabilidad:** Con 20 usuarios representativos
- **Pruebas de Carga:** Hasta 1500 usuarios concurrentes
- **Pruebas de Seguridad:** Penetration testing y análisis de código
- **Pruebas de Aceptación:** Con stakeholders y usuarios finales

---

## Arquitectura

### Frontend
 React y CSS

### Backend
Node.js


### Base de Datos
 MySQL

---

## Gestión de Historias de Usuario

- **Catálogo:** Búsqueda, filtrado y visualización de productos
- **Usuario:** Registro, autenticación y gestión de perfil
- **Compras:** Carrito, pagos y gestión de órdenes
- **Administración:** Panel de control y reportes

---

## V&V de requisitos

**VALIDACIÓN:**

**Validación de Lista de Deseos:**
- Los usuarios pueden agregar/eliminar fácilmente
- Las notificaciones de descuentos llamaria la atencion del usuario
- El límite de 50 productos es adecuado

**Validación del Proceso de Compra:**
- La integración al pagar es segura y confiable
- El email de confirmación proporciona seguridad
- La validación de stock previene frustraciones

**VERIFICACIÓN:**

**Verificación de Lista de Deseos:**
- El límite de 50 productos se respeta
- Las notificaciones de descuentos debe de aparecer cuando corresponde

 **Verificación de Recomendaciones:**
- El algoritmo debe producir resultados correctos por la busqueda o compra del usuario
- La actualización tras compra se ejecuta automáticamente y se actualiza el algoritmo

---

## Métricas de Calidad

- Que la forma de pago sea segura
- El rendimiento de la pagina al buscar videojuegos, hacer la compra, ect. Debe ser rapido
- Que no se caiga la pagina al tener muchos usuarios conectados a la vez
---
## Escritura de Requisitos de Usuario

### HU01: Registro de nuevo usuario
Como usuario nuevo

Quiero registrarme en la plataforma con email y contraseña

Para poder acceder a todas las funciones de GameHub

Criterios de Aceptación:
- Validar formato de email correcto
- La contraseña debe tener mínimo 8 caracteres, una mayúscula y un número
- Enviar email de confirmación de cuenta
- Redireccionar al catálogo tras registro exitoso

### HU02: Inicio de sesión seguro
Como usuario registrado

Quiero iniciar sesión de forma segura

Para acceder a mi cuenta y funciones personalizadas

Criterios de Aceptación:
- Validar credenciales 
- Implementar protección como el 2FA
- Recordar sesión opcionalmente
- Redireccionar a página principal o catálogo

### HU03: Búsqueda y filtrado de productos
Como usuario registrado o invitado

Quiero buscar y filtrar videojuegos por diversos criterios

Para encontrar rápidamente productos de mi interés

Criterios de Aceptación:
- Barra de búsqueda por texto en tiempo real
- Filtros por género, plataforma, precio, rating
- Resultados que se actualizan sin recargar página
- Ordenamiento por relevancia, precio, novedad
- Paginación de resultados
