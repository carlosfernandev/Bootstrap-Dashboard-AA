# Dashboard Responsive (Bootstrap)

Proyecto académico para construir un **dashboard responsive** usando **Bootstrap vía CDN**, cumpliendo la estructura y restricciones definidas en `docs/docs.md`.

## Hecho por:

- Orrala Arriaga Paulo
- Patiño García Carlos Fernando
- Villón Panimboza Ángel Alejandro

## Tecnologías

- HTML5
- Bootstrap 5 (CDN)
- JavaScript (bundle de Bootstrap vía CDN)

## Estructura del proyecto

- `dashboard.html`: página principal del dashboard
- `docs/docs.md`: especificaciones y requisitos de la actividad
- `html/vista-usuarios.html`: vista de usuarios (tabla + acciones)
- `html/form-usuario.html`: formulario para crear usuario

## Cómo ejecutar

1. Abrir `dashboard.html` en un navegador.
2. No requiere servidor ni dependencias instaladas (todo está por CDN).

## Especificaciones (según `docs/docs.md`)

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

## Paleta de colores (background)

Clases utilitarias de Bootstrap permitidas para fondos:

- `.bg-light`
- `.bg-light-subtle`
- `.bg-dark`
- `.bg-dark-subtle`
- `.bg-body-secondary`
- `.bg-body-tertiary`
- `.bg-body`

## Estado actual (implementación)

- `dashboard.html`: layout base con navbar + sección de cards (grid de Bootstrap).
- `html/vista-usuarios.html`: tabla responsive con acciones por fila y botón “Nuevo”.
- `html/form-usuario.html`: campos de Nombre, Correo y Rol.
- Pendiente (si aplica): botón “Enviar” del formulario.
