# Serenity Spa & Beauty

Proyecto basado en HTML5 Boilerplate con Vite como herramienta de desarrollo y
Sass para organizar y compilar los estilos.

## Desarrollo

```bash
npm install
npm run dev
```

Vite carga `main.js`, que importa `sass/style.scss`. Los cambios de SCSS se
compilan en memoria y se reflejan automáticamente en el navegador. No es
necesario ejecutar Sass por separado.

## Compilación

```bash
npm run build
```

La compilación recrea `dist/` y genera:

```text
dist/index.html
dist/css/style.css
dist/js/app.js
```

No edites `dist` manualmente: modifica las fuentes y vuelve a compilar.

Para revisar la compilación final localmente:

```bash
npm run preview
```
