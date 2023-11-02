# Travel Page

[Travel Page](https://luisariza.github.io/travel_page/) es una pagina de viajes diseñada con:

- [**Tailwind**](https://tailwindcss.com/): Framework de CSS

Agregué la opción de **Dark Mode** y **Responsive Design** con las herramientas de <ins>Tailwind</ins> 
## Runnning

Para iniciar el proyecto primero ejecuta:

```sh
npm tw:build
```

Una vez instaladas las dependencias, inicia el proyecto:

```sh
npm start
```

Ahora ingresa en tu navegador http://localhost:5500/. Ya puedes hacer cambios al proyecto y verlos en tiempo real.

## Building

Si quieres enviar tu proyecto a producción ejecuta:

```sh
npm run tw:purge
```

Se creará automaticamaente una carpeta llamada "public" donde estará el codigo **minificado** (_para que pese menos_).

## Deploy

Para subir el codigo a <ins>GitHub Pages</ins> solo ejecuta:

```sh
npm run deploy
```

Con esto, se creará una rama en tu repositorio (_gh-pages_) donde solo vivirá el codigo de la capreta "dist".

> Importante hacer **build** antes de desplegar, para tener el codigo optimizado.
