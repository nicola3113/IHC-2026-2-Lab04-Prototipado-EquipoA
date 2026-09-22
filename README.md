# Laboratorio 04 · Prototipado de Interfaces para un Dashboard Bursátil

**Curso:** Interacción Hombre-Computador (202W0606) — Semestre 2026-2
**Universidad Nacional Mayor de San Marcos** · Facultad de Ingeniería de Sistemas e Informática · EP Ingeniería de Software
**Docente:** Mg. Ing. Ernesto D. Cancho-Rodríguez, MBA (GWU)
**Equipo A** · Lima, 18 de septiembre de 2026

Prototipo **Ernesto Investing AI**: una plataforma web de gestión de portafolio de inversiones
dirigida a traders minoristas e inversores principiantes. El trabajo recorre la escalera completa
de fidelidad —análisis de referencia, boceto en papel, wireframe y alta fidelidad— y termina en un
prototipo navegable.

---

## 🔗 Enlaces

| Recurso | Enlace |
|---|---|
| **App generada con Figma Make** (navegable, 4 pantallas) | https://auburn-squid-75629760.figma.site/ |
| **Dashboard en modo oscuro** (Figma Make) | https://scheme-open-12953100.figma.site/ |
| **Versión móvil del portafolio** (Figma Make) | https://blurry-slab-37286964.figma.site/ |
| **Figma Make** (archivo con los prompts ejecutados) | https://www.figma.com/make/9DfvD19QGGffIGtJfe47DP/Dise%C3%B1ar-pantalla-principal-Dashboard |
| **Archivo de diseño de Figma** (6 pantallas, solo lectura) | https://www.figma.com/design/5knvURBDiuYFFfjWi9aWve/Ernesto-Investing-AI---Prototipo-Lab-04---IHC-2026-2-Equipo-A |
| **Prototipo navegable** (Figma Prototype) | https://www.figma.com/proto/5knvURBDiuYFFfjWi9aWve/Ernesto-Investing-AI---Prototipo-Lab-04---IHC-2026-2-Equipo-A?node-id=19-8&starting-point-node-id=19%3A8&scaling=contain |
| **Informe consolidado (PDF, 63 pp.)** | [`entregables/06_documento_consolidado/`](entregables/06_documento_consolidado) |
| **Guion de la exposición en vídeo** | [`entregables/07_guion_exposicion/`](entregables/07_guion_exposicion) |
| **Wireframe en PlantUML** | [`entregables/03_wireframe_salt/`](entregables/03_wireframe_salt) |

---

## 👥 Equipo A

| Integrante | Código | Responsabilidad principal |
|---|---|---|
| Arboleda Sánchez, Ericka Sofía | 24200047 | Análisis de TradingView y anotación de capturas |
| Cabrejos Palomino, Christian Daniel | 23200242 | Pantalla 3 (órdenes) y validación del formulario |
| Ccoicca Fernández, Adrián | 24200154 | Coordinación; boceto ganador y layout base |
| Cerna Sifuentes, Augusto Nicolás | 24200053 | Pantallas 2 y 6, prompt propio y consolidación |
| Grijalva De La Cruz, Rony Smith | 24200058 | Pantalla 4 (versión móvil) y flujo móvil |
| Martines Cancho, Josué | 24200060 | Pantalla 5 (modo oscuro) y contrastes |
| Postigo Vega, Diana Carolina | 24200167 | Análisis de Yahoo Finance y tabla comparativa |
| Siesquen Torres, Katherine Lizbeth | 24200066 | Análisis de Investing.com y accesibilidad cromática |
| Tecsi Alanoca, Jean Carlo | 24200068 | Wireframe PlantUML Salt y verificación del código |
| Tonconi Isidro, María Sunori | 24200176 | Pantalla 1 y sistema de diseño compartido |
| Villegas Niño, Marco Antonio | 21200266 | Análisis de IBKR TWS y libro de órdenes |

---

## 📦 Entregables

| N.º | Entregable | Ubicación |
|---|---|---|
| 1 | Tabla comparativa de 4 plataformas + capturas anotadas | [`01_analisis_referencia/`](entregables/01_analisis_referencia) · Tabla 3 y Figuras 1-4 del informe |
| 2 | 11 bocetos en papel, ganador marcado | [`02_bocetos_papel/`](entregables/02_bocetos_papel) |
| 3 | Wireframe PlantUML Salt (.puml + PNG + SVG) | [`03_wireframe_salt/`](entregables/03_wireframe_salt) |
| 4 | Prototipo de alta fidelidad (5 + 1 pantallas) + los 6 prompts + las 6 salidas de Figma Make | [`04_prototipo_alta_fidelidad/`](entregables/04_prototipo_alta_fidelidad) |
| 5 | Prototipo navegable: 10 conexiones sobre las 6 pantallas | Enlace de Figma Prototype (arriba) · mapa de flujo y detalle en [`05_prototipo_navegable/`](entregables/05_prototipo_navegable) |
| 6 | Prompt propio del equipo (Tarea A — Leaderboard) | [`prompts/Prompt_6_Leaderboard_TareaA_EquipoA.txt`](entregables/04_prototipo_alta_fidelidad/prompts/Prompt_6_Leaderboard_TareaA_EquipoA.txt) |
| 7 | Documento consolidado (PDF + DOCX) | [`06_documento_consolidado/`](entregables/06_documento_consolidado) |
| — | Guion de la exposición en vídeo | [`07_guion_exposicion/`](entregables/07_guion_exposicion) |

---

## 🖥️ Las seis pantallas

| Frame | Contenido |
|---|---|
| **01** Dashboard principal (tema claro) | 4 tarjetas KPI, gráfico de velas con selector de periodo, Top Movers con sparklines y tabla de posiciones |
| **02** Watchlist y alertas | Cuadrícula de 9 activos, filtros y panel de alertas activas |
| **03** Ejecución de órdenes | 3 columnas: ficha del activo y libro de órdenes, gráfico interactivo, formulario con validación en tiempo real |
| **04** Versión móvil del portafolio | 3 vistas de 390 × 844 px conectadas por flujo |
| **05** Dashboard en modo oscuro | Paleta GitHub Dark / TradingView Dark con contraste verificado |
| **06** Leaderboard de la liga (Tarea A) | Podio, clasificación, portafolio simulado y logros |

### Sistema de diseño

| Elemento | Tema claro | Tema oscuro |
|---|---|---|
| Fondo | `#F0F2F6` | `#0D1117` |
| Tarjeta | `#FFFFFF` | `#161B22` |
| Azul corporativo | `#1F3864` | `#58A6FF` |
| Dorado de acento | `#C5961A` | `#C5961A` |
| Verde de ganancia | `#1B7E34` | `#238636` |
| Rojo de pérdida | `#C62828` | `#DA3633` |

Radio de esquina 12 px (16 px en móvil) · Tipografía Inter/Segoe UI · Cifras en Consolas tabular.
Contraste del texto principal: 15.9:1 en claro y 14.8:1 en oscuro (mínimo AAA: 7:1).

---

## 🗂️ Estructura

```
S4/
├── insumos/                          Material original del Classroom
├── entregables/
│   ├── 01_analisis_referencia/       4 figuras anotadas
│   ├── 02_bocetos_papel/             11 bocetos
│   ├── 03_wireframe_salt/            .puml / .png / .svg / URL
│   ├── 04_prototipo_alta_fidelidad/  prompts/ (6 prompts) + figma_make/ (6 capturas)
│   ├── 05_prototipo_navegable/       mapa de flujo + ENLACES.md
│   ├── 06_documento_consolidado/     Informe .docx y .pdf
│   └── 07_guion_exposicion/          Guion .docx y .pdf
├── LEEME_Entregables.md
└── README.md
```

---

## ▶️ Cómo revisar

1. **Prototipo:** abrir el enlace de Figma Prototype. Arranca en el Dashboard; desde ahí se llega a
   la Watchlist (menú lateral), a la Ejecución de órdenes (tabla de posiciones o tarjeta de activo),
   al modo oscuro (ícono de configuración) y al Leaderboard (ícono de trofeo). El logotipo de la
   barra superior devuelve siempre al Dashboard.
2. **Interacción real:** para probar filtros, pestañas y formularios, abrir las tres aplicaciones de
   Figma Make enlazadas arriba.
3. **Informe:** `entregables/06_documento_consolidado/Informe_Lab04_Prototipado_Interfaces_EquipoA.pdf`,
   en formato APA 7.
4. **Vídeo:** seguir el guion de `entregables/07_guion_exposicion/`. Son 12 bloques repartidos entre
   los once integrantes, ninguno de más de 3 minutos; cada bloque indica qué decir y qué mostrar en
   pantalla.

---

## 🧪 Sobre Figma Make

**Las seis pantallas del laboratorio se generaron con Figma Make**, a partir de los seis prompts
hiperdetallados que están en [`04_prototipo_alta_fidelidad/prompts/`](entregables/04_prototipo_alta_fidelidad/prompts).
Las capturas de lo que devolvió la herramienta están en
[`04_prototipo_alta_fidelidad/figma_make/`](entregables/04_prototipo_alta_fidelidad/figma_make).

| # | Pantalla | Tiempo de generación | App publicada |
|---|---|---|---|
| 1 | Dashboard principal | 2 min 38 s | https://auburn-squid-75629760.figma.site/ |
| 2 | Watchlist y alertas | misma sesión | https://auburn-squid-75629760.figma.site/ |
| 3 | Ejecución de órdenes | 7 min 52 s | https://auburn-squid-75629760.figma.site/ |
| 4 | Leaderboard (Tarea A) | 5 min 53 s | https://auburn-squid-75629760.figma.site/ |
| 5 | Dashboard en modo oscuro | 2 min 41 s | https://scheme-open-12953100.figma.site/ |
| 6 | Versión móvil del portafolio | 3 min 3 s | https://blurry-slab-37286964.figma.site/ |

El plan gratuito de Figma reparte un **cupo mensual** de créditos de IA que se agotó en la cuarta
generación y no se renueva hasta el 30 de septiembre de 2026, así que las dos últimas pantallas se
generaron al día siguiente con el crédito de otra integrante del equipo. Esa es la razón de que el
trabajo se repartiera en tres días. El proceso completo, con tiempos, desviaciones y correcciones,
está documentado en la sección 7.1 del informe.

**Una limitación del plan gratuito:** el botón «Copy design», que vuelca el resultado de Make al
lienzo de diseño como capas editables, pertenece al plan Professional («Can't copy design layers
from Figma Make» en el plan Starter). Por eso el archivo de diseño contiene la captura a tamaño real
de cada pantalla, encuadrada en un frame con su nombre, y las conexiones del prototipo se tendieron
con diez zonas activas transparentes sobre los controles correspondientes. El detalle está en la
sección 8 del informe.


---

> **Aviso.** Todas las cifras, tickers y participantes que aparecen en el prototipo son datos
> simulados con fines didácticos. No constituyen información financiera real ni recomendación de
> inversión alguna.
