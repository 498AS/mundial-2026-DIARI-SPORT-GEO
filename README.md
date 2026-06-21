# Mundial 2026 · «Así lo ve la IA» · Sport / GEO

> Serie editorial publicada en **Sport** sobre el Mundial FIFA 2026 cruzada con la auditoría GEORadar de cómo ChatGPT, Gemini y Claude representan el torneo a sus aficionados. El fútbol es la excusa; **la IA es el objeto de estudio**.

| | |
|---|---|
| **Sección** | Así lo ve la IA |
| **Firma** | Carlos Ortet · Enric Jové |
| **Medio** | Sport |
| **Producción** | Zoopa · 498A Innovation Lab · GEORadar |
| **Estado** | 🟢 8 artículos publicables (junio 2026, ventana pre-evento + arranque del torneo) |
| **Estudio fuente** | [Informe GEO Mundial FIFA 2026](https://498as.github.io/mundial-2026-geo-audit/informe.html) |

---

## TL;DR

Cientos de millones de aficionados están preguntando al Mundial a una IA antes que a un periodista. Esta serie audita esas respuestas — y revela los sesgos por motor, idioma y origen del usuario. **No buscamos respuestas, auditamos a la máquina.**

- 8 columnas publicadas, ~1.900 caracteres cada una.
- 3 motores como personajes fijos: **ChatGPT** (disfrutón), **Gemini** (tertuliano cauto), **Claude** (intelectual).
- Datos del estudio GEO embebidos como observación, nunca como producto.
- Guía de estilo + prompt generador en [`guia-estilo.md`](guia-estilo.md) para escribir nuevas entregas.

---

## Estructura del repo

```
mundial-2026-DIARI-SPORT-GEO/
├── README.md                        ← Este archivo
├── CHANGELOG.md                     ← Historial de la serie
├── guia-estilo.md                   ← ⭐ Libro de estilo v2 + prompt generador + checklist
├── articulos/                       ← 8 columnas canónicas (publicables)
├── exploratorios/                   ← 3 piezas no canónicas (borrador / referencia)
├── originales/                      ← .docx originales del autor
└── estudio/
    └── mundial-2026-geo-audit.md    ← Informe GEO fuente de datos
```

---

## Los 8 artículos canónicos

| # | Título | Tema | Caracteres |
|---|---|---|---:|
| 1 | [El Mundial como laboratorio](articulos/01-el-mundial-como-laboratorio.md) | Manifiesto / presentación de la serie | 2.034 |
| 2 | [La pregunta del millón](articulos/02-la-pregunta-del-millon.md) | Favoritos · ¿quién ganará? | 2.027 |
| 3 | [Un Mundial desde el sofá](articulos/03-un-mundial-desde-el-sofa.md) | Viajar vs verlo en casa | 1.874 |
| 4 | [Tim Payne, llegar tarde al chiste](articulos/04-tim-payne-llegar-tarde-al-chiste.md) | Viralidad y economía de la atención | 1.883 |
| 5 | [Tres mundiales en uno](articulos/05-tres-mundiales-en-uno.md) | México · USA · Canadá como sedes | 1.887 |
| 6 | [La FIFA organiza, YouTube manda](articulos/06-la-fifa-organiza-youtube-manda.md) | Fuentes · ¿quién narra el torneo? | 2.014 |
| 7 | [Las malas lenguas del Mundial](articulos/07-las-malas-lenguas-del-mundial.md) | Idioma · sesgo lingüístico | 1.915 |
| 8 | [Mundial sin gradas](articulos/08-mundial-sin-gradas.md) | TV récord + estadios a medias · dynamic pricing | 2.002 |

**Total**: ~15.700 caracteres · 2.570 palabras · media 1.954 car. / 321 pal.

---

## Piezas exploratorias (no canónicas)

Borradores con ángulos interesantes que aún no se han integrado en el canon. Pueden servir como base para futuras entregas tras edición editorial.

| Pieza | Ángulo |
|---|---|
| [El LinkedIn de Cabo Verde](exploratorios/el-linkedin-de-cabo-verde.md) | Diáspora + IA como acelerador de scouting |
| [La IA suspende en titulares](exploratorios/la-ia-suspende-en-titulares.md) | Las 3 IAs escribiendo el titular de España 0-0 Cabo Verde (técnica meta) |
| [Messi, Cristiano y el eterno debate](exploratorios/messi-cristiano-eterno-debate.md) | Contraste bilingüe (ES vs PT) sobre la misma pregunta |

---

## Cómo escribir la próxima entrega

1. Abrir [`guia-estilo.md`](guia-estilo.md) y copiar el **prompt generador** (sección 14).
2. Rellenar `<<TEMA>>` y `<<DATOS>>` (los datos salen del [estudio fuente](estudio/mundial-2026-geo-audit.md)).
3. Pegar en una sesión nueva de Claude, ChatGPT o el LLM elegido.
4. Validar contra la **checklist** (sección 12): 1.875–2.030 caracteres, una tríada o antítesis, cero em-dashes, casting de las IAs respetado.

---

## El casting fijo

Lo más distintivo de la serie: las 3 IAs son personajes con voz propia.

| Motor | Personalidad | Comportamiento |
|---|---|---|
| **ChatGPT** (OpenAI) | Práctico · disfrutón · joven · se moja | Cita web en vivo, decidido (elige sede en 90% de respuestas), invita a "vivir a tope" |
| **Gemini** (Google) | Tertuliano cauto · estadístico · mira por tu dinero | "Depende" en 29% de respuestas, bebe de YouTube y creadores, chauvinista en francés |
| **Claude** (Anthropic) | El intelectual | Llega a las mismas conclusiones por otro camino, *más de laboratorio que de tertulia* |

---

## Especificaciones técnicas (la regla de oro)

- **Longitud**: ~1.900 caracteres con espacios (título incluido), rango 1.875–2.030.
- **Palabras**: ~310, rango 299–362.
- **Idioma**: español, con anglicismos irónicos y guiños rioplatenses.
- **Tipografía**: cero em-dashes (— ni –). Coma, punto y coma, dos puntos, paréntesis.
- **Estructura**: 4 movimientos (título · gancho · desarrollo con cifras · cierre aforístico).

Detalle completo en [`guia-estilo.md`](guia-estilo.md).

---

## El estudio fuente

Las cifras vienen del **Informe GEO Mundial FIFA 2026** (ZOOPA / 498 Advisory Services):

- 4.690 respuestas IA · 17 perfiles de aficionado · 4 idiomas (ES · EN · PT · FR) · 2 motores (ChatGPT, Gemini).
- Versión completa en este repo: [`estudio/mundial-2026-geo-audit.md`](estudio/mundial-2026-geo-audit.md).
- Web oficial: https://498as.github.io/mundial-2026-geo-audit/informe.html
- PDF: https://498as.github.io/mundial-2026-geo-audit/informe.pdf

---

## Créditos

**Autores**: [Carlos Ortet](https://carlosortet.com) (publicista · CEO Zoopa · Director 498A) · Enric Jové (científico).
**Medio publicador**: Diari Sport.
**Producción y datos**: Zoopa · 498A Innovation Lab · GEORadar.
**Contacto prensa**: carlos.ortet@zoopa.es · +34 627 954 480

---

## Licencia

Propietario · Zoopa / 498A · 2026. Los artículos son propiedad de Sport y se reproducen aquí como dossier consolidado de la serie.
