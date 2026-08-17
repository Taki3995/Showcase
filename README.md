# 🚀 Data Science & Operations Research Showcase

Bienvenido/a a mi portafolio principal. Este repositorio funciona como un índice curado de mis proyectos más significativos, donde combino **Ciencia de Datos, Deep Learning, Optimización Matemática e Ingeniería de Datos** para resolver problemas complejos y automatizar decisiones operativas.

Selecciona cualquiera de los proyectos a continuación para explorar el código fuente, la arquitectura y los resultados obtenidos.

## 📑 Índice de Contenidos
* [🌐 Arquitectura de Sistemas & Desarrollo Full-Stack](#-arquitectura-de-sistemas--desarrollo-full-stack)
* [🧠 Deep Learning & Natural Language Processing](#-deep-learning--natural-language-processing)
* [📊 Machine Learning & Análisis Predictivo](#-machine-learning--análisis-predictivo)
* [📡 Procesamiento de Señales (DSP) & Detección de Anomalías](#-procesamiento-de-señales-dsp--detección-de-anomalías)
* [⚙️ Investigación de Operaciones & Optimización](#️-investigación-de-operaciones--optimización)
* [🛠️ Data Engineering & Automatización Operativa](#️-data-engineering--automatización-operativa-experiencia-industrial)

---

## 🌐 Arquitectura de Sistemas & Desarrollo Full-Stack

### 1. [DalliaOS: Infraestructura de Self-Hosting Automatizada](https://github.com/Akari-AI)
Plataforma y ecosistema de autohospedaje diseñado para democratizar la privacidad digital, eliminando la barrera técnica del despliegue de servidores para usuarios comunes.
*   **Problema a Resolver:** La extrema complejidad técnica (redes, puertos, SSL) y los riesgos de seguridad que obligan a la población a depender exclusivamente de nubes corporativas centralizadas, perdiendo el control de sus datos.
*   **Enfoque Arquitectónico:** Desarrollo de una arquitectura robusta y automatizada que orquesta contenedores en segundo plano. Implementación de proxy inverso dinámico (Traefik) y gestión de tareas asíncronas de alto rendimiento.
*   **Seguridad y Auditoría:** Integración de hardware de seguridad (Go-TPM), autenticación *passwordless* (WebAuthn), y telemetría avanzada para monitoreo de infraestructura.
*   **Stack Backend & DevOps:** `Go (Golang)` `Docker` `Traefik` `PostgreSQL` `Prometheus` `Github Actions`
*   **Stack Frontend & Auth:** `React` `TypeScript` `Tailwind` `WebAuthn` `TPM`

---

## 🧠 Deep Learning & Natural Language Processing

### 2. [Detección de Melanoma mediante Deep Learning](https://github.com/Taki3995/Melanoma_Detection.git)
Clasificador binario de imágenes médicas para la detección temprana de melanoma.
*   **Enfoque Técnico:** Implementación de arquitectura ResNet18 adaptada para visión computacional médica.
*   **Optimizaciones:** Uso de Optuna para la búsqueda y ajuste de hiperparámetros, combinado con técnicas robustas de Data Augmentation para mejorar la generalización del modelo.
*   **Stack:** `Python` `PyTorch` `ResNet` `Computer Vision` `Optuna`

### 3. [Análisis de Sentimiento con Arquitectura Transformer](https://github.com/Taki3995/Sentiment-Analysis.git)
Desarrollo desde cero de un modelo basado en Transformers para la clasificación de polaridad en reseñas de cine (Dataset IMDB).
*   **Enfoque Técnico:** Construcción modular de componentes core de procesamiento de lenguaje natural.
*   **Optimizaciones:** Implementación propia de un Tokenizador BPE (Byte-Pair Encoding) y Mecanismos de Atención Multi-Cabezal.
*   **Stack:** `Python` `PyTorch` `NLP` `Transformers`

---

## 📊 Machine Learning & Análisis Predictivo

### 4. [Predictor de Quiebra Financiera Corporativa](https://github.com/Taki3995/bankruptcy-probability-factor-detector.git)
Modelo probabilístico diseñado para predecir la quiebra de empresas utilizando ratios y métricas financieras históricas.
*   **Enfoque Técnico:** Análisis comparativo exhaustivo entre Regresión Logística (Máxima Verosimilitud) y modelos regularizados (Ridge - L2).
*   **Optimizaciones:** Manejo avanzado de desbalance de clases extremo mediante la técnica SMOTE.
*   **Stack:** `Python` `Scikit-learn` `Estadística Clásica` `SMOTE`

---

## 📡 Procesamiento de Señales (DSP) & Detección de Anomalías

### 5. [Detección de Anomalías Industriales (CWRU Bearing Anomaly)](https://github.com/Taki3995/cwru-bearing-fault-diagnosis.git)
Sistema automatizado para el diagnóstico y detección de fallos en rodamientos utilizando técnicas avanzadas de Procesamiento Digital de Señales (DSP), sin depender de modelos de Machine Learning (caja negra).
*   **Enfoque Técnico:** Procesamiento de señales de vibración mediante implementación nativa de Filtros de Sub-banda Iterativos de Fourier y Transformadas de Hilbert para el análisis de la envolvente de amplitud. 
*   **Optimizaciones:** Aislamiento de transitorios de impacto mecánico del ruido electromagnético y rotacional minimizando la Entropía Espectral de Shannon. Detección de anomalías evaluando el Top 12 de picos de energía contra la cinemática teórica del rodamiento (BPFI, BPFO, BSF) bajo estrictos márgenes de tolerancia.
*   **Stack:** `Python` `NumPy` `SciPy` `DSP` `Data Analysis`

---

## ⚙️ Investigación de Operaciones & Optimización

### 6. [Optimización Híbrida para Facility Location (CFLP)](https://github.com/Taki3995/Single-Multi-Source-CFLP.git)
Solución matemática avanzada para el Problema de Localización de Instalaciones con Capacidades (Capacitated Facility Location Problem).
*   **Enfoque Técnico:** Diseño de un algoritmo híbrido que minimiza los costos conjuntos de transporte y apertura de instalaciones.
*   **Optimizaciones:** Integración de una Metaheurística Tabú con un Modelo Exacto para alcanzar convergencia rápida y óptimos globales.
*   **Stack:** `AMPL` `Python` `Heurísticas` `Investigación de Operaciones`

---

## 🛠️ Data Engineering & Automatización Operativa (Experiencia Industrial)
*Proyectos desarrollados y desplegados para la optimización de procesos en sala de control (Gasvalpo).*

### 7. [Pipeline ETL: Automatización PCS](https://github.com/Taki3995/Automatizacion-PCS.git)
Sistema de extracción, transformación y carga para automatizar el reporte crítico de Poder Calorífico Superior.
*   **Impacto Operativo:** Reducción del tiempo de procesamiento de reportes de 1 hora a menos de 3 minutos.
*   **Enfoque Técnico:** Extracción automática de datos vía servidores IMAP, parsing de PDFs y Web Scraping. Implementación de lógicas de imputación ("promedio inteligente") para cubrir vacíos de datos durante mantenimientos de sensores.
*   **Stack:** `Python` `BeautifulSoup` `pdfplumber` `ETL Pipeline`

### 8. Sistema Integral de Camiones GNL: [Extractor](https://github.com/Taki3995/Extractor_Camiones.git) & [Automatización](https://github.com/Taki3995/Automatizacion_Camiones.git)
Plataforma de monitoreo y proyección de niveles de inventario en estanques satélites de Gas Natural Licuado (GNL).
*   **Impacto Operativo:** Mejora en la gestión de contingencias de carga y visibilidad logística.
*   **Enfoque Técnico:** Implementación de modelos heurísticos basados en datos de consumo histórico (comparativas D vs D-365) para proyectar demanda. 
*   **Optimizaciones:** Orquestación de datos y desarrollo de dashboard interactivo para el equipo de despacho.
*   **Stack:** `Python` `Tkinter` `Power BI` `Heurísticas de Negocio`

---
> 💡 *Para ver implementaciones de escala académica, scripts universitarios y laboratorios de experimentación, visita mi repositorio [academic-archive](https://github.com/Taki3995/Academic-Archive-and-Applied-Research.git).*
