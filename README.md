# G2S Analytics — Carlos Gino Garibotto Sandoval

Portafolio profesional de análisis cuantitativo aplicado a decisiones de negocio y política pública. Este repositorio contiene proyectos de data analytics, modelos predictivos y sistemas de visualización desarrollados íntegramente en R, con énfasis en reproducibilidad, rigor metodológico y comunicación ejecutiva. Cada proyecto está documentado con su pipeline completo — desde la ingesta de datos hasta el despliegue en producción — y publicado como reporte interactivo en GitHub Pages.

## Sobre el autor

Economista titulado de la Universidad Nacional Mayor de San Marcos con más de 25 años de experiencia en análisis cuantitativo. La trayectoria combina formación económica sólida con dominio técnico en machine learning aplicado: segmentación de clientes con K-Means, modelos de propensión con LightGBM y XGBoost, análisis RFM adaptado al mercado peruano, y series de tiempo con variables rezagadas. El enfoque siempre parte del problema de negocio — no de la herramienta — lo que permite traducir modelos complejos en recomendaciones accionables para equipos comerciales y directivos.

## Proyectos destacados

El trabajo más reciente se centra en el mercado de telecomunicaciones peruano, con dos proyectos construidos sobre el dataset del Datathon Entel 2022. El primero es un modelo de propensión a la convergencia digital (AUC 0.81, Lift 32.8x) desplegado como app Shiny en Docker. El segundo es una segmentación por perfil de consumo digital — integrando 7 fuentes y ~500,000 líneas móviles — que combina clustering K-Means con modelos de conversión por segmento y un sistema RFM adaptado al prepago peruano, con simulador de umbrales publicado en shinyapps.io. Complementan el portafolio análisis electorales territoriales del Perú 2006–2026 y un estudio epidemiológico de rezagos temporales COVID-19 con datos MINSA para 25 departamentos.

## Stack técnico

Todo el trabajo está construido sobre R como lenguaje central: tidyverse y data.table para procesamiento, tidymodels y tidyclust para modelado reproducible, LightGBM vía bonsai para gradient boosting, Shiny y bslib para aplicaciones interactivas, y Quarto para reportes ejecutivos publicados directamente en GitHub Pages. Los despliegues de producción usan Docker con rocker/tidyverse como imagen base y shinyapps.io para acceso público. El repositorio refleja un flujo de trabajo profesional — con control de versiones, pipelines modulares y separación clara entre datos, scripts y outputs — pensado para ser auditable y reproducible por cualquier equipo técnico.
