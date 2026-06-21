# Changelog

> Historial del dossier de la serie «Así lo ve la IA» publicada en Sport.

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
