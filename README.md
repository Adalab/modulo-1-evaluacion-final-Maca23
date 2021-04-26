# Evaluación final. Módulo HTML y CSS

Mi primer proyecto de manera individual. Forma parte de la evaluación académica y personal, sobre el aprendizaje adquerido en 3 semanas. Gracias a la utilización de **Adalab Starter Kit**, creado en **node y gulp**, he podido trabajar de manera cómoda, fácil y ordenada.

En este proyecto he contado con una plantilla con funcionalidades preinstaladas y preconfiguradas. Incluye un motor de plantillas HTML, preprocesador SASS y un servidor local.

## De qué se trata

1. Página web realizada con flexbox y Grid.
2. Aplicado mediaqueries (responsive) para distintos dispositivos.
3. El botón de menú debe estar fijo en la parte superior izquierda de la pantalla y no debe desaparecer al hacer scroll. Este menú no despliega ningún submenú.
4. Todos los links de la página deben dirigir a la web de ‘Adalab’.
5. El botón de flecha del módulo hero debe enlazar a la sección "3 Reasons To Purchase".
6. El botón de flecha del footer debe enlazar al inicio de la página.
7. En el hover de los botones ("Go" y "More reasons") se debe incluir una transición.
8. Animación en el botón del footer.

### Adalab Starter Kit

En el Kit hay 3 tipos de ficheros y carpetas:

- Los ficheros que están sueltos en la raíz del repositorio, como gulpfile.js, package.json... Son la configuración del proyecto y no necesitamos modificarlos.
- La carpeta `src/`: son los ficheros de nuestra página web, como HTML, CSS, JS...
- Las carpetas `public/` y `docs/`, que son generadas automáticamente cuando arrancamos el proyecto. El Kit lee los ficheros que hay dentro de `src/`, los procesa y los genera dentro de `public/` y `docs/`.

**La estructura de carpetas**

```
src
 ├─ api // los ficheros de esta carpeta se copian en public/api/
 |  └─ data.json
 ├─ images
 |  └─ logo.jpg
 ├─ js // los ficheros de esta carpeta se concatenan en el fichero main.js y este se guarda en public/main.js
 |  ├─ main.js
 |  └─ events.js
 ├─ scss
 |  ├─ components
 |  ├─ core
 |  ├─ layout
 |  └─ pages
 └─ html
    └─ partials
```

Para **más información** sobre [Adalab Web Starter Kit](https://github.com/Adalab/adalab-web-starter-kit)

#### Cómo clonar este repositorio

1. **Instala las dependencias** locales ejecutando en la terminal el comando:

```bash
npm install
```

2. Una vez hemos instalado las dependencias, vamos a arrancar el proyecto. **El proyecto hay que arrancarlo cada vez que te pongas a programar.** Para ello ejecuta el comando:

```bash
npm start
```

Este comando:

3. **Abre una ventana del navegador y muestra tu página web**, al igual que hace el plugin de VS Code Live Server (Go live).
**Observa** todos los ficheros que hay dentro de la carpeta `src/`, para que cada vez que modifiques un fichero **se actualice en tu navegador**.
**Procesa los ficheros** HTML, SASS / CSS y JS y los **genera y guarda en la carpeta `public/`**. Por ejemplo:
  - Convierte los ficheros SASS en CSS.
  - Combina los diferentes ficheros de HTML y los agrupa en uno o varios ficheros HTML.

4. Después de ejecutar `npm start` ya puedes empezar a editar todos los ficheros que están dentro de la carpeta `src/` y programar cómodamente.

5. Si quieres utilizar Github Pages para generar tu página para producción, ejecuta el comando:

```bash
npm run docs
```

**Para terminar**

1. Sube a tu repo la carpeta `docs/` que se te acaba de generar.
2. Entra en la pestaña `settings` de tu repo.
3. Y en el apartado de GitHub Pages activa la opción **master branch /docs folder**.