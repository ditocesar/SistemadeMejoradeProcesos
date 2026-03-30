---
description: Genera preguntas personalizadas para la exposición final basadas en el documento Word del grupo
---

# Workflow: Generar Preguntas para Exposición Final

## Parámetros requeridos
- **Grupo:** Número de grupo (01-16)
- **Documento:** Ruta al documento Word final del grupo (Hito 5)
- **Número de preguntas:** 4-8 (default: 6)

## Pasos

1. Leer el documento Word final del grupo especificado. Si el documento está en la carpeta del grupo (`GRUPOS/grupo_XX/entregables/hito5_final.md`), leerlo de ahí.

2. Leer el banco de preguntas general en `06_EXPOSICION_FINAL/preguntas_generador.md` para referencia.

3. Analizar el documento buscando:
   - **Inconsistencias** entre fases (ej: causas raíz que no se atacan en Improve)
   - **Datos específicos** que los estudiantes deben poder explicar
   - **Decisiones no justificadas** o débilmente justificadas
   - **Herramientas mal aplicadas** o con errores
   - **Fortalezas** del proyecto para preguntas de profundización
   - **Lagunas** en el análisis o documentación

4. Generar preguntas personalizadas con la siguiente estructura:

   ```
   | # | Pregunta | Dirigida a | Tipo | Fase DMAIC | Nivel Bloom |
   |---|---------|-----------|------|-----------|------------|
   | 1 | [Pregunta específica del proyecto] | [Miembro o cualquiera] | Inconsistencia/Profundización/Defensa | D/M/A/I/C | Comprensión/Aplicación/Análisis/Evaluación |
   ```

5. Asegurar que:
   - Al menos 1 pregunta por fase DMAIC
   - Preguntas distribuidas entre diferentes miembros del equipo
   - Mix de niveles de dificultad
   - Al menos 2 preguntas que requieran cálculos o datos específicos
   - Al menos 1 pregunta integradora que conecte múltiples fases
   - Al menos 1 pregunta que desafíe supuestos del proyecto

6. Guardar las preguntas en `GRUPOS/grupo_XX/retroalimentacion/preguntas_exposicion.md`.

## Ejemplo de uso
```
/generar_preguntas_exposicion
> Grupo: 05
> Documento: GRUPOS/grupo_05/entregables/hito5_final.md
> Número de preguntas: 6
```

## Ejemplo de salida

```markdown
# Preguntas Personalizadas - Grupo 05 (Empresa: Envases del Norte)

| # | Pregunta | Dirigida a | Fase |
|---|---------|-----------|------|
| 1 | En su Project Charter mencionan que el problema afecta la línea 3. Sin embargo, los datos recolectados incluyen datos de la línea 2. ¿Por qué? | María (Responsable datos) | D/M |
| 2 | El Cpk calculado es 0.85. ¿Qué acciones concretas proponen para mejorarlo a 1.33? | Juan | M |
| 3 | Su Ishikawa muestra 12 causas pero solo validaron 2 estadísticamente. ¿Cómo determinaron cuáles validar? | Pedro | A |
| 4 | El costo de implementación estimado es $45,000 pero no incluyen costo de capacitación. ¿Cuánto cambiaría el ROI? | Ana (Responsable costos) | I |
| 5 | Su plan de control solo menciona inspección visual. ¿No sería más efectivo un gráfico de control X-bar/R? | Cualquiera | C |
| 6 | Si la empresa les dijera que solo pueden implementar UNA mejora, ¿cuál elegirían y por qué? | Líder | Integradora |
```
