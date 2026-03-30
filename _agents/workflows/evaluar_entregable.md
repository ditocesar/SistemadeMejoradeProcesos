---
description: Evalúa el entregable Word de un grupo contra la rúbrica del hito correspondiente
---

# Workflow: Evaluar Entregable de un Grupo

## Parámetros requeridos
- **Grupo:** Número de grupo (01-16)
- **Hito:** Número de hito (1-5)
- **Documento:** Ruta al documento Word del grupo

## Pasos

1. Identificar el hito y cargar la rúbrica de evaluación correspondiente:
   - Hito 1 → `01_DEFINE/evaluaciones/hito1_define_examen.md`
   - Hito 2 → `02_MEASURE/evaluaciones/hito2_measure_examen.md`
   - Hito 3 → `03_ANALYZE/evaluaciones/hito3_parcial_examen.md`
   - Hito 4 → `04_IMPROVE/evaluaciones/hito4_improve_examen.md`
   - Hito 5 → `05_CONTROL/evaluaciones/hito5_final_examen.md`

2. Leer el documento entregado por el grupo.

3. Evaluar el documento contra los siguientes criterios generales:

   ### Criterios de Evaluación

   | # | Criterio | Peso | Descripción |
   |---|---------|------|------------|
   | 1 | Completitud | 20% | ¿Incluye todos los elementos requeridos? |
   | 2 | Calidad técnica | 30% | ¿Las herramientas se aplicaron correctamente? |
   | 3 | Coherencia | 15% | ¿Hay conexión lógica entre secciones? |
   | 4 | Evidencia empírica | 20% | ¿Usan datos reales? ¿Los análisis son válidos? |
   | 5 | Presentación | 15% | ¿Formato profesional, sin errores, bien organizado? |

4. Para cada sección del documento, verificar:
   - **Define:** ¿Project Charter completo? ¿Problema cuantificado? ¿SIPOC coherente? ¿VOC/CTQ con evidencia?
   - **Measure:** ¿Mapa de proceso detallado? ¿Datos reales recolectados? ¿Estadísticas correctas? ¿Capacidad calculada?
   - **Analyze:** ¿Ishikawa completo? ¿5 Porqués profundos? ¿Pruebas estadísticas válidas? ¿FMEA con RPN?
   - **Improve:** ¿Múltiples alternativas? ¿Selección con criterios? ¿To-Be credible? ¿Costo-beneficio cuantificado?
   - **Control:** ¿Plan de control completo? ¿Gráfico apropiado? ¿Plan de reacción? ¿Lecciones aprendidas?

5. Generar un reporte de evaluación con:
   - Puntaje por criterio (escala 0-20)
   - Puntaje total (escala 0-100)
   - Fortalezas identificadas (mínimo 3)
   - Áreas de mejora (mínimo 3)
   - Recomendaciones específicas para el siguiente hito

6. Guardar la evaluación en `GRUPOS/grupo_XX/retroalimentacion/evaluacion_hitoX.md`.

7. Actualizar el README del grupo con la nota y estado del hito.

## Ejemplo de uso
```
/evaluar_entregable
> Grupo: 03
> Hito: 2
> Documento: GRUPOS/grupo_03/entregables/hito2_measure.md
```
