# Presentación: Fase MEASURE (Semanas 3-5)

## Slide 1: Portada
- **Título:** Fase MEASURE - Metodología DMAIC
- **Subtítulo:** Midiendo el estado actual del proceso
- **Curso:** Mejora de Procesos
- **Semanas:** 3, 4 y 5

---

## Slide 2: Objetivos de Aprendizaje
Al finalizar esta fase, el estudiante será capaz de:
1. Elaborar un mapa de proceso detallado (As-Is)
2. Diseñar e implementar un plan de recolección de datos
3. Calcular e interpretar métricas de capacidad del proceso
4. Realizar análisis estadístico descriptivo
5. Identificar el desempeño actual (baseline) del proceso

---

## Slide 3: ¿Por qué Medir?
> *"Si no puedes medirlo, no puedes mejorarlo"* — Lord Kelvin

**La medición nos permite:**
- 📊 Conocer el estado actual (baseline)
- 🎯 Establecer objetivos realistas
- ✅ Verificar mejoras después de implementar cambios
- 📈 Tomar decisiones basadas en datos, no en opiniones

---

## Slide 4: Mapeo de Procesos
**Tipos de mapas:**
1. **Diagrama de flujo básico** → Secuencia de pasos
2. **Diagrama de carril (Swimlane)** → Responsabilidades por área
3. **Value Stream Mapping (VSM)** → Flujo de valor con tiempos
4. **SIPOC** → Vista de alto nivel (ya elaborado en Define)

**Análisis de valor:**
- **VA (Valor Agregado):** Transforma el producto/servicio para el cliente
- **NVA (No Valor Agregado):** No transforma, es desperdicio
- **BNVA (Business NVA):** Necesario pero no agrega valor al cliente

---

## Slide 5: Plan de Recolección de Datos

| Pregunta | Respuesta |
|----------|----------|
| **¿Qué** medir? | Variables del CTQ |
| **¿Cómo** medir? | Instrumento/método |
| **¿Cuándo** medir? | Frecuencia |
| **¿Cuántos** datos? | Tamaño de muestra |
| **¿Quién** mide? | Responsable |
| **¿Dónde** registrar? | Hoja de verificación |

---

## Slide 6: Tipos de Datos

| Tipo | Subtipos | Ejemplos | Gráficos |
|------|---------|----------|----------|
| **Continuos** | Tiempo, peso, temperatura, longitud | Tiempo de ciclo: 15.3 min | Histograma, Box Plot |
| **Discretos** | Conteos, proporciones, categorías | Defectos: 3, Tipo: A/B/C | Pareto, Gráfico de barras |

> **Regla:** Los datos continuos dan más información con menos datos que los discretos.

---

## Slide 7: Estadística Descriptiva

### Medidas de Tendencia Central
- **Media (X̄):** Promedio aritmético
- **Mediana:** Valor central
- **Moda:** Valor más frecuente

### Medidas de Dispersión
- **Rango:** Max - Min
- **Desviación estándar (σ/s):** Dispersión respecto a la media
- **Coeficiente de variación (CV):** s/X̄ × 100%

---

## Slide 8: Herramientas Gráficas

| Herramienta | Uso Principal |
|------------|--------------|
| **Histograma** | Distribución de datos, forma, extensión |
| **Diagrama de Pareto** | Identificar los "pocos vitales" (regla 80/20) |
| **Box Plot** | Comparar distribuciones, detectar outliers |
| **Run Chart** | Tendencias y patrones en el tiempo |
| **Dot Plot** | Distribución con pocos datos |
| **Scatter Plot** | Relación entre dos variables |

---

## Slide 9: Capacidad del Proceso

**¿Qué es?** La habilidad del proceso para cumplir con las especificaciones del cliente.

```
         LSL                 USL
          |                   |
     _____|___________._______|_____
    /     |          /|\      |     \
   /      |         / | \     |      \
  /       |        /  |  \    |       \
 /________|_______/___|___\___|________\
                   X̄
          
          |←── 6σ del proceso ──→|
          |←── Rango de especificación ──→|
```

**Cp = (USL - LSL) / 6σ** → ¿El proceso cabe en la especificación?
**Cpk = min[(USL-X̄)/3σ, (X̄-LSL)/3σ]** → ¿El proceso está centrado?

---

## Slide 10: Interpretación de Cp y Cpk

| Escenario | Cp | Cpk | Significado |
|-----------|---|-----|------------|
| Capaz y centrado | Alto | Alto | ✅ Proceso ideal |
| Capaz pero descentrado | Alto | Bajo | ⚠️ Centrar el proceso |
| Incapaz | Bajo | Bajo | ❌ Reducir variabilidad |

**Valores objetivo:**
- Cp ≥ 1.33 → Proceso capaz
- Cpk ≥ 1.33 → Proceso capaz y centrado
- Cp ≥ 2.0 → Clase mundial (Six Sigma)

---

## Slide 11: DPMO y Nivel Sigma

| Nivel Sigma | DPMO | Yield | Cp |
|------------|------|-------|----|
| 1σ | 691,462 | 30.85% | 0.33 |
| 2σ | 308,538 | 69.15% | 0.67 |
| 3σ | 66,807 | 93.32% | 1.00 |
| 4σ | 6,210 | 99.38% | 1.33 |
| 5σ | 233 | 99.977% | 1.67 |
| 6σ | 3.4 | 99.9997% | 2.00 |

**Fórmulas:**
- DPU = Defectos / Unidades inspeccionadas
- DPO = Defectos / (Unidades × Oportunidades)
- DPMO = DPO × 1,000,000

---

## Slide 12: Actividades Semanas 3-5

### Semana 3: Mapeo y Plan de Datos
- Elaborar mapa de proceso detallado (As-Is)
- Identificar y clasificar actividades (VA/NVA/BNVA)
- Diseñar plan de recolección de datos
- Crear hojas de verificación

### Semana 4: Métricas y Capacidad
- Recolectar datos según el plan
- Calcular métricas clave (Cp, Cpk, DPMO)
- Preparar entregable Hito 2

### Semana 5: Análisis Estadístico
- Análisis estadístico descriptivo completo
- Crear gráficos (histograma, Pareto, box plot)
- Identificar patrones y tendencias
- Documentar baseline del proceso

---

## Slide 13: Entregable - Hito 2
### Documento Word: Fase MEASURE (acumulativo con DEFINE)

**Contenido adicional mínimo:**
1. Mapa de proceso detallado (As-Is)
2. Plan de recolección de datos
3. Base de datos recolectada
4. Estadísticas descriptivas y gráficos
5. Análisis de capacidad del proceso (si aplica)
6. Baseline del proceso documentado
7. Conclusiones de la fase Measure

**Formato:** Documento Word acumulativo, sección Measure 10-15 páginas
**Fecha de entrega:** Fin de semana 4
