---
description: Genera retroalimentación detallada para un grupo después de la revisión de un hito
---

# Workflow: Generar Retroalimentación por Grupo

## Parámetros requeridos
- **Grupo:** Número de grupo (01-16)
- **Hito:** Número de hito evaluado (1-6)
- **Evaluación previa:** Opcional, ruta a la evaluación realizada con `/evaluar_entregable`

## Pasos

1. Leer la evaluación del hito correspondiente:
   - Si existe evaluación previa en `GRUPOS/grupo_XX/retroalimentacion/evaluacion_hitoX.md`, usarla como base
   - Si no, leer el documento del grupo y evaluar internamente

2. Leer las plantillas y rúbricas del hito para contrastar el entregable con lo esperado.

3. Generar retroalimentación constructiva con la siguiente estructura:

   ### Formato de Retroalimentación

   ```markdown
   # Retroalimentación - Grupo XX - Hito Y

   ## Resumen General
   [Párrafo con impresión general del trabajo]

   ## 🟢 Fortalezas (lo que hicieron bien)
   1. [Fortaleza específica con ejemplo del documento]
   2. [Fortaleza]
   3. [Fortaleza]

   ## 🟡 Áreas de Mejora (lo que pueden mejorar)
   1. [Área de mejora con recomendación concreta]
   2. [Área de mejora]
   3. [Área de mejora]

   ## 🔴 Errores Críticos (lo que deben corregir)
   1. [Error con explicación de por qué es incorrecto y cómo corregirlo]
   2. [Error]

   ## 📋 Recomendaciones para el Próximo Hito
   1. [Recomendación específica y accionable]
   2. [Recomendación]
   3. [Recomendación]

   ## Nota
   | Criterio | Nota (/20) |
   |---------|-----------|
   | Completitud | |
   | Calidad técnica | |
   | Coherencia | |
   | Evidencia empírica | |
   | Presentación | |
   | **Total** | **/100** |
   ```

4. Principios de la retroalimentación:
   - **Específica:** Referirse a secciones o datos concretos del documento
   - **Constructiva:** Siempre incluir cómo mejorar, no solo señalar errores
   - **Balanceada:** Reconocer lo bueno antes de señalar lo malo
   - **Accionable:** Las recomendaciones deben ser claras y ejecutables
   - **Formativa:** Orientada al aprendizaje, no solo calificativa

5. Guardar en `GRUPOS/grupo_XX/retroalimentacion/retroalimentacion_hitoX.md`.

## Ejemplo de uso
```
/generar_retroalimentacion
> Grupo: 07
> Hito: 3
> Evaluación previa: GRUPOS/grupo_07/retroalimentacion/evaluacion_hito3.md
```
