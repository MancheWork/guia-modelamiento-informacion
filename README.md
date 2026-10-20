# Guía de Aprendizaje · Modelamiento de Información

Guía web interactiva y autocontenido (un solo `index.html`, sin dependencias externas)
para aprender a pasar de un modelo entidad-relación (MER, notaciones Chen y Martin)
a un esquema relacional correcto y documentado.

## Contenido

- Fundamentos del modelamiento y notación Chen / Martin (crow's foot)
- MER avanzado: jerarquías, entidades intermedias, relaciones ternarias y recursivas
- Calidad del MER y errores frecuentes
- Modelo relacional: estructuras, reglas y objetivos
- Mapeo de entidades, atributos y relaciones (tabla de decisiones, exclusividad, CHECK)
- Generalizaciones (3 casos) y documentación del esquema
- Laboratorio con 5 ejercicios guiados: pistas progresivas, talleres de decisión,
  verificación automática de esquemas y soluciones oficiales
- Glosario, autoevaluación con tiempo (30 preguntas) y chuleta final

## Uso

Abre `index.html` en cualquier navegador moderno. No requiere servidor ni conexión.

## Regenerar

```powershell
python "fuentes\build.py"
```

Las fuentes viven en `fuentes\` (`parte1–4.html`); el script las concatena e inyecta
los diagramas como imágenes embebidas para producir el `index.html` final.

## Privacidad

Todo el progreso, respuestas y borradores se guardan solo en el navegador del
estudiante (`localStorage`). No se envía ni se pide ningún dato personal.
No se publica contenido de otras asignaturas: esta guía solo cubre
modelamiento de información.
