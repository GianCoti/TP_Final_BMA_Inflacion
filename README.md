
# TP Final - Análisis Financiero: Inflación vs Banco Macro (BMA)

Este trabajo práctico analiza la relación entre la inflación mensual y trimestral en Argentina y el rendimiento bursátil de Banco Macro (BMA) entre enero de 2020 y diciembre de 2024.

## Archivos incluidos

- Inflación mensual vs variación mensual de BMA
- Inflación acumulada vs rendimiento BMA por trimestre
- Volumen operado vs rendimiento BMA
- Dashboard interactivo

## Metodología

- Se descargaron datos ajustados de BMA desde Yahoo Finance utilizando yfinance.
- Se cargó inflación mensual desde un archivo CSV oficial.
- Se realizaron cruces mensuales y trimestrales entre inflación y precios de BMA.
- Se calcularon variaciones porcentuales y rendimientos reales.
- Se generaron visualizaciones comparativas y un dashboard interactivo con plotly.

## Conclusiones

Durante el período analizado, Banco Macro (BMA) mostró rendimientos mixtos frente a la inflación. En varios trimestres, el rendimiento bursátil fue negativo o insuficiente para cubrir la inflación acumulada, lo que indica una pérdida de poder adquisitivo para los inversores. Solo en algunos períodos puntuales (como 2023-06 y 2024-03) BMA logró superar la inflación, pero sin consistencia sostenida.

Este análisis evidencia que, en contextos de alta inflación como el argentino, invertir en acciones individuales como BMA no garantiza cobertura real. Se recomienda complementar con instrumentos indexados o estrategias de cobertura más robustas.

## Herramientas utilizadas

- Python: pandas, numpy, matplotlib, plotly
- Supabase: almacenamiento de datos
- GitHub: repositorio y entrega
- Google Colab: entorno de desarrollo

## Autor

Gabriel — Estudiante de Ciencia de Datos, Auditor IT SOX en telecomunicaciones, apasionado por el análisis estratégico y la cultura argentina.
