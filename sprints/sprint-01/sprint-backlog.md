# 🏃 Sprint 1 — Sprint Backlog

## 📌 Información del Sprint

**Proyecto:** Stashly  
**Sprint:** Sprint 1  
**Estado:** ✅ Completado  
**Objetivo:** construir el primer flujo funcional de acceso sin registro, análisis mediante URL y visualización de información multimedia.

---

## 🎯 Objetivo del Sprint

Permitir que un usuario ingrese a Stashly sin registrarse, utilice la función **Traer** con una URL compatible y visualice la información obtenida antes de reproducir o guardar contenido.

---

## 📋 Historias seleccionadas

### US-01 — Acceso sin registro — ✅ Done

Como usuario, quiero ingresar a Stashly sin crear una cuenta, para utilizar rápidamente las funciones principales.

**Resultado validado:**
- Acceso sin autenticación obligatoria.
- Navegación principal disponible.
- Buscar y Traer accesibles sin login.

### US-05 — Agregar contenido mediante URL — ✅ Done

Como usuario, quiero pegar una URL compatible, para que Stashly analice el contenido y muestre las opciones disponibles.

**Resultado validado:**
- Entrada y validación de URL.
- Resolución mediante backend.
- Errores controlados.
- Integración con el flujo de descarga cuando corresponde.

### US-07 — Visualizar información del contenido — ✅ Done

Como usuario, quiero ver información del contenido encontrado, para verificarlo antes de reproducirlo o guardarlo.

**Resultado validado:**
- Título y metadata disponible.
- Miniatura/cover cuando existe.
- Tipo y fuente del contenido.
- Manejo de información faltante sin romper la vista.

---

## ✅ Definition of Done

- [x] Flujo principal utilizable.
- [x] Validaciones y errores básicos.
- [x] Integración frontend/backend.
- [x] Pruebas básicas del flujo.
- [x] Historias reflejadas en Jira.
- [x] Documentación del Sprint actualizada.

---

## 🏁 Resultado

El Sprint 1 deja disponible el flujo:

```text
Usuario entra a Stashly
        ↓
Accede sin registrarse
        ↓
Abre Traer
        ↓
Pega una URL
        ↓
Stashly valida y resuelve
        ↓
Muestra información multimedia
```

**Cierre:** Sprint completado. El trabajo posterior amplía el producto con búsqueda multi-provider, reproducción, offline, biblioteca y experiencia responsive.
