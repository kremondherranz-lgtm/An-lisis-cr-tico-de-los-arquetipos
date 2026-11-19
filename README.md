# Análisis crítico de los arquetipos

Estudio del mercado automotriz en La Habana: oferta formal e informal, demanda, fuentes complementarias y análisis crítico de los arquetipos que estructuran ese mercado.

## Contenido

| Ruta | Descripción |
|---|---|
| `arquetipo_historia_analisis_critico_.docx` | Documento principal del análisis crítico. Su contexto y análisis se resumen en [`README_arquetipo_historia_analisis_critico.md`](README_arquetipo_historia_analisis_critico.md). |
| `data/` | Datos del estudio: `raw/` (fuentes sin procesar), `processed/` (encuesta limpia, informe, tablas y gráficas) y `journals/` (notas de trabajo). Ver `data/README.md`. |
| `docs/` | Documentación metodológica, catálogos e informes de fuentes externas y diarios de investigación. Ver `docs/README.md`. |

## Fuentes de datos

- **Oferta formal:** catálogos de Dongfeng Cuba, MCV Comercial, Womy y BDC One.
- **Oferta informal:** muestra de 100 anuncios de Revolico.
- **Demanda:** exportaciones del formulario de Google Forms sobre el mercado automotriz en La Habana (11 respuestas válidas) y preferencias de propulsión.
- **Complementarias:** registros de vehículos eléctricos (particulares y entidades estatales), arrendadores de vivienda en La Habana y estadísticas de ONEI.

## Análisis y metodología

- `docs/methodology/ANALISIS_POR_PREGUNTA_Y_RESPUESTAS.md`: codificación de variables, frecuencias y porcentajes por pregunta, respuestas abiertas, hallazgos y resumen ejecutivo.
- `docs/methodology/Explicacion_pasos_seguidos_4_11_2026_metodologia_oficial_corregido.docx`: descripción del proceso seguido.
- `data/processed/INFORME_4_11_2026_con_interpretaciones.docx`: informe con interpretaciones de los resultados.
- `data/processed/tablas_graficas/`: tablas y gráficas del análisis exploratorio.

## Notas

- Los precios se conservan en su moneda original.
- Los archivos temporales de Microsoft Office (`~$*`) se excluyen del repositorio mediante `.gitignore`.
- Los resultados de la encuesta son exploratorios: la muestra válida es pequeña (11 casos).
- `data/processed/unified_cars.csv` se regenera desde los CSV de `data/raw/` y no está versionado.
