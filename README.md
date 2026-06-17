# Centro legal de Cuadria (legal.cuadria.xyz)

Sitio estático servido por GitHub Pages con dominio `legal.cuadria.xyz`.
Aloja los documentos legales de las apps de Cuadria, separados por app.

## Estructura
```
/                      portada (hub de apps)
/<app>/                índice legal de esa app
/<app>/privacidad/     política de privacidad (index.html)
/<app>/terminos/       términos y condiciones (index.html)
```
URL de ejemplo: https://legal.cuadria.xyz/easyreport/privacidad

## Añadir una app nueva
1. Crear carpeta `/<nombre-app>/` con su `index.html`, y dentro
   `privacidad/index.html` y `terminos/index.html`.
2. Añadir una tarjeta de la app en la portada `index.html` raíz.
3. `git push` → GitHub Pages publica solo.

No borrar el archivo `CNAME` (mantiene el dominio legal.cuadria.xyz).
