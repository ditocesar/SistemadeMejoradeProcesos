# Presentación: Fase ANALYZE (Semanas 6-8)

## Slide 1: Portada
- **Título:** Fase ANALYZE - Metodología DMAIC
- **Subtítulo:** Descubriendo las causas raíz del problema
- **Curso:** Mejora de Procesos
- **Semanas:** 6, 7 y 8

---

## Slide 2: Objetivos de Aprendizaje
Al finalizar esta fase, el estudiante será capaz de:
1. Aplicar herramientas de análisis de causa raíz (Ishikawa, 5 Porqués)
2. Realizar pruebas de hipótesis para validar causas
3. Aplicar análisis de correlación y regresión
4. Elaborar un FMEA del proceso
5. Priorizar y validar causas raíz con evidencia estadística

---

## Slide 3: ¿Qué hacemos en Analyze?
**Pregunta clave:** ¿Cuáles son las verdaderas causas raíz del problema?

```
Fase Measure → DATOS del estado actual
     ↓
Fase Analyze → CAUSAS RAÍZ validadas
     ↓
Fase Improve → SOLUCIONES basadas en causas
```

**Regla de oro:** No proponer soluciones hasta tener causas raíz validadas.

---

## Slide 4: Diagrama de Ishikawa (Causa-Efecto)
**Las 6M:**
1. 👷 **Mano de obra** → Personas, habilidades, capacitación
2. 📋 **Métodos** → Procedimientos, instrucciones, estándares
3. ⚙️ **Maquinaria** → Equipos, tecnología, herramientas
4. 📦 **Materiales** → Insumos, proveedores, calidad
5. 🌍 **Medio ambiente** → Entorno, clima, espacio
6. 📏 **Medición** → Instrumentos, sistemas de medición

**Pasos:**
1. Definir el efecto (problema) claramente
2. Brainstorming de causas por cada M
3. Profundizar en sub-causas
4. Priorizar las causas más probables

---

## Slide 5: Técnica de los 5 Porqués

**Concepto:** Preguntar "¿Por qué?" repetidamente hasta llegar a la causa raíz.

**Ejemplo:**
| Nivel | Pregunta y Respuesta |
|-------|---------------------|
| **Problema** | Las piezas tienen rebaba |
| **¿Por qué 1?** | El molde no cierra completamente |
| **¿Por qué 2?** | Hay desgaste en las guías del molde |
| **¿Por qué 3?** | No se ha hecho mantenimiento preventivo |
| **¿Por qué 4?** | No existe un programa de mantenimiento |
| **¿Por qué 5?** | Nunca se estableció uno → **CAUSA RAÍZ** |

> **Cuidado:** No siempre son exactamente 5 porqués. Puede ser 3 o puede ser 7.

---

## Slide 6: ¿Causa Raíz o Síntoma?

| Síntoma ❌ | Causa Raíz ✅ |
|-----------|--------------|
| "Los operarios cometen errores" | "No existe procedimiento estandarizado documentado" |
| "La máquina se detiene" | "El sensor de temperatura está descalibrado" |
| "Los clientes se quejan" | "El tiempo de entrega excede el compromiso porque el proceso de empaque tiene 3 cuellos de botella" |

**Criterios de una verdadera causa raíz:**
- Es específica y controlable
- Si se elimina, el problema desaparece
- Tiene evidencia que la soporta
- No se puede descomponer más

---

## Slide 7: Pruebas de Hipótesis

**¿Para qué?** Validar estadísticamente que una causa sospechada realmente afecta al proceso.

**Proceso:**
1. Formular H₀ (no hay efecto) y H₁ (sí hay efecto)
2. Seleccionar nivel de significancia (α = 0.05)
3. Seleccionar la prueba apropiada
4. Calcular estadístico y p-valor
5. Tomar decisión

**Decisión:**
- Si **p-valor < α** → Rechazar H₀ → La causa ES significativa
- Si **p-valor ≥ α** → No rechazar H₀ → No hay evidencia suficiente

---

## Slide 8: Selección de Prueba Estadística

```
¿Qué quiero comparar?
├── Medias
│   ├── 1 muestra vs. valor → t-test 1 muestra
│   ├── 2 muestras independientes → t-test 2 muestras
│   ├── 2 muestras pareadas → t-test pareado
│   └── ≥3 muestras → ANOVA
├── Proporciones
│   ├── 1 proporción vs. valor → Prueba Z
│   └── 2+ proporciones → Chi-cuadrado
└── Relación entre variables
    ├── Continua vs. continua → Correlación/Regresión
    └── Categórica vs. categórica → Chi-cuadrado
```

---

## Slide 9: Correlación y Regresión

**Correlación:** ¿Existe relación entre dos variables?
- **r** va de -1 a +1
- |r| > 0.7 → Correlación fuerte
- |r| 0.4-0.7 → Correlación moderada
- |r| < 0.4 → Correlación débil

**Regresión:** ¿Cómo puedo predecir Y a partir de X?
- Y = β₀ + β₁X + ε
- R² → % de variación explicada por el modelo
- p-valor de los coeficientes → ¿Son significativos?

> ⚠️ **Correlación ≠ Causalidad.** La evidencia estadística se complementa con conocimiento del proceso.

---

## Slide 10: FMEA (Análisis de Modo y Efecto de Falla)

**¿Qué es?** Método sistemático para identificar riesgos en el proceso.

**Componentes:**
- **Modo de falla:** ¿Qué puede fallar?
- **Efecto:** ¿Qué impacto tiene?
- **Severidad (S):** ¿Qué tan grave es? (1-10)
- **Ocurrencia (O):** ¿Con qué frecuencia? (1-10)
- **Detectabilidad (D):** ¿Se puede prevenir? (1-10)
- **RPN = S × O × D** → Número de Prioridad de Riesgo

**Priorización:**
- RPN > 200 → Acción inmediata
- RPN 100-200 → Acción cuando sea posible
- RPN < 100 → Monitorear

---

## Slide 11: Actividades Semanas 6-8

### Semana 6: Análisis de Causa Raíz
- Elaborar Diagrama de Ishikawa con el equipo
- Aplicar 5 Porqués a las causas principales
- Priorizar causas potenciales

### Semana 7: Validación Estadística + EXAMEN PARCIAL
- Realizar pruebas de hipótesis para validar causas
- Análisis de correlación si aplica
- **EXAMEN PARCIAL (Hito 3)**

### Semana 8: FMEA y Síntesis
- Elaborar FMEA del proceso
- Consolidar causas raíz validadas
- Documentar hallazgos con evidencia

---

## Slide 12: Entregable - Hito 3 / Examen Parcial
### Documento Word Acumulativo: D + M + A

**Contenido adicional mínimo (Sección Analyze):**
1. Diagrama de Ishikawa completo
2. Análisis de 5 Porqués (mínimo 3 causas investigadas)
3. Pruebas estadísticas realizadas con resultados
4. FMEA del proceso (mínimo 5 modos de falla)
5. Resumen de causas raíz validadas con evidencia
6. Conclusiones de la fase Analyze

**Formato:** Documento Word acumulativo, sección Analyze 12-15 páginas
**Fecha de entrega:** Semana 7 (junto con el examen parcial)
