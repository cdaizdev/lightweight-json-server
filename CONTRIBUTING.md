# Contributing to lightweight-json-server 

¡Gracias por el interés en contribuir a **lightweight-json-server**! Este proyecto busca ser una alternativa rápida y sencilla para prototipar APIs, y tu ayuda es fundamental para mantenerlo así.

Al participar en este proyecto, te comprometes a mantener un entorno respetuoso y colaborativo.

---

## Cómo empezar

### 1. Requisitos previos

Asegúrate de tener instalado:

* **Node.js** (versión 18 o superior)
* **npm** o **pnpm**

### 2. Configuración del entorno

1. Haz un **Fork** del repositorio.
2. Clona tu fork localmente:
```bash
git clone https://github.com/cdaizdev/lightweight-json-server.git

```


3. Instala las dependencias:
```bash
npm install

```


4. Crea una rama para tu modificación:
```bash
git checkout -b feature/nueva-funcionalidad

```



---

## Reportando Errores (Bugs)

Si encuentras un error, por favor abre una **Issue** detallando:

* Una descripción clara del problema.
* Pasos para reproducirlo.
* Comportamiento esperado vs. Comportamiento actual.
* Tu versión de Node.js y sistema operativo.

---

## Proponiendo Mejoras

¡Las ideas nuevas son bienvenidas! Si quieres añadir una funcionalidad:

1. Revisa las **Issues** abiertas para ver si alguien ya lo ha sugerido.
2. Si es un cambio grande, abre una Issue primero para discutir el diseño antes de escribir el código.

---

## Guía de Estilo y Estándares

Para mantener la consistencia en el código, pedimos seguir estas reglas:

* **Linting:** Usamos ESLint. Asegúrate de ejecutar `npm run lint` antes de subir tus cambios.
* **Tests:** Si añades una funcionalidad, incluye un test que la cubra. Ejecuta los tests existentes con:
```bash
npm test

```


* **Commits:** Usa mensajes descriptivos en inglés o español (pero sé consistente). Ejemplo: `feat: add support for custom ports`.

---

## Proceso de Pull Request

1. Asegúrate de que tu rama esté actualizada con `main`.
2. Empuja tus cambios a tu fork: `git push origin feature/nueva-funcionalidad`.
3. Abre un **Pull Request** (PR) hacia la rama `main` del repositorio original.
4. Describe brevemente tus cambios en la descripción del PR.
5. Espera a la revisión. ¡Responderemos lo antes posible!

---

## Licencia

Al contribuir a este proyecto, aceptas que tus contribuciones estarán bajo la misma **Licencia MIT** que rige al proyecto.

---

¿Te gustaría que añada alguna sección específica para el manejo de bases de datos JSON o alguna regla de seguridad particular?
