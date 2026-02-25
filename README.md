# COPEN-built-environment-adiposity
Secondary analysis of the COPEN 2022 survey assesing the relationship between built environment and anthropometry among adults from Bogota, Medellin, Cali, Barranquilla and Bucaramanga 

# Ambiente físico construido y adiposidad en Colombia
## Estudio COPEN 2022 — Análisis multinivel

Este repositorio contiene los códigos del análisis estadístico de la tesis 
de maestría en Epidemiología Clínica de la Pontificia Universidad Javeriana, que evalúa 
la relación entre el ambiente físico construido residencial y el IMC y 
perímetro abdominal en adultos de cinco ciudades colombianas.

## Estructura
- `01_descriptivo.Rmd` — Estadísticas descriptivas de la muestra
- `02_modelo1_BMI_AF.Rmd` — Modelo multinivel IMC ~ AFC actividad física
- `03_modelo2_WC_AF.Rmd` — Modelo multinivel PA ~ AFC actividad física  
- `04_modelo3_BMI_Alim.Rmd` — Modelo multinivel IMC ~ AFC alimentación
- `05_modelo4_WC_Alim.Rmd` — Modelo multinivel PA ~ AFC alimentación
- `06_poder_posthoc.Rmd` — Poder estadístico post hoc (Monte Carlo, B=1000)

## Nota sobre los datos
Los datos del estudio COPEN no se incluyen en este repositorio 
por restricciones de confidencialidad. Los códigos están documentados 
para permitir la replicación con datos equivalentes.

## Paquetes principales
- WeMix (modelos multinivel ponderados)
- tidyverse, lme4, sf

## Contacto
Sebastian Gutierrez — sa_gutierrezr@javeriana.edu.co
