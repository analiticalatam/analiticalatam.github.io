# CONTEXTO — AnalíticaLatam

## URLs
- **Sitio principal:** https://analiticalatam.github.io/
- **Mapa electoral:** /mapa_peru_v10_actualizado.html
- **Voto extranjero:** /voto_extranjero.html
- **Repositorio 1 (site):** https://github.com/analiticalatam/analiticalatam.github.io
- **Repositorio 2 (backup):** https://github.com/analiticalatam/peru-elecciones-2026

## Archivos clave
- `/Users/catherinemilagros/Desktop/peru-elecciones-2026/index.html` — página principal
- `/Users/catherinemilagros/Desktop/peru-elecciones-2026/mapa_peru_v10_actualizado.html` — mapa interactivo 2026
- `/Users/catherinemilagros/Desktop/peru-elecciones-2026/voto_extranjero.html` — tabla voto exterior 2026
- `/Users/catherinemilagros/Desktop/peru-elecciones-2026/mapa_peru_2021.html` — mapa interactivo 2021
- `/Users/catherinemilagros/Desktop/peru-elecciones-2026/voto_extranjero_2021.html` — tabla voto exterior 2021
- `/Users/catherinemilagros/Desktop/peru-elecciones-2026/comparacion_2021_2026.html` — comparación lado a lado 2021 vs 2026
- Backups en `/Users/catherinemilagros/Downloads/backup_2026/`

## Feature: Botón Hero con float ovalado
- Animación `floatBtn` 2.8s: sube 16px, se desplaza 6px izq/der
- Tarjetas de países: se mecen lado a lado (`floatCard` 6s, 5px)
- Transición de panel: 1s cubic-bezier(.25,.46,.45,.94)

## Feature: Mapa — Total Nacional visible siempre
- `reg-table-card` visible desde el inicio (no solo en modo Ganador)
- `populateRegionTable()` se llama en carga inicial y al cambiar a modo Ganador

## Feature: Voto extranjero
- Botón permanente debajo de la leyenda de candidatos en el mapa
- Abre `voto_extranjero.html` (2026) o `voto_extranjero_2021.html` (2021) con tabla de países

## Feature: Comparación 2021 vs 2026
- Dos mapas D3 lado a lado (460×620px), modo ganador solamente
- Cross-highlighting: hover en un departamento lo resalta en ambos mapas
- Tooltips muestran datos de ambos años simultáneamente
- Tabla comparativa nacional: Electores, Votos emitidos, Participación, Blancos, Nulos, Blancos+Nulos con diferencias
- Leyenda con candidatos y conteo de regiones ganadas
- Callao inset en ambos mapas

## Equipo
- Catherine Paredes — Analista Política Perú (catherine.jpeg)
- Geovanna Valle — "Politóloga y abogada especializada en estudios subnacionales y representación política" (geovana.jpeg)
- Cristián Valarezo — Analista Chile (web/Cristrian.jpeg)
- Mariana Arzate — Analista México (mariana.jpeg)

## Redes
- Geovanna: https://linkedin.com/in/geovanna-valle-3a641319b (Twitter: #)
- Catherine: Twitter @catherinparedes, LinkedIn en tarjeta del equipo

## Etiquetas Ecuador
- "Elecciones seccionales en noviembre 2026"
- Tags: Seccionales, Noviembre 2026, Gobiernos locales
