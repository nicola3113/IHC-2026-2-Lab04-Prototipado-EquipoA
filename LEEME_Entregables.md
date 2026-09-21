# Laboratorio 04 — Prototipado de Interfaces · Equipo A

Curso: Interacción Hombre-Computador (202W0606) · Semestre 2026-2
Universidad Nacional Mayor de San Marcos · FISI · EP Ingeniería de Software
Fecha: 18 de septiembre de 2026

## Enlaces del prototipo

| Recurso | Enlace |
|---------|--------|
| App generada con Figma Make (navegable) | https://auburn-squid-75629760.figma.site/ |
| Figma Make (archivo con los prompts) | https://www.figma.com/make/9DfvD19QGGffIGtJfe47DP/Dise%C3%B1ar-pantalla-principal-Dashboard |
| Archivo de Figma (vista, 7 pantallas) | https://www.figma.com/design/5knvURBDiuYFFfjWi9aWve/Ernesto-Investing-AI---Prototipo-Lab-04---IHC-2026-2-Equipo-A |
| Prototipo navegable (Figma Prototype) | https://www.figma.com/proto/5knvURBDiuYFFfjWi9aWve/Ernesto-Investing-AI---Prototipo-Lab-04---IHC-2026-2-Equipo-A?node-id=1-23&starting-point-node-id=1-23&scaling=contain |
| Prototipo ejecutable en navegador | `entregables/05_prototipo_navegable/index.html` |

Ambos enlaces de Figma están configurados como **cualquier persona con el enlace puede ver**.

## Mapa de entregables exigidos por la guía

| N.º | Entregable | Formato pedido | Dónde está |
|-----|-----------|----------------|------------|
| 1 | Tabla comparativa de plataformas de referencia | Word editable | Sección 4 y Tabla 3 del informe; capturas anotadas en `entregables/01_analisis_referencia/` |
| 2 | Bocetos en papel (uno por integrante, ganador marcado) | JPG/PNG | `entregables/02_bocetos_papel/` (11 archivos; `boceto_01.png` es el ganador) |
| 3 | Wireframe PlantUML Salt | .puml + PNG | `entregables/03_wireframe_salt/` (`.puml`, `.png`, `.svg` y URL permanente) |
| 4 | Prototipo Figma (5 + 1 pantallas) | Enlace Figma (view) | Enlace arriba; capturas en `entregables/04_prototipo_alta_fidelidad/`; los 6 prompts en `.../prompts/`; salida real de Figma Make (4 pantallas) en `.../figma_make/` |
| 5 | Prototipo navegable | Enlace Figma Prototype | Enlace arriba; versión HTML en `entregables/05_prototipo_navegable/index.html` |
| 6 | Prompt propio del equipo (Tarea A) | Texto en el documento | Sección 10.1 del informe y `.../prompts/Prompt_6_Leaderboard_TareaA_EquipoA.txt` |
| 7 | Documento de entrega consolidado | PDF | `entregables/06_documento_consolidado/` (.pdf de 66 pp. y .docx editable) |
| — | Guion de la exposición en vídeo | — | `entregables/07_guion_exposicion/` (.docx y .pdf) |

## Estructura de carpetas

```
S4/
├── insumos/                         Material descargado del Classroom (guía, listas, imágenes de referencia)
├── entregables/
│   ├── 01_analisis_referencia/      4 figuras anotadas: Yahoo Finance, TradingView, Investing.com, IBKR TWS
│   ├── 02_bocetos_papel/            11 bocetos digitalizados (boceto_01 = ganador por votación)
│   ├── 03_wireframe_salt/           dashboard_wireframe.puml / .png / .svg / plantuml_url.txt
│   ├── 04_prototipo_alta_fidelidad/ 7 capturas + prompts/ (6 prompts) + figma_make/ (salida real de la herramienta)
│   ├── 05_prototipo_navegable/      index.html + 6 pantallas HTML + assets/ (CSS y SVG)
│   ├── 06_documento_consolidado/    Informe .docx y .pdf
│   └── 07_guion_exposicion/         Guion del vídeo .docx y .pdf
└── LEEME_Entregables.md             este archivo
```

## Las siete pantallas del prototipo

| Frame en Figma | Contenido |
|----------------|-----------|
| 01 Dashboard principal (tema claro) | KPI, gráfico de velas, Top Movers y tabla de posiciones |
| 02 Watchlist y alertas | Cuadrícula de activos, filtros y panel de alertas activas |
| 02b Watchlist — modal Nueva alerta | Cuadro de diálogo modal de creación de alerta |
| 03 Ejecución de órdenes | Libro de órdenes, gráfico interactivo y formulario con validación |
| 04 Versión móvil del portafolio | Tres vistas de 390 × 844 px conectadas por flujo |
| 05 Dashboard (modo oscuro) | Variante nocturna con paleta GitHub Dark / TradingView Dark |
| 06 Leaderboard de la liga (Tarea A) | Ranking, puntuación, portafolio simulado y logros |

## Cómo abrir el prototipo ejecutable

Abrir `entregables/05_prototipo_navegable/index.html` con Chrome, Edge o Firefox, con la ventana
maximizada y el zoom al 100 %. Las siete pantallas están enlazadas entre sí mediante puntos
calientes sobre los controles reales (menú lateral, botones de la tabla, conmutador de tema);
desde cualquiera se vuelve al Dashboard pulsando el logotipo de la barra superior.

## Pendiente

Grabar el vídeo de exposición siguiendo el guion de `07_guion_exposicion/`. El guion reparte la
exposición en 12 bloques entre los once integrantes, con un máximo de 3 minutos por persona.

> Nota: todas las cifras del prototipo son simuladas y tienen fines didácticos; no constituyen
> información financiera real.
