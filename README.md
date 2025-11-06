# GameHub

**Autor:** Juan Esteban Ospina Pinzón  

---

## 1. Introducción y Contexto del Proyecto

### 1.1. Objetivo General
Desarrollar una tienda en línea de videojuegos que integre funcionalidades avanzadas como sistema de recomendaciones, gestión de preventas, comunidad de usuarios y panel administrativo completo, con un diseño moderno y centrado en el usuario.

### 1.2. Alcance
GameHub será una plataforma de comercio electrónico especializada en videojuegos y consolas, ofreciendo experiencias personalizadas mediante catálogos inteligentes, recomendaciones basadas en comportamiento y procesos de compra optimizados.

---

## 2. Ciclo de Vida de Desarrollo de Software

### 2.1. Metodología
- **Enfoque:** Ágil/Scrum
- **Iteraciones:** Sprints de 2 semanas
- **Entregables:** Incrementos funcionales tras cada sprint

### 2.2. Fases del Proyecto
1. Análisis de Requerimientos
2. Diseño del Sistema
3. Desarrollo
4. Pruebas 

---

## 3. Técnicas de Recolección de Requerimientos Aplicadas

### Técnicas Utilizadas
- Entrevistas
- Análisis de Documentación

## 4. Requerimientos Funcionales

### 4.1. Catálogo y Búsqueda (HU01)
**Requerimiento:** Sistema de búsqueda y filtrado avanzado

**Criterios de Aceptación:**
  - Barra de búsqueda por texto en tiempo real
  - Filtros por género y plataforma
  - Actualización dinámica de resultados sin recarga completa

### 4.2. Sistema de Recomendaciones (HU02)
**Requerimiento:** Motor de recomendaciones personalizadas

**Criterios de Aceptación:**
  - Análisis de historial de compras y preferencias
  - Algoritmo de similitud implementado
  - Mínimo 5 recomendaciones relevantes
  - Actualización automática tras cada compra

### 4.3. Gestión de Preventas (HU03)
**Requerimiento:** Sistema de reservas con notificaciones

**Criterios de Aceptación:**
  - Botón "Reservar" en productos en preventa
  - Confirmación y captura de método de pago
  - Notificación automática vía email al disponibilidad

### 4.4. Proceso de Pago Seguro (HU04)
**Requerimiento:** Flujo de compra seguro y confiable

**Criterios de Aceptación:**
  - Integración con pasarelas de pago seguras
  - Soporte para 3+ métodos de pago
  - Validación de datos de tarjeta y dirección
  - Generación automática de comprobante PDF

### 4.5. Lista de Deseos (HU05)
**Requerimiento:** Gestión de productos de interés futuro

**Criterios de Aceptación:**
  - Agregar/eliminar productos de lista de deseos
  - Notificaciones de descuentos y disponibilidad
  - Límite de 50 productos por usuario
  - Compartir lista con otros usuarios

### 4.6. Registro de Usuario
**Requerimiento:** Sistema de autenticación seguro

**Criterios de Aceptación:**
  - Validación de formato email y fortaleza de contraseña
  - Almacenamiento seguro con encriptación
  - Email de confirmación de registro
  - Redirección a catálogo tras registro exitoso

### 4.7. Gestión de Carrito
**Requerimiento:** Carrito de compras persistente

 **Criterios de Aceptación:**
  - Agregar/eliminar productos del carrito
  - Cálculo automático de total con impuestos y envío
  - Persistencia entre sesiones
  - Validación de stock antes de pago

---

## 5. Requerimientos No Funcionales 

### 5.1. Calidad en Uso
- **Eficiencia:** Tiempo de respuesta rapida para búsquedas
- **Satisfacción:** Interfaz intuitiva con puntuación de usabilidad de 1 a 5 estrellas

### 5.2. Calidad Externa
- **Rendimiento:** Soporte para 1000 usuarios concurrentes
- **Seguridad:**  cumplimiento para pagos seguros
- **Compatibilidad:** Funcionamiento en los navegadores Chrome, Firefox, Safari, Edge 

