**Sistema de análisis realizado con Python y Yahoo Finance**

**Descripción General**

Este proyecto es una herramienta desarrollada en Python que permite obtener, procesar y visualizar datos financieros en tiempo real o histórico utilizando la API no oficial de Yahoo Finance.
Su objetivo principal es facilitar el análisis básico de acciones mediante la extracción automática de precios y la generación de gráficos estadísticos.

**Objetivos del Proyecto**

Centralizar la información financiera en un solo flujo de trabajo.
Realizar cálculos estadísticos básicos sobre los precios.
Generar gráficos que permitan interpretar la evolución y variabilidad de las acciones.

**Funciones Principales**

1 - Extracción de Datos
Obtiene información de acciones desde Yahoo Finance utilizando la librería yfinance.
Permite consultar una o múltiples empresas mediante sus tickers.
Extrae datos como:
Precio de apertura (Open)
Precio de cierre (Close)
Máximo y mínimo (High / Low)
Volumen transado
Precio ajustado (Adj Close)

2 - Procesamiento y Estadísticas Básicas
El sistema calcula indicadores estadísticos fundamentales, entre ellos:
Media
Mediana
Desviación estándar
Variancia
Rendimiento diario
Rendimiento acumulado

3 - Generación de Gráficos
Utiliza la librería como Matplotlib  para mostrar:
Evolución del precio en el tiempo
Distribución de rendimientos
Comparación entre varias acciones
Volumen transado
Estadísticas visuales básicas (boxplot, histogramas, etc.)

4 - Modularidad
El proyecto está diseñado para ser extensible:
Se pueden agregar nuevos indicadores financieros.
Se pueden incluir modelos predictivos (ARIMA, LSTM, regresiones).
Es posible integrar alertas, dashboards o bases de datos.

5 - Tecnologías Utilizadas
yfinance → para extracción de datos
Python/Pandas → para manipulación de datos
Matplotlib → visualización gráfica
Streamlit → creacion de interfaz web

**Conclusiones**

1 - Este proyecto permitió comprobar que, con Python y librerías como yfinance, es posible acceder fácilmente a datos reales del mercado y analizarlos sin necesidad de herramientas costosas o complejas.

2 - El análisis estadístico aplicado a las acciones ayudó a transformar datos en información útil, permitiendo entender mejor cómo cambian los precios, cómo se comportan las empresas y qué patrones pueden aparecer a lo largo del tiempo.

3 - Los gráficos generados hicieron que la información fuera más clara y visual, facilitando la identificación de tendencias, movimientos bruscos y comportamientos que no se ven a simple vista solo con números.

4 - En conjunto, el proyecto dejó establecida una base muy sólida para continuar creciendo: se pueden agregar indicadores técnicos, comparar múltiples empresas o avanzar hacia modelos predictivos, ampliando las posibilidades de análisis financiero de manera gradual.
