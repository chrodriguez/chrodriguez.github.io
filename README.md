# CV de Christian Rodriguez

Este repositorio lo uso para mantener mi propio CV usando GIT y [jsonresume](https://jsonresume.org/).

## ¿Cómo usar el repositorio?

* `git clone` del repositorio
* En el directorio clonado correr: `npm i`
* Editar `resume.json`
* Visualizar los cambios en el navegador con `npm start`
* Exportar el CV usando `npm export -- cv.pdf`

## Aplicando temas

El repositorio instala dos temas ademaś del tema por default. Para instalar más
temas usar:

```
npm install --save <nombre-tema>
```

Para visualizar la web con un tema usar:

```
npm start -- --theme elegant
```
> Ejemplo utilizando el tema elegant

Para exportar el PDF usando un tema:

```
npm run-script export -- --theme kendall cv.pdf
```

