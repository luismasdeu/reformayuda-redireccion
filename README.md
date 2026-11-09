# reformayuda-redireccion

Sirve el dominio antiguo **reformayuda.es** con GitHub Pages y lleva cada dirección a la misma en **obrayuda.es**
(`index.html` y `404.html` hacen la redirección conservando la ruta).

`.well-known/assetlinks.json` se mantiene aquí sin redirigir, para que la app de Android que aún apunta a
reformayuda.es siga verificada hasta que se publique la versión que apunta a obrayuda.es.
