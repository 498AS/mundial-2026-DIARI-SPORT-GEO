# Changelog

> Historial del dossier de la serie «Así lo ve la IA» publicada en Sport.

## [v1.6] - 2026-06-21

**Sport-isms: "es de gol" + "Estados Unidos" en lugar de "en aquel país"**

- *"La paradoja es magnífica"* → *"La paradoja es de gol"*. Más Sport-flavor (frase hecha del aficionado: *"eso fue de gol"*, *"jugada de gol"*), y ahorra 2 caracteres.
- *"la cifra más alta del fútbol en aquel país"* → *"la cifra más alta del fútbol en Estados Unidos"*. Más directo y journal-style; rompe la elegancia anafórica de "aquel país" a cambio de una claridad inmediata más afín al lector de Sport.
- Caracteres: 2.023 → **2.022** (dentro de rango canónico 1.875–2.030).

## [v1.5] - 2026-06-21

**Fix de ambigüedad: aclarado que el 72% de cuota es en México**

- El stat *"México-Sudáfrica, 23,4 millones y un 72% de cuota"* podía leerse, mal, como continuación de la audiencia USA del párrafo anterior. La realidad documentada (Goal.com, Yahoo Sports, Newsnation) es que tanto los **23,4 millones de espectadores** como el **72,1% de cuota de pantalla** son **en México** (la mayor audiencia del fútbol mexicano del siglo XXI; tres de cada cuatro televisores encendidos en el país sintonizando a El Tri).
- Fix: añadido *"en México"* al final del stat → *"…un 72% de cuota en México."* Ata la cifra al país sin romper el ritmo.
- Compensación de caracteres: quitado *"de espectadores"* tras los 27,5 millones de USA-Paraguay (el contexto deja claro que son viewers, no dinero). Net: -6 caracteres.
- Caracteres: 2.028 → **2.023** (dentro de rango canónico 1.875–2.030).

## [v1.4] - 2026-06-21

**Pasada humanizer + ortografía final para Sport**

- Auditoría completa del #8 antes de enviar al diario: acentos y tildes (más, vacío, magnífica, México, Sudáfrica, récords, vívelo, también, está, pública, millón, dependía), comillas dobles consistentes, decimales con coma, miles con punto, cero em-dashes, concordancia sg/pl, casting de las 3 IAs en presente.
- **Fix de exactitud factual**: *"con semifinales que pasaron de 473 a 13 dólares en horas"* → *"con **una semifinal** que pasó de 473 a 13 dólares en horas"*. La realidad documentada por The Athletic, SI y ESPN es **una sola** semifinal del Club World Cup 2025 (Chelsea-Fluminense, MetLife) cayendo de 473,90 a 13,40 dólares. El plural era atacable en un fact-check; el singular es defendible al 100%.

## [v1.3] - 2026-06-21

**Añadida la referencia al Club World Cup 2025 como precedente verificable**

- Nueva línea en P2 después del *"Lo curioso es que la IA ya lo había avisado"*: *"Y eso que no hacía falta una IA: el Club World Cup 2025 ya había hecho el ensayo, con semifinales que pasaron de 473 a 13 dólares en horas."*
- Decisión narrativa: la IA va primero (continuidad con la serie *Así lo ve la IA*), el Club World Cup justo después como **antídoto a la chulería tecnológica** — humilde, verificable y refuerza el diagnóstico sin presumir.
- Doble validación implícita: el patrón era humanamente predecible (Club World Cup); la IA solo lo cuantificó (85% / 67% / 10%).
- Trims para mantener rango canónico: dropeado el aforismo *"Y el dinero, cuando un torneo lo monta así, no es una variable: es la regla."* (redundante con la referencia Club World Cup); *"Por si quedaba alguna duda,"* (humanizer perdible); *"La propia FIFA"* → *"La FIFA"*.
- Caracteres: 1.998 → **2.028** (dentro de rango canónico 1.875–2.030).

## [v1.2] - 2026-06-21

**Pulido del #8: la frase de Claude con dato propio**

- Reescrita la frase de Claude para darle dato propio (su característica más distintiva: la **ventana de contexto de un millón de palabras**, real para Claude Opus 4.x). Antes: *"el intelectual, llega a la misma conclusión por otro camino"* — vago, recicla la fórmula del corpus #2. Ahora: *"el intelectual con un millón de palabras en la cabeza, se salta el bolsillo y va al fondo"* — el "se salta el bolsillo" hace contraste limpio con el "tira por la prudencia" de Gemini.
- Números grandes a dígitos para consistencia interna: *"veintinueve de los ciento cuatro"* → *29 de los 104*; *"noventa de los ciento cuatro"* → *90 de los 104*.
- Caracteres: 2.002 → **1.998** (sigue en rango canónico 1.875–2.030).

## [v1.1] - 2026-06-21

**Humanización del #8 «Mundial sin gradas» con sistema Zoopa**

- Aplicado el humanizer (sistema Smart Brevity + Voz Zoopa de `_system/system_prompt_writerbatch_zoopa.md`): ritmo alternado, frases más directas, ningún jergón corporativo, tono de "colega listo, no marca difundiendo".
- Nueva apertura con el fragmento **«Estadio medio vacío, TV en récords históricos.»** como gancho de primera línea (la frase resume la paradoja en seis palabras y deja que el cuerpo la desarrolle).
- Conector conversacional añadido (*"Por si quedaba alguna duda…"*) para introducir el dato del 30% de comisión del FIFA Marketplace sin sonar a informe.
- Vocabulario variado en repeticiones de "bate récords" → "revienta la audiencia".
- Caracteres: 1.937 → **2.002** (dentro de rango canónico 1.875–2.030).

## [v1.0] - 2026-06-21

**Lanzamiento del repo público con el dossier completo**

- 8 artículos canónicos (#1 a #8) consolidados en `articulos/`.
- 3 piezas exploratorias no canónicas en `exploratorios/`.
- Originales `.docx` del autor en `originales/` como referencia editorial.
- Estudio GEO Mundial 2026 (informe fuente) en `estudio/`.
- Guía de estilo v2 con prompt generador y checklist pre-publicación en `guia-estilo.md`.
- README con índice, especificaciones técnicas, casting de motores y enlaces al estudio.

### Artículos incluidos
1. *El Mundial como laboratorio* — manifiesto de la serie.
2. *La pregunta del millón* — favoritos y casas de apuestas.
3. *Un Mundial desde el sofá* — viajar vs ver en casa.
4. *Tim Payne, llegar tarde al chiste* — viralidad y economía de la atención.
5. *Tres mundiales en uno* — sedes (México · USA · Canadá).
6. *La FIFA organiza, YouTube manda* — fuentes y narrativa.
7. *Las malas lenguas del Mundial* — idioma y sesgo lingüístico.
8. *Mundial sin gradas* — TV récord + estadios a medias + dynamic pricing.

### Procedencia del corpus
- Artículos #1 a #7 + estudio fuente: recuperados del proyecto canónico
  `contentfactory/asi-lo-ve-la-ia/` (sesión de redacción jun 2026).
- Artículo #8 redactado en esta versión a partir de la guía v2 + datos del arranque del torneo.
- Guía v2 ampliada con el corpus completo (originalmente cubría solo #1–#5).
