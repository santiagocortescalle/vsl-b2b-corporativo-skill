# VSL B2B corporativo

Skill en español para ayudar a agencias, productoras y estudios de diseño B2B a investigar el negocio comprador, construir una oferta y promesa de ventas defendibles y escribir un video sales letter para una landing. El caso principal busca agendar una llamada de diagnóstico con responsables de marketing, marca, contenido, campañas o creatividad.

Antes del guion, el proceso entrevista al estudiante sobre su negocio y el del comprador, elige una oferta concreta y trabaja siete campos de promesa: quién califica, resultado, fricción, plazo, mecanismo, ganancia mayor y frustración profunda. También recoge casos, preguntas de compra, datos de vanidad, voz y condiciones comerciales. Ofrece tres caminos para tratar el precio: cifra o mínimo, rango orientativo, o explicación de variables sin cifra en el video.

Durante la entrevista actúa como consultor: si falta información o hay dudas, propone opciones adaptadas a la agencia y al comprador, recomienda un camino con sus razones y señala qué habría que validar. Puede avanzar con hipótesis visibles sin inventar hechos.

## Instalar en Codex

Abre Codex y pega este mensaje:

> Usa $skill-installer para instalar la habilidad VSL B2B corporativo desde https://github.com/santiagocortescalle/vsl-b2b-corporativo-skill/tree/main/vsl-b2b-corporativo. Avísame cuando esté disponible.

También puedes instalarlo desde una copia local, ejecutando en la raíz:

```bash
mkdir -p ~/.codex/skills
cp -R vsl-b2b-corporativo ~/.codex/skills/
```

Después, inicia una nueva sesión e invoca `$vsl-b2b-corporativo`, o pide ayuda para crear un VSL B2B para una agencia o productora.

## Instalar en Claude Code

Desde la raíz de una copia local de este repositorio:

```bash
mkdir -p ~/.claude/skills
cp -R vsl-b2b-corporativo ~/.claude/skills/
```

Después, inicia una nueva sesión e invoca `/vsl-b2b-corporativo`. Claude Code también puede cargar el skill cuando la petición encaje con su descripción. [Documentación oficial de skills de Claude Code](https://code.claude.com/docs/en/skills).

## Primer uso sugerido

> Quiero construir un VSL para una landing de mi agencia. Primero ayúdame a entender el negocio comprador y a diseñar una oferta y promesa con los siete campos de tu framework. Entrevístame sobre casos, objeciones y operación antes de escribir. Si dudo o me falta información, propón opciones y recomienda un camino. Mi objetivo es agendar llamadas de diagnóstico.

El skill mostrará una ficha de decisión para corregir los hechos materiales antes del guion. Puede trabajar con información incompleta y dejar los vacíos visibles. No necesita que el estudiante tenga instalado otro skill de copywriting.

## Material para la clase

El [cuerpo de conocimiento](01-cuerpo-de-conocimiento.md) explica las decisiones detrás del framework y los puntos que aún pueden afinarse con ejemplos reales de estudiantes.

El [informe de QA y tres VSL de prueba](02-qa-y-vsls.md) muestra la rúbrica, decisiones consultivas y guiones de una productora, una agencia y un estudio de diseño. Todos los negocios y datos de ese ejercicio son ficticios.

## Alcance de la evidencia

Las pautas de escritura y estructura son un punto de partida. No garantizan un aumento de conversión. Es útil revisar reuniones realizadas, oportunidades que avanzan y ventas junto con las reproducciones del video.

La orientación sobre grupos compradores se apoya en [6sense](https://6sense.com/science-of-b2b/buyer-experience-report-2025/), [Edelman y LinkedIn](https://www.edelman.com/expertise/Business-Marketing/2025-b2b-thought-leadership-report) y los [trabajos de compra descritos por Gartner](https://www.gartner.com/en/sales/trends/sales-and-marketing-alignment). Son investigaciones B2B generales; el rendimiento del VSL para agencias y productoras de Latinoamérica se debe validar en su propio funnel.

## Licencia

MIT. Puedes usar, adaptar y compartir el skill conservando el aviso de copyright y la licencia.
