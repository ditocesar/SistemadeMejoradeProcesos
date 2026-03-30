# Plantilla: Gráficos de Control

## Información
| Campo | Valor |
|-------|-------|
| **Variable monitoreada** | |
| **Tipo de dato** | Continuo / Discreto |
| **Tamaño de subgrupo (n)** | |
| **Número de subgrupos** | |

## Selección del Gráfico de Control

```
¿Tipo de dato?
├── CONTINUO
│   ├── Subgrupo n < 10 → X-bar / R
│   ├── Subgrupo n ≥ 10 → X-bar / S
│   └── n = 1 (individuales) → I-MR
└── DISCRETO
    ├── Defectuosos (pasa/no pasa)
    │   ├── n constante → np
    │   └── n variable → p
    └── Defectos (conteo)
        ├── Área constante → c
        └── Área variable → u
```

## Tabla de Datos

| Subgrupo | Medición 1 | Medición 2 | ... | Medición n | X̄ (Media) | R (Rango) o S (Desv.) |
|----------|-----------|-----------|-----|-----------|-----------|----------------------|
| 1 | | | | | | |
| 2 | | | | | | |
| 3 | | | | | | |
| ... | | | | | | |

## Cálculo de Límites de Control

### Para Gráfico X-bar / R:
| Línea | Fórmula | Valor |
|-------|---------|-------|
| UCL (X-bar) | X̿ + A₂R̄ | |
| CL (X-bar) | X̿ | |
| LCL (X-bar) | X̿ - A₂R̄ | |
| UCL (R) | D₄R̄ | |
| CL (R) | R̄ | |
| LCL (R) | D₃R̄ | |

### Constantes (tabla de factores)
| n | A₂ | D₃ | D₄ |
|---|----|----|-----|
| 2 | 1.880 | 0 | 3.267 |
| 3 | 1.023 | 0 | 2.575 |
| 4 | 0.729 | 0 | 2.282 |
| 5 | 0.577 | 0 | 2.115 |

## Interpretación de Señales Fuera de Control

| Regla | Descripción | ¿Se detectó? |
|-------|------------|-------------|
| **Regla 1** | Un punto fuera de los límites 3σ | Sí / No |
| **Regla 2** | 9 puntos consecutivos del mismo lado de la línea central | Sí / No |
| **Regla 3** | 6 puntos consecutivos ascendentes o descendentes | Sí / No |
| **Regla 4** | 14 puntos consecutivos alternando arriba y abajo | Sí / No |

## Conclusiones

> ¿El proceso está bajo control estadístico? ¿Qué acciones se recomiendan?

_Escribir aquí..._
