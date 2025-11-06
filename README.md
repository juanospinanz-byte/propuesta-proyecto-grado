# GameHub

**Autor:** Juan Esteban Ospina Pinzón  

---

## Introducción y Contexto del Proyecto

### Objetivo General
Desarrollar una tienda en línea de videojuegos que integre funcionalidades avanzadas como sistema de recomendaciones, gestión de preventas, comunidad de usuarios y panel administrativo completo, con un diseño moderno y centrado en el usuario.

### Alcance
GameHub será una plataforma de comercio electrónico especializada en videojuegos y consolas, ofreciendo experiencias personalizadas mediante catálogos inteligentes, recomendaciones basadas en comportamiento y procesos de compra optimizados.

---

## Ciclo de Vida de Desarrollo de Software

### Metodología
- **Enfoque:** Ágil/Scrum
- **Iteraciones:** Sprints de 2 semanas
- **Entregables:** Incrementos funcionales tras cada sprint

### Fases del Proyecto
1. Análisis de Requerimientos
2. Diseño del Sistema
3. Desarrollo
4. Pruebas 

---

## Técnicas de Recolección de Requerimientos Aplicadas

### Técnicas Utilizadas
- Entrevistas
- Análisis de Documentación

--- 

## Requerimientos Funcionales

### Catálogo y Búsqueda (HU01)
**Requerimiento:** Sistema de búsqueda y filtrado avanzado

**Criterios de Aceptación:**
  - Barra de búsqueda por texto en tiempo real
  - Filtros por género y plataforma
  - Actualización dinámica de resultados sin recarga completa

### Sistema de Recomendaciones (HU02)
**Requerimiento:** Motor de recomendaciones personalizadas

**Criterios de Aceptación:**
  - Análisis de historial de compras y preferencias
  - Algoritmo de similitud implementado
  - Mínimo 5 recomendaciones relevantes
  - Actualización automática tras cada compra

### Gestión de Preventas (HU03)
**Requerimiento:** Sistema de reservas con notificaciones

**Criterios de Aceptación:**
  - Botón "Reservar" en productos en preventa
  - Confirmación y captura de método de pago
  - Notificación automática vía email al disponibilidad

### Proceso de Pago Seguro (HU04)
**Requerimiento:** Flujo de compra seguro y confiable

**Criterios de Aceptación:**
  - Integración con pasarelas de pago seguras
  - Soporte para 3+ métodos de pago
  - Validación de datos de tarjeta y dirección
  - Generación automática de comprobante PDF

### Lista de Deseos (HU05)
**Requerimiento:** Gestión de productos de interés futuro

**Criterios de Aceptación:**
  - Agregar/eliminar productos de lista de deseos
  - Notificaciones de descuentos y disponibilidad
  - Límite de 50 productos por usuario
  - Compartir lista con otros usuarios

### Registro de Usuario
**Requerimiento:** Sistema de autenticación seguro

**Criterios de Aceptación:**
  - Validación de formato email y fortaleza de contraseña
  - Almacenamiento seguro con encriptación
  - Email de confirmación de registro
  - Redirección a catálogo tras registro exitoso

### Gestión de Carrito
**Requerimiento:** Carrito de compras persistente

 **Criterios de Aceptación:**
  - Agregar/eliminar productos del carrito
  - Cálculo automático de total con impuestos y envío
  - Persistencia entre sesiones
  - Validación de stock antes de pago

---

## Requerimientos No Funcionales 

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

## Arquitectura y Stack Tecnológico

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

