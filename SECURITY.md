# Política de seguridad

Guía 100 % estática (`index.html` autocontenido, sin backend, sin dependencias,
sin formularios que envíen datos). El único almacenamiento es `localStorage`
del propio navegador del estudiante.

## Reportar un problema

Si encuentras contenido sensible publicado por error o una vulnerabilidad,
abre un *issue* en este repositorio describiendo el hallazgo **sin incluir
datos personales** y se retirará el contenido afectado.

## Controles activos

- Sin secretos ni tokens en el repositorio (verificado antes de cada push).
- Sin dependencias externas: no hay cadena de suministro que auditar.
- Sin datos personales: solo contenido didáctico ficticio.
- GitHub Pages servido por HTTPS con HSTS.
