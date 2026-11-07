
# 🎵 Stashly

> **Busca, reproduce y descarga contenido multimedia desde un solo lugar.**

---

## 📌 ¿Qué es Stashly?

**Stashly** es una aplicación **open source (código abierto)** orientada a la **búsqueda, reproducción, visualización y descarga de contenido multimedia**.

El proyecto busca centralizar diferentes fuentes, servicios, librerías y clientes de código abierto en una misma aplicación, permitiendo que el usuario pueda acceder fácilmente a contenido como:

- 🎵 **Música**
- 🎬 **Videos**
- 🖼️ **Contenido multimedia**
- 🔗 **Contenido mediante URL**
- ⬇️ **Archivos descargables**

El usuario podrá **buscar contenido directamente desde Stashly** o **pegar la URL de un recurso compatible** para analizarlo y acceder a las opciones disponibles.

---

## 🎯 Objetivo del proyecto

El objetivo de **Stashly** es desarrollar una plataforma sencilla y centralizada que permita al usuario:

- **Buscar contenido multimedia.**
- **Reproducir contenido directamente desde la aplicación.**
- **Descargar contenido desde fuentes compatibles.**
- **Agregar contenido mediante una URL.**
- **Consultar diferentes fuentes desde una sola interfaz.**
- **Utilizar las funciones principales sin necesidad de registrarse.**

---

## ❓ Problema que busca resolver

Actualmente, el contenido multimedia se encuentra distribuido entre una gran cantidad de plataformas, servicios y aplicaciones.

Esto puede obligar al usuario a utilizar diferentes herramientas dependiendo del contenido que quiera **buscar, visualizar, reproducir o descargar**.

**Stashly busca centralizar estas funciones en una sola aplicación**, proporcionando una experiencia más sencilla para acceder a diferentes tipos de contenido multimedia.

---

# 🚀 Funcionalidades principales

## 🔎 Motor de búsqueda

Permite buscar **música, videos y otros contenidos multimedia** desde las diferentes fuentes integradas en Stashly.

## 🔗 Analizador de URL

Permite pegar una **URL proveniente de una plataforma compatible** para que Stashly identifique el contenido disponible.

## ▶️ Reproductor multimedia

Permite reproducir contenido compatible directamente desde la aplicación.

## ⬇️ Sistema de descarga

Permite descargar contenido cuando la **fuente utilizada y sus condiciones lo permitan**.

## 🌐 Integración con fuentes externas

Stashly podrá conectarse con diferentes:

- **Servicios**
- **APIs**
- **Librerías**
- **Bases de datos**
- **Clientes open source**

## 👤 Acceso sin registro

Las funcionalidades principales podrán utilizarse **sin necesidad de crear una cuenta**.

---

# 📚 Épicas iniciales

## 📦 EP-01 — Gestión de contenido mediante URL

Desarrollar un sistema que permita procesar enlaces provenientes de diferentes plataformas compatibles e identificar el contenido multimedia disponible.

---

## 🔌 EP-02 — Integración con fuentes multimedia

Implementar diferentes servicios, librerías, APIs o clientes de código abierto que permitan acceder y consultar contenido multimedia.

---

## 🔄 EP-03 — Integración Frontend y Backend

Desarrollar la comunicación entre la interfaz de usuario y el backend para consultar las diferentes fuentes y servicios utilizados por Stashly.

---

## 🔎 EP-04 — Sistema de búsqueda

Implementar un sistema que permita buscar contenido multimedia desde una única interfaz.

---

# ✨ Features principales

- **FT-01 — Analizador de URL**
- **FT-02 — Motor de búsqueda**
- **FT-03 — Reproductor multimedia**
- **FT-04 — Sistema de descarga**
- **FT-05 — Integración con clientes open source**
- **FT-06 — Visualización de información multimedia**
- **FT-07 — Selección de formatos disponibles**
- **FT-08 — Interfaz visual clara e intuitiva**

---

# 👥 Historias de usuario

## 🟢 US-01 — Acceso sin registro

**Como usuario**,  
quiero **ingresar a Stashly sin necesidad de crear una cuenta**,  
para **utilizar rápidamente las funcionalidades principales de la aplicación**.

### ✅ Criterios de aceptación

- El usuario debe poder ingresar a la aplicación **sin registrarse**.
- El sistema no debe obligar al usuario a crear una cuenta para acceder a las funciones principales.
- El usuario debe poder acceder al **buscador** desde la pantalla principal.
- El usuario debe poder utilizar el **analizador de URL** sin iniciar sesión.
- El acceso inicial a la aplicación debe ser directo y sencillo.

**Prioridad:** Alta  
**Estado:** To Do

---

## 🔵 US-02 — Buscar contenido multimedia

**Como usuario**,  
quiero **buscar música, videos u otro contenido multimedia**,  
para **encontrar fácilmente el contenido que deseo consumir**.

### ✅ Criterios de aceptación

- La aplicación debe mostrar un **campo de búsqueda**.
- El usuario debe poder introducir palabras o términos relacionados con el contenido deseado.
- El sistema debe procesar la búsqueda utilizando las fuentes disponibles.
- La aplicación debe mostrar los resultados encontrados.
- Los resultados deben mostrar información suficiente para identificar el contenido.
- Si no se encuentran resultados, el sistema debe informar al usuario.

**Prioridad:** Alta  
**Estado:** To Do

---

## 🟣 US-03 — Reproducir contenido

**Como usuario**,  
quiero **reproducir contenido multimedia desde Stashly**,  
para **consumirlo sin necesidad de utilizar otro reproductor o aplicación**.

### ✅ Criterios de aceptación

- El usuario debe poder seleccionar un contenido desde los resultados.
- El sistema debe identificar si el contenido puede reproducirse.
- El usuario debe disponer de una opción de **reproducción**.
- El reproductor debe permitir **iniciar y pausar** el contenido.
- El sistema debe informar cuando un contenido no pueda reproducirse directamente.
- La reproducción no debe impedir que el usuario pueda regresar a los resultados.

**Prioridad:** Alta  
**Estado:** To Do

---

## 🟠 US-04 — Descargar contenido

**Como usuario**,  
quiero **descargar contenido multimedia disponible desde fuentes compatibles**,  
para **poder almacenarlo y acceder a él posteriormente desde mi dispositivo**.

### ✅ Criterios de aceptación

- El sistema debe identificar si el contenido permite una opción de descarga.
- El usuario debe visualizar claramente la opción **Descargar**.
- La descarga debe iniciarse únicamente después de una acción del usuario.
- El sistema debe informar cuando una fuente no permita descargar el contenido.
- El usuario debe conocer el formato disponible antes de iniciar la descarga.
- El sistema debe informar si ocurre un error durante el proceso.

**Prioridad:** Alta  
**Estado:** To Do

---

## 🔗 US-05 — Agregar contenido mediante URL

**Como usuario**,  
quiero **pegar la URL de un contenido proveniente de una plataforma compatible**,  
para **que Stashly analice el enlace y muestre las opciones disponibles**.

### ✅ Criterios de aceptación

- La interfaz debe contener un **campo para ingresar una URL**.
- El usuario debe poder copiar y pegar un enlace.
- El sistema debe comprobar que el campo contenga una URL válida.
- Stashly debe intentar identificar la plataforma o fuente del enlace.
- El sistema debe analizar el contenido asociado a la URL.
- Si la URL es compatible, debe mostrar la información encontrada.
- Si la URL no es compatible, debe mostrar un mensaje informativo.
- Una URL incorrecta no debe provocar errores críticos en la aplicación.

**Prioridad:** Alta  
**Estado:** To Do

---

## 🟡 US-06 — Elegir formato disponible

**Como usuario**,  
quiero **visualizar los formatos disponibles para un contenido**,  
para **seleccionar la opción que mejor se adapte a mis necesidades**.

### ✅ Criterios de aceptación

- El sistema debe consultar los formatos disponibles del contenido.
- El usuario debe poder visualizar las opciones disponibles antes de descargar.
- Cada opción debe indicar su **tipo o formato** cuando esta información esté disponible.
- El usuario debe poder seleccionar una de las opciones mostradas.
- La opción seleccionada debe utilizarse para iniciar la reproducción o descarga correspondiente.
- Si solamente existe un formato, el sistema debe mostrarlo correctamente.

**Prioridad:** Media  
**Estado:** To Do

---

## 🖼️ US-07 — Visualizar información del contenido

**Como usuario**,  
quiero **visualizar información sobre el contenido encontrado**,  
para **comprobar que seleccioné el recurso correcto antes de reproducirlo o descargarlo**.

### ✅ Criterios de aceptación

Cuando la fuente proporcione esta información, Stashly debe mostrar:

- **Título del contenido.**
- **Miniatura o imagen.**
- **Duración.**
- **Tipo de contenido.**
- **Fuente o plataforma de origen.**
- **Formatos disponibles.**

Además:

- La información debe mostrarse antes de ejecutar una descarga.
- Los datos deben presentarse de manera clara y organizada.
- Si algún dato no está disponible, la aplicación debe continuar funcionando sin generar errores.

**Prioridad:** Media  
**Estado:** To Do

---

# 🗂️ Estructura inicial del repositorio

```text
stashly/
│
├── README.md
│
├── .gitignore
│
├── assets/
│   └── stashly-cover.png
│
├── docs/
│   ├── product-backlog.md
│   ├── user-stories.md
│   │
│   └── sprints/
│       └── sprint-01/
│           └── sprint-backlog.md
│
└── src/
````

---

# 🏃 Metodología de trabajo

El proyecto será desarrollado utilizando **Scrum**.

El trabajo se dividirá en diferentes **Sprints**, donde se seleccionarán historias provenientes del **Product Backlog**.

El flujo general será:

**Product Backlog**
⬇️
**Selección de historias**
⬇️
**Sprint Backlog**
⬇️
**Desarrollo del Sprint**
⬇️
**Sprint Review**
⬇️
**Actualización del Product Backlog**

---

# 🌿 Control de versiones

El proyecto utiliza **Git y GitHub** para mantener un historial de su evolución.

Los cambios importantes serán registrados mediante commits pequeños y descriptivos.

Ejemplos:

```bash
chore: initialize repository structure
docs: add README
docs: define project epics
docs: add product backlog features
docs: add user stories
docs: define sprint 1 backlog
```

---

# 🛠️ Tecnologías

Las tecnologías definitivas serán seleccionadas según las necesidades técnicas del proyecto.

Inicialmente se contempla trabajar con tecnologías orientadas a:

* **Desarrollo Frontend**
* **Desarrollo Backend**
* **APIs REST**
* **Integración con servicios externos**
* **Git**
* **GitHub**
* **Markdown**
* **Scrum**
* **Jira**

---

# 👨‍💻 Equipo

Proyecto desarrollado por estudiantes del programa:

**Técnico Laboral como Asistente en Desarrollo de Software**

**Submódulo:** Metodologías Ágiles

---

# 📊 Estado actual

> 🟢 **En desarrollo funcional**

Estado actualizado: **7 de noviembre de 2026**.

Actualmente Stashly ya cuenta con trabajo funcional en:

* ✅ Acceso sin registro.
* ✅ Búsqueda unificada y detalle multimedia.
* ✅ Reproducción compatible.
* ✅ Traer contenido mediante URL.
* ✅ Gestión de fuentes/providers.
* ✅ Descarga/offline y cola.
* ✅ Mi Stash y reproducción local.
* ✅ Mini-player.
* 🔄 Filtros, fallback de fuentes, continuidad de reproducción y responsive final.
* ⏳ Organización avanzada de Mi Stash y contenido destacado.

La implementación Angular + ASP.NET Core se está desarrollando fuera de este repositorio documental y debe sincronizarse con GitHub para que el código fuente y esta documentación representen el mismo estado del producto.

---

## 💙 Stashly

**Un lugar para buscar, reproducir y acceder a contenido multimedia de forma sencilla.**

> **Open Source · Multimedia · Search · Play · Download**

```
```