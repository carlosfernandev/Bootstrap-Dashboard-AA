**Instrucciones:**

 - Crear un archivo dashboard.html
 - Usar Bootstrap vía CDN.

**Estructura del Dashboard**

 1. NavBar superior debe incluir:
   - Nombre del sistema (ej: Panel Administrativo)
   - Usuario (ej: Admin)
   - Botón o ícono (opcional)
 2. SideBar (menú lateral), puede ser fijo o colapsable

- Inicio (presenta las cards)
- Usuarios (presenta la tabla de registros de usuarios).  También incluye un botón de "Nuevo", que llamará al formulario de usuario
 
3. Tarjetas de resumen, mínimo 4 cards con datos como:

  - Usuarios registrados
  - Ventas
  - Productos
  - Mensajes
4. La opción de usuarios incluye mínimo 5 registros:

  - Nombre
  - Correo
  - Estado
  - Acción (botones)
5. El formulario debe incluir:

  - Nombre
  - Correo
  - Rol (puede ser administrador o usuario)
  - Botón enviar

**Requisitos obligatorios**

El dashboard debe ser responsive:

  - Sidebar se adapta o se oculta en móvil
  - Cards se reorganizan
  - Tabla se visualiza correctamente
**Restricciones:**

  - No usar CSS personalizado (ni en <style> ni en archivos .css)
  - No usar frameworks adicionales
  - No usar librerías externas de diseño