---
description: Genera un examen de evaluación para un hito específico del curso DMAIC
---

# Workflow: Generar Examen por Hito

## Parámetros requeridos
- **Hito:** Número del hito (1-6)
- **Fase DMAIC:** Define / Measure / Analyze / Improve / Control / Exposición

## Pasos

1. Identificar el hito y la fase DMAIC correspondiente según el mapeo:
   - Hito 1 → Define (Semana 2)
   - Hito 2 → Measure (Semana 4)
   - Hito 3 → Parcial: Define+Measure+Analyze (Semana 7)
   - Hito 4 → Improve (Semana 10)
   - Hito 5 → Final: Todas las fases (Semana 13)
   - Hito 6 → Exposición Final (Semana 14)

2. Leer el sílabo en `00_SILABO/silabo_mejora_procesos.md` para identificar los contenidos específicos de las semanas correspondientes.

3. Leer el examen existente del hito correspondiente en la carpeta `XX_FASE/evaluaciones/` para usar como referencia de formato y estructura.

4. Si el usuario quiere un examen **nuevo** (diferente al existente), generar preguntas nuevas siguiendo esta estructura:
   - **Parte I: Teóricas (25-30%)** → Conceptos y definiciones de la fase
   - **Parte II: Prácticas (30-35%)** → Ejercicios con herramientas DMAIC
   - **Parte III: Aplicación al proyecto (35-40%)** → Preguntas sobre el caso real del grupo

5. Las preguntas deben cumplir con la taxonomía de Bloom:
   - Nivel 1-2: Recordar/Comprender → Parte I
   - Nivel 3-4: Aplicar/Analizar → Parte II
   - Nivel 5-6: Evaluar/Crear → Parte III

6. Incluir siempre una rúbrica de evaluación con 4 niveles: Excelente, Bueno, Regular, Deficiente.

7. Guardar el examen generado en la carpeta `XX_FASE/evaluaciones/` con el nombre `hitoX_FASE_examen_v2.md` (o v3, v4, según versión).

## Ejemplo de uso
```
/generar_examen
> Hito: 3
> Fase: Analyze (Parcial)
> Nota: Generar un examen alternativo al existente con énfasis en pruebas de hipótesis
```
