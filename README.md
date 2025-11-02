# Analyse-et-Optimisation-de-Portfeuilles-d-Investissement-par-Facteurs
Répliquer les résultats de Dichtl et al. (2021) en construisant six facteurs (MKT, VAL, CAP, MOM, QUA, VOL) à partir des indices MSCI USA, puis en optimisant des portfeuilles via six stratégies d’allocation. Évaluation des performances hors échantillon avec des métriques financières et visualisation des résultats.

# Inversiones Tarea 3: Análisis de Factores y Estrategias de Portafolio

## Descripción del Proyecto
Este repositorio contiene el análisis y los resultados de la Tarea 3 del curso de Inversiones. El proyecto se centra en la construcción de factores de inversión, el análisis descriptivo de estos factores, y la comparación de diferentes estrategias de portafolio.

## Autores
- **Julien Duval**
- **Camille Auvity**
- **Hadrien Bregou**

## Estructura del Proyecto

### Parte 1: Construcción de Factores y Análisis Descriptivo
- **Factores Construidos:** MKT, VAL, CAP, MOM, QUA, VOL
- **Análisis Estadístico:** Media, desviación estándar, asimetría, y curtosis de cada factor.
- **Matriz de Correlación:** Correlaciones de Pearson entre los factores.
- **Gráficos:** Rentabilidad acumulada de los factores.

### Parte 2: Comparación de Estrategias de Portafolio
- **Estrategias Analizadas:**
  - Portafolio Equal Weight (EW)
  - Portafolio de Mínima Varianza (MinVar)
  - Portafolio Mean-Variance (MV)
  - Portafolio Black-Litterman (BL)
  - Portafolio Volatility Timing (VT)
  - Portafolio Reward-to-Risk Timing (RRT)

### Parte 3: Análisis de Estrategias
- **Métricas de Rendimiento:**
  - Ratio de Sharpe
  - Downside Risk
  - Ratio de Sortino
  - Maximum Drawdown (MDD)
  - MPPM (Manipulation-Proof Performance Measure)
- **Gráficos:** Retornos acumulados y ponderaciones de los portafolios.

## Resultados Destacados
- **Factores:** El factor MKT mostró la mayor volatilidad y eventos extremos, mientras que QUA y VOL fueron más estables.
- **Estrategias:** MinVar y VT destacaron por su bajo riesgo y estabilidad, mientras que MV y RRT mostraron mayor volatilidad en busca de rendimientos más altos.

## Requisitos
- Python 3.8 o superior
- Librerías: pandas, numpy, matplotlib, seaborn

## Uso
1. Clona este repositorio.
2. Asegúrate de tener instaladas las librerías necesarias.
3. Ejecuta los scripts de Python para replicar los análisis y gráficos.
