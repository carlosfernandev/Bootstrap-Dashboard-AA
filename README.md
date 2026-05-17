# Dashboard Responsive (Bootstrap)

Proyecto académico para construir un **dashboard responsive** usando **Bootstrap vía CDN**, cumpliendo la estructura y restricciones definidas en `docs.md`.

## Tecnologías

- HTML5
- Bootstrap 5 (CDN)
- JavaScript (bundle de Bootstrap vía CDN)

## Estructura del proyecto

- `dashboard.html`: página principal del dashboard
- `docs.md`: especificaciones y requisitos de la actividad

## Cómo ejecutar

1. Abrir `dashboard.html` en un navegador.
2. No requiere servidor ni dependencias instaladas (todo está por CDN).

## Especificaciones (según `docs.md`)

### 1) NavBar superior

Debe incluir como mínimo:

- Nombre del sistema (ej.: “Panel Administrativo”)
- Usuario (ej.: “Admin”)
- Botón o ícono (opcional)

### 2) SideBar (menú lateral)

Puede ser fijo o colapsable y debe incluir opciones:

- Inicio (presenta las cards)
- Usuarios (presenta tabla de registros y botón “Nuevo” que muestra el formulario)

### 3) Tarjetas de resumen

Mínimo **4 cards** con datos como:

- Usuarios registrados
- Ventas
- Productos
- Mensajes

### 4) Tabla de usuarios

En la opción **Usuarios**, incluir mínimo **5 registros** y columnas:

- Nombre
- Correo
- Estado
- Acción (botones)

### 5) Formulario de usuario

Debe incluir:

- Nombre
- Correo
- Rol (administrador o usuario)
- Botón enviar

## Requisitos obligatorios (responsive)

El dashboard debe ser responsive:

- El sidebar se adapta o se oculta en móvil
- Las cards se reorganizan
- La tabla se visualiza correctamente

## Restricciones

- No usar CSS personalizado (ni en `<style>` ni en archivos `.css`)
- No usar frameworks adicionales
- No usar librerías externas de diseño

## Estado actual (implementación)

- Layout base con **sidebar + navbar + sección de cards** usando grid de Bootstrap.
- Responsive inicial: el sidebar se muestra en columna completa en pantallas pequeñas y como columna lateral en pantallas grandes.
- Pendiente (si aplica): vista **Usuarios** con tabla, botón “Nuevo” y formulario.
