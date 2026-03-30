---
description: Genera una presentación según la fase DMAIC y las semanas del sílabo
---

# Workflow: Generar Presentación por Fase DMAIC

## Parámetros requeridos
- **Fase DMAIC:** Define / Measure / Analyze / Improve / Control
- **Semanas:** Rango de semanas (ej: 3-5)
- **Enfoque especial:** Opcional, tema a enfatizar

## Pasos

1. Leer el sílabo en `00_SILABO/silabo_mejora_procesos.md` para identificar los contenidos de las semanas solicitadas.

2. Leer la presentación existente de la fase en `XX_FASE/presentaciones/` para usar como referencia de formato.

3. Generar la presentación con la siguiente estructura por slide:
   - **Slide 1:** Portada (título, subtítulo, semanas, curso)
   - **Slide 2:** Objetivos de aprendizaje (3-5 objetivos)
   - **Slides 3-N:** Contenido teórico con:
     - Definiciones claras y concisas
     - Tablas comparativas
     - Diagramas/esquemas en texto (usando ASCII art o markdown)
     - Ejemplos prácticos relevantes
     - Fórmulas cuando apliquen
   - **Slide N+1:** Actividades por semana
   - **Slide N+2:** Entregable del hito correspondiente

4. Incluir en cada slide:
   - Contenido visual (tablas, listas, diagramas)
   - Máximo 6-8 líneas de texto por slide
   - Ejemplos del mundo real
   - Conexión con el proyecto de los estudiantes

5. Si hay un enfoque especial solicitado por el usuario, ampliar ese tema con más slides y mayor profundidad.

6. Guardar en la carpeta correspondiente `XX_FASE/presentaciones/` con formato `semXX-XX_tema_presentacion.md`.

## Ejemplo de uso
```
/generar_presentacion
> Fase: Analyze
> Semanas: 6-8
> Enfoque: Mayor profundidad en pruebas de hipótesis con ejemplos de manufactura
```
