# 📋 Planificación TPE - Parte 2

**Fecha de Entrega:** Domingo 24 de Mayo  
**Objetivo:** Implementar SSR, MVC y Sistema de Usuarios.

---

## 🏗️ Tareas Técnicas Base (Compartido)
- [ ] Configurar `config.php` con constantes de DB.
- [ ] Implementar Script de Auto-deploy (Creación de tablas e inserción de datos).
- [ ] Configurar Router para URLs semánticas.
- [ ] Setup inicial de clases Base (Model, View, Controller).

---

## 👤 Responsabilidades - Integrante A
*Enfoque: Gestión de Ítems (Lado N) y Acceso Público.*

### Funcionalidad Pública
- [ ] **Listado de ítems:** Vista general con todos los elementos de la DB.
- [ ] **Detalle de ítem:** Vista particular de un ítem por ID.

### Panel de Administración (ABM Ítems)
- [ ] **Login:** Sistema de autenticación para `webadmin`.
- [ ] **Listar:** Tabla de administración de ítems.
- [ ] **Alta:** Formulario con `<select>` dinámico de categorías.
- [ ] **Baja:** Eliminación de ítems.
- [ ] **Modificación:** Edición de datos existentes.

---

## 👤 Responsabilidades - Integrante B
*Enfoque: Gestión de Categorías (Lado 1) y Filtrado.*

### Funcionalidad Pública
- [ ] **Listado de categorías:** Vista con todas las categorías disponibles.
- [ ] **Items por categoría:** Filtrado dinámico (ej: `/categoria/:id`).

### Panel de Administración (ABM Categorías)
- [ ] **Logout:** Implementar cierre de sesión y destrucción de variables.
- [ ] **Listar:** Tabla de administración de categorías.
- [ ] **Alta:** Formulario para nuevas categorías.
- [ ] **Baja:** Eliminación (Ojo con la integridad referencial).
- [ ] **Modificación:** Edición de nombres/descripciones.

---

## 🎨 Requerimientos No Funcionales (Checklist)
- [ ] Todas las vistas usan plantillas `.phtml`.
- [ ] El patrón MVC está estrictamente separado.
- [ ] El código no tiene repeticiones innecesarias (DRY).
- [ ] Nombres de variables y funciones son descriptivos.
- [ ] El `README.md` incluye instrucciones de despliegue y credenciales.
