---
name: brief-marca
description: "Recopila, organiza y mantiene el contexto estratégico de una marca —oferta, público, posicionamiento, personalidad, valores y objetivos— en un brief reutilizable. Úsala cuando el usuario quiera crear, guardar o actualizar el contexto de marca, o al iniciar un proyecto de marca si aún no existe un brief."
---

# Contexto de marca

Construye un brief de marca breve, útil y reutilizable para el trabajo posterior. Escribe el brief en español, salvo que el usuario pida otro idioma. Distingue los hechos confirmados, las preferencias y las hipótesis; no conviertas aspiraciones en prestaciones demostradas.

## Antes de recopilar información

Busca el contexto de marca existente en el proyecto. Respeta el archivo que ya se esté usando; en este proyecto es `brand-context.md` en la carpeta raiz del proyecto. Si existe, léelo y conserva la información válida. Pregunta qué quiere cambiar solo cuando la petición no indique qué actualizar; si el usuario ya ha señalado cambios, aplícalos sin volver a pedir confirmación.

Si no existe un brief, recopila lo necesario usando el contexto disponible y preguntando todas las respuestas, seccion por seccion. Haz preguntas breves y agrupadas; ofrece opciones cuando ayuden a responder con facilidad y permite una respuesta propia. No preguntes por datos ya compartidos. Si el usuario ofrece una imagen de referencia, analizala, solo para determinar una opcion adicional de respuesta a una pregunta.

## El Flujo de preguntas
Cada seccion esta compuesta de varias preguntas. Se hace pregunta por pregunta, una por una. En cada pregunta, se da un frase descriptiva de explicacion de lo que se esta preguntando. Es interactivo, cada respuesta suma a la consideracion para la siguiente. De esa manera, la dinamica es mas interactiva. 
Cada seccion se anuncia al inicia por ejemplo "Inicio Seccion Marca", y al final de cada seccion se comenta "Seccion Marca Finalizada".

## Contenido del brief

Recoge, cuando esté disponible:

- **Marca y oferta:** nombre o estado del naming, categoría, descripción, etapa.
- **Público:** quién es, qué necesita, 
- **Enfoque** qué problema resuelve la marca y cómo lo expresa.
- **Posicionamiento:** diferencia frente a alternativas, competidores conocidos y segmento de mercado.
- **Personalidad y voz:** rasgos, tono y referentes de comunicación.
- **Valores y misión:** principios que guían la marca y propósito, aunque estén en borrador.
- **Objetivos:** objetivo principal y métricas relevantes con horizonte temporal.

No fuerces campos sin datos: Marca "Pendiente" solo si el usuario explica que no tiene datos a una pregunta o parte de una pregunta. 

## Guardar y actualizar

Guarda el brief en el archivo de contexto existente; para este proyecto, actualiza `brief-marca.md` en la carpeta raiz del proyecto, en lugar de crear copias fechadas. Conserva su idioma y estructura general, mejora la claridad y evita perder información vigente. Si el usuario pide expresamente otra ubicación o un historial fechado, sigue esa instrucción.

Usa una estructura fácil de consultar, incluye cada seccion y la lista de respuestas:

```markdown
# Brief de Marca

## Seccion
- **Pregunta**: Respuesta
```

Tras guardar los cambios, informa qué se actualizó y dónde. Indica que se puede volver a actualizar el brief cuando cambie la marca.

## Uso por otras skills

Las skills de marca deben consultar este brief antes de trabajar cuando esté disponible, reutilizar sus datos y preguntar solo por la información específica de la tarea que falte. Este contexto orienta el trabajo, pero no reemplaza la solicitud concreta del usuario.
