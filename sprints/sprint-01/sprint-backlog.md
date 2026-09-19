````md
# 🏃 Sprint 1 — Sprint Backlog

## 📌 Información del Sprint

**Proyecto:** Stashly  
**Sprint:** Sprint 1  
**Estado:** 🟡 Por iniciar  
**Duración estimada:** 2 semanas  
**Puntos estimados:** 11 Story Points

---

# 🎯 Objetivo del Sprint

Desarrollar el **flujo inicial de Stashly**, permitiendo que un usuario pueda ingresar a la aplicación sin necesidad de registrarse, pegar una URL de contenido multimedia y visualizar la información obtenida después de analizar el enlace.

Al finalizar este Sprint se espera contar con una primera versión funcional y representativa del flujo principal de la aplicación.

---

# 📋 Historias seleccionadas

Para este Sprint se seleccionaron las siguientes historias del **Product Backlog**:

- **US-01 — Acceso sin registro**
- **US-05 — Agregar contenido mediante URL**
- **US-07 — Visualizar información del contenido**

---

# 🟢 US-01 — Acceso sin registro

**Como usuario**,  
quiero **ingresar a Stashly sin necesidad de crear una cuenta**,  
para **utilizar rápidamente las funcionalidades principales de la aplicación**.

**Prioridad:** Alta  
**Estimación:** 3 Story Points  
**Estado:** To Do

---

## ✅ Criterios de aceptación

- El usuario debe poder ingresar a la aplicación **sin registrarse**.
- El sistema no debe obligar al usuario a crear una cuenta.
- El usuario debe visualizar la pantalla principal de Stashly.
- Desde la pantalla principal debe poder acceder al analizador de URL.
- El acceso inicial debe ser sencillo y directo.

---

## 🛠️ Tareas

- [ ] Diseñar la pantalla inicial de Stashly.
- [ ] Crear la estructura visual principal.
- [ ] Implementar el acceso sin autenticación.
- [ ] Crear navegación hacia el analizador de URL.
- [ ] Validar que ninguna función inicial requiera registro.
- [ ] Probar el flujo de ingreso a la aplicación.

---

# 🔗 US-05 — Agregar contenido mediante URL

**Como usuario**,  
quiero **pegar la URL de un contenido proveniente de una plataforma compatible**,  
para **que Stashly analice el enlace y muestre las opciones disponibles**.

**Prioridad:** Alta  
**Estimación:** 5 Story Points  
**Estado:** To Do

---

## ✅ Criterios de aceptación

- La interfaz debe contener un **campo para ingresar una URL**.
- El usuario debe poder escribir o pegar un enlace.
- El sistema debe comprobar que el campo no esté vacío.
- El sistema debe validar que el texto ingresado corresponda a una URL.
- Stashly debe intentar identificar el contenido asociado al enlace.
- El usuario debe poder iniciar el análisis mediante un botón.
- Si la URL es válida, el sistema debe continuar con el procesamiento.
- Si la URL no es válida, debe mostrarse un mensaje informativo.
- Una URL incorrecta no debe generar errores críticos en la aplicación.

---

## 🛠️ Tareas

- [ ] Crear el campo para ingresar una URL.
- [ ] Crear el botón **Analizar**.
- [ ] Implementar validación de campo vacío.
- [ ] Implementar validación básica de URL.
- [ ] Crear la lógica inicial para procesar el enlace.
- [ ] Crear mensajes de error para URLs inválidas.
- [ ] Crear estado de carga durante el análisis.
- [ ] Conectar el resultado del análisis con la vista de información.
- [ ] Realizar pruebas con URLs válidas e inválidas.

---

# 🖼️ US-07 — Visualizar información del contenido

**Como usuario**,  
quiero **visualizar información sobre el contenido encontrado**,  
para **comprobar que seleccioné el recurso correcto antes de reproducirlo o descargarlo**.

**Prioridad:** Media  
**Estimación:** 3 Story Points  
**Estado:** To Do

---

## ✅ Criterios de aceptación

Cuando la fuente proporcione esta información, Stashly debe mostrar:

- **Título del contenido.**
- **Miniatura o imagen.**
- **Duración.**
- **Tipo de contenido.**
- **Fuente o plataforma de origen.**
- **Formatos disponibles.**

Además:

- La información debe mostrarse después de analizar correctamente una URL.
- Los datos deben presentarse de manera clara y organizada.
- Si algún dato no está disponible, la aplicación debe continuar funcionando.
- El sistema no debe mostrar errores críticos por información faltante.

---

## 🛠️ Tareas

- [ ] Diseñar el componente de información multimedia.
- [ ] Mostrar el título del contenido.
- [ ] Mostrar miniatura o imagen cuando esté disponible.
- [ ] Mostrar duración cuando esté disponible.
- [ ] Mostrar tipo de contenido.
- [ ] Mostrar plataforma o fuente de origen.
- [ ] Preparar sección para formatos disponibles.
- [ ] Manejar información faltante.
- [ ] Crear estado visual cuando no existan datos.
- [ ] Probar la visualización con diferentes contenidos.

---

# 📊 Resumen del Sprint

| Historia | Descripción | Prioridad | Puntos | Estado |
|---|---|---|---:|---|
| **US-01** | Acceso sin registro | Alta | 3 | To Do |
| **US-05** | Agregar contenido mediante URL | Alta | 5 | To Do |
| **US-07** | Visualizar información del contenido | Media | 3 | To Do |
| | **Total** | | **11** | |

---

# 🔄 Flujo esperado al finalizar el Sprint

```text
Usuario entra a Stashly
        ↓
Accede sin registrarse
        ↓
Visualiza la pantalla principal
        ↓
Pega una URL
        ↓
Presiona "Analizar"
        ↓
Stashly valida la URL
        ↓
Procesa el contenido
        ↓
Muestra información multimedia
````

---

# ✅ Definition of Done

Una historia podrá considerarse **Done** cuando:

* [ ] Se hayan completado todas las tareas relacionadas.
* [ ] Cumpla todos sus criterios de aceptación.
* [ ] La funcionalidad pueda utilizarse sin errores críticos.
* [ ] Se hayan realizado pruebas básicas.
* [ ] Los cambios estén registrados mediante commits claros.
* [ ] La documentación correspondiente esté actualizada.

---

# 🌿 Commits sugeridos

Durante el Sprint se pueden realizar commits como:

```bash
docs: define sprint 1 backlog

feat: create initial stashly interface

feat: add guest access flow

feat: add url input component

feat: add url validation

feat: implement url analysis flow

feat: add media information view

fix: handle invalid urls

test: validate sprint 1 main flow

docs: update sprint 1 progress
```

---

# 🏁 Resultado esperado

Al finalizar el **Sprint 1**, Stashly deberá contar con un primer flujo funcional donde el usuario pueda:

1. **Ingresar sin crear una cuenta.**
2. **Acceder al analizador de URL.**
3. **Pegar un enlace de contenido multimedia.**
4. **Solicitar el análisis del enlace.**
5. **Visualizar la información obtenida del contenido.**

Las funcionalidades de **búsqueda, reproducción, selección de formatos y descarga** permanecerán en el Product Backlog para futuros Sprints.

````

Guárdalo exactamente en:

```text
docs/
└── sprints/
    └── sprint-01/
        └── sprint-backlog.md
````

Esa organización coincide con la estructura indicada por el profesor.

Además, me parece mejor **no meter búsqueda, reproducción y descarga todavía**: con estas tres historias el Sprint 1 ya entrega un flujo completo y las demás quedan para Sprint 2 y posteriores, que es justamente la idea de trabajar incrementalmente con Scrum.
