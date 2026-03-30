# 📊 Sistema de Mejora de Procesos - Metodología DMAIC

## Descripción del Curso

Curso de **14 semanas** enfocado en la aplicación práctica de la metodología **DMAIC** (Define, Measure, Analyze, Improve, Control) para la mejora de procesos en empresas reales.

- **Grupos:** 16 equipos de estudiantes
- **Modalidad:** Proyecto de aplicación en empresa real
- **Alcance:** Propuesta de mejora (sin llegar a implementación)
- **Evaluación:** 6 hitos de evaluación + exposición final

---

## 🗺️ Mapa del Curso

| Semanas | Fase DMAIC | Hito de Evaluación |
|---------|-----------|-------------------|
| 1-2 | **DEFINE** | Hito 1 (Sem 2) |
| 3-5 | **MEASURE** | Hito 2 (Sem 4) |
| 6-8 | **ANALYZE** | Hito 3 / Examen Parcial (Sem 7) |
| 9-11 | **IMPROVE** | Hito 4 (Sem 10) |
| 12-13 | **CONTROL** | Hito 5 / Examen Final (Sem 13) |
| 14 | **EXPOSICIÓN** | Hito 6 / Exposición Final (Sem 14) |

---

## 📁 Estructura de Carpetas

```
SMP_OFJ/
├── 00_SILABO/           → Sílabo completo del curso
├── 01_DEFINE/           → Plantillas, presentaciones y evaluaciones de fase Define
├── 02_MEASURE/          → Plantillas, presentaciones y evaluaciones de fase Measure
├── 03_ANALYZE/          → Plantillas, presentaciones y evaluaciones de fase Analyze
├── 04_IMPROVE/          → Plantillas, presentaciones y evaluaciones de fase Improve
├── 05_CONTROL/          → Plantillas, presentaciones y evaluaciones de fase Control
├── 06_EXPOSICION_FINAL/ → Rúbrica, preguntas y evaluación de exposición
├── GRUPOS/              → Carpetas individuales por grupo (01-16)
│   └── grupo_XX/        → Entregables y retroalimentación por grupo
└── _agents/workflows/   → Skills de automatización
```

---

## 🤖 Workflows Disponibles

| Comando | Descripción |
|---------|-------------|
| `/generar_examen` | Genera examen por hito/fase DMAIC |
| `/generar_presentacion` | Genera presentación según fase del sílabo |
| `/generar_preguntas_exposicion` | Genera preguntas para exposición final |
| `/evaluar_entregable` | Evalúa entregable de un grupo contra rúbrica |
| `/generar_retroalimentacion` | Genera retroalimentación detallada por grupo |

---

## 📋 Instrucciones de Uso

1. **Revisar el sílabo** en `00_SILABO/` para el plan semana a semana
2. **Usar las plantillas** de cada fase DMAIC para guiar a los estudiantes
3. **Aplicar los exámenes** de `evaluaciones/` en cada hito
4. **Usar los workflows** para automatizar la generación de contenido
5. **Registrar entregables** de cada grupo en `GRUPOS/grupo_XX/entregables/`
6. **Generar retroalimentación** usando el workflow correspondiente
