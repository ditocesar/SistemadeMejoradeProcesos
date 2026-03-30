# Presentación: Fase CONTROL (Semanas 12-13)

## Slide 1: Portada
- **Título:** Fase CONTROL - Metodología DMAIC
- **Subtítulo:** Sosteniendo las mejoras en el tiempo
- **Curso:** Mejora de Procesos
- **Semanas:** 12 y 13

---

## Slide 2: Objetivos de Aprendizaje
Al finalizar esta fase, el estudiante será capaz de:
1. Diseñar un plan de control efectivo para el proceso mejorado
2. Seleccionar y construir gráficos de control apropiados
3. Interpretar señales de fuera de control y definir planes de reacción
4. Integrar el documento final del proyecto DMAIC
5. Documentar lecciones aprendidas del proyecto

---

## Slide 3: ¿Por qué CONTROL?

> *"Sin control, las mejoras son temporales"*

```
Mejora SIN control:           Mejora CON control:
   ↑                            ↑
   │  ╱╲                        │         ___________
   │ │  │  ╱╲                   │        │           
   │ │  │ │  ╲                  │   ╱────┘           
   │ │  │ │   ╲  ╱╲            │  │                  
───│─┘──│─┘────╲╱──╲────       ───┘──────────────────
   │                            │
   └──── Vuelve al inicio       └──── Mejora sostenida
```

**Sin plan de control:** Las mejoras se degradan con el tiempo
**Con plan de control:** Las mejoras se mantienen y son visibles

---

## Slide 4: Gráficos de Control - Concepto

**¿Qué son?** Herramientas estadísticas que monitorean la estabilidad del proceso en el tiempo.

**Componentes:**
- **UCL** (Upper Control Limit): Límite superior de control = CL + 3σ
- **CL** (Center Line): Línea central (media del proceso)
- **LCL** (Lower Control Limit): Límite inferior de control = CL - 3σ

```
UCL ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─
         •         •
    •       •           •        •
CL ═══•═══════•═══════════•══════════•════
       •         •   •        •
              •                    •
LCL ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─ ─
```

> ⚠️ **Límites de control ≠ Límites de especificación**
> Los límites de control vienen del PROCESO, las especificaciones vienen del CLIENTE.

---

## Slide 5: Selección del Gráfico de Control

| ¿Qué tipo de dato? | ¿Tamaño de muestra? | Gráfico |
|--------------------|---------------------|---------|
| **Continuo** | n = 1 (individual) | I-MR |
| **Continuo** | n = 2-9 | X̄-R |
| **Continuo** | n ≥ 10 | X̄-S |
| **Discreto** (defectuosos) | n constante | np |
| **Discreto** (defectuosos) | n variable | p |
| **Discreto** (defectos) | Área constante | c |
| **Discreto** (defectos) | Área variable | u |

---

## Slide 6: Señales de Fuera de Control (Western Electric Rules)

| Regla | Patrón | Significado |
|-------|--------|------------|
| **1** | 1 punto fuera de 3σ | Causa especial obvia |
| **2** | 9 puntos del mismo lado de CL | Cambio en la media |
| **3** | 6 puntos en tendencia (ascendente/descendente) | Tendencia/desgaste |
| **4** | 14 puntos alternando arriba/abajo | Sobre-ajuste del proceso |
| **5** | 2 de 3 puntos entre 2σ y 3σ | Aumento de variabilidad |
| **6** | 4 de 5 puntos más allá de 1σ | Cambio pequeño en media |

**Ante señal fuera de control:**
1. 🛑 Detener y evaluar
2. 🔍 Investigar causa especial
3. 🔧 Corregir la causa
4. 📝 Documentar
5. ✅ Verificar que vuelve a control

---

## Slide 7: Plan de Control - Elementos

Un plan de control efectivo incluye:

1. **¿Qué controlar?** → Variables CTQ del proceso mejorado
2. **¿Cómo controlar?** → Gráfico de control, inspección, auditoría
3. **¿Con qué frecuencia?** → Cada hora, cada turno, diario
4. **¿Quién controla?** → Operario, supervisor, calidad
5. **¿Qué hacer si falla?** → Plan de reacción
6. **¿Cómo documentar?** → SOPs, instrucciones de trabajo
7. **¿Cómo capacitar?** → Plan de entrenamiento

---

## Slide 8: Estandarización de Procesos

**Documentos clave:**
| Documento | Propósito | Detalle |
|-----------|----------|---------|
| **SOP** (Standard Operating Procedure) | Paso a paso del proceso | Alto |
| **Instrucción de trabajo** | Tarea específica | Muy alto |
| **Check list** | Verificación rápida | Medio |
| **Ayuda visual** | Referencia rápida en el puesto | Bajo |

**Regla:** Si no está documentado, no es estándar.

---

## Slide 9: Lecciones Aprendidas

**¿Por qué documentar lecciones aprendidas?**
- Evitar repetir errores en futuros proyectos
- Compartir conocimiento con otros equipos
- Mejorar la efectividad de la metodología DMAIC
- Reconocer éxitos y áreas de mejora

**Categorías:**
1. 🏢 **Sobre el proyecto:** Técnicas, herramientas, metodología
2. 👥 **Sobre el equipo:** Comunicación, liderazgo, distribución de trabajo
3. 🤝 **Sobre la empresa:** Acceso a datos, colaboración, compromisos
4. 📊 **Sobre la mejora:** Viabilidad, impacto, sostenibilidad

---

## Slide 10: Integración del Documento Final

### Estructura del Documento Completo

| Sección | Contenido | Páginas aprox. |
|---------|----------|---------------|
| Portada y datos del equipo | | 1 |
| Índice | | 1 |
| Resumen ejecutivo | | 1-2 |
| **1. Define** | Charter, SIPOC, VOC/CTQ | 10-12 |
| **2. Measure** | Mapa proceso, datos, baseline | 10-12 |
| **3. Analyze** | Ishikawa, 5W, hipótesis, FMEA | 10-12 |
| **4. Improve** | Solución, To-Be, plan, costos | 10-12 |
| **5. Control** | Plan de control, gráficos, SOPs | 8-10 |
| **6. Lecciones aprendidas** | Reflexiones por fase | 3-5 |
| Anexos | Datos, evidencias, cálculos | Variable |
| **TOTAL** | | **55-70 páginas** |

---

## Slide 11: Actividades Semanas 12-13

### Semana 12: Diseño del Plan de Control
- Seleccionar gráficos de control apropiados
- Calcular límites de control
- Diseñar plan de reacción
- Documentar procedimientos estandarizados

### Semana 13: Integración Final + EXAMEN FINAL
- Integrar todas las secciones del documento
- Documento de lecciones aprendidas
- Revisión de coherencia entre fases
- Preparación para la exposición
- **EXAMEN FINAL (Hito 5)**

---

## Slide 12: Entregable - Hito 5 / Examen Final
### Documento Word Final Completo: D + M + A + I + C

**Contenido adicional mínimo (Sección Control):**
1. Plan de control completo con todas las variables CTQ
2. Gráficos de control seleccionados con justificación
3. Cálculos de límites de control
4. Plan de reacción ante fuera de control
5. Procedimientos estandarizados (SOPs)
6. Lecciones aprendidas completas
7. Resumen ejecutivo del proyecto

**Formato:** Documento Word final completo, 55-70 páginas
**Fecha de entrega:** Semana 13 (junto con el examen final)
