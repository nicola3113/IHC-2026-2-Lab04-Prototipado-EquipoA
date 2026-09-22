# Prompts autónomos para Figma Make

Cada archivo `LISTO_*.txt` de esta carpeta es un prompt completo y autónomo: lleva pegado al
inicio el sistema de diseño del proyecto y los datos de muestra, para que la pantalla salga
coherente con las demás aunque se genere desde una cuenta y una sesión distintas.

> **Estado: las seis pantallas ya están generadas con Figma Make.** Esta carpeta se conserva
> como registro del reparto y para poder reproducir cualquier pantalla desde cero.

## Reparto y resultado

| Archivo | Pantalla | Generada en | App publicada |
|---|---|---|---|
| `LISTO_4_Movil_Portafolio.txt` | Versión móvil del portafolio (3 vistas de 390 × 844 px) | 3 min 3 s | https://blurry-slab-37286964.figma.site/ |
| `LISTO_5_Dashboard_Oscuro.txt` | Dashboard en modo oscuro | 2 min 41 s | https://scheme-open-12953100.figma.site/ |
| `LISTO_6_Leaderboard_TareaA.txt` | Leaderboard de la liga (Tarea A) | 5 min 53 s | https://auburn-squid-75629760.figma.site/ |

Las capturas de las seis salidas están en `../../figma_make/`.

## Pasos para reproducir una pantalla

1. Iniciar sesión en https://www.figma.com con la cuenta propia.
2. En la barra superior, pulsar el botón **Make**.
3. Abrir el archivo `.txt` que corresponda, seleccionar todo el texto y copiarlo.
4. Pegarlo en el campo «Describe your idea» y pulsar Enter.
5. Esperar. La generación tarda entre 2 y 8 minutos; la barra dice «Working for…».
6. Cuando termine, renombrar el archivo arriba a la izquierda como
   `Ernesto Investing AI - <nombre de la pantalla> - Equipo A`.
7. Pulsar **Publish** y copiar el enlace de la aplicación publicada.

## Advertencias

- **El plan gratuito da un cupo mensual de créditos de IA**, no diario. En esta cuenta se agotó
  en la cuarta generación y el aviso indicaba que no se renovaría hasta el 30 de septiembre
  de 2026. Por eso las dos últimas pantallas se generaron con el crédito de otra integrante.
- **No crear cuentas nuevas** para saltar ese límite: va contra los términos de Figma. Cada
  integrante usa la suya.
- Al publicar, Figma ofrece incluir el historial del chat en la página pública. Conviene
  desactivar esa opción antes de confirmar.
- Si el resultado se desvía del prompt (cambia el activo, el nombre del usuario o el número de
  Top Movers), la corrección consume otra generación: hay que decidir si vale la pena o si se
  documenta la desviación en el informe, como se hizo en la sección 7.1.
