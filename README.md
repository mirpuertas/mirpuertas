# ¡Hola! Soy Miguel Puertas

**Programador – Científico de Datos**

Estudiante avanzado de Ciencia de Datos (UNSAM)

Intereses: estadística bayesiana • análisis espacial • inferencia causal • simulación estadística

## Tecnologías y herramientas

**Lenguajes:**
Python • R • Java • SQL

**Modelado y estadística:**
PyMC (incl. NUTPIE – sampler Rust) • ArviZ • SciPy • Statsmodels • Scikit-learn • NumPy • Pandas

**Backend y APIs:**
FastAPI • SQLAlchemy • Alembic • Supabase (PostgreSQL) • Docker • Render • Postman

**Aplicaciones y producto:**
Flutter • Dart • SQLite (mobile) • UX orientado a producto

**Datos geoespaciales:**
GeoPandas • Rasterio • QGIS • Sentinel-2

**Computación y DevOps:**
Git • Docker • CI/CD básico • Entornos virtuales • Gestión de dependencias

**Documentación científica:**
$\LaTeX$ • Jupyter/Colab • Reportes reproducibles

## Sobre mí

Soy programador y científico de datos en formación, con experiencia previa en soporte técnico, mantenimiento de hardware y enseñanza de lenguas extranjeras. Actualmente curso la **Licenciatura en Ciencia de Datos en la Universidad Nacional de San Martín**, donde me especializo en estadística aplicada, inferencia bayesiana y causal, análisis espacial y desarrollo backend transaccional.

Me interesa desarrollar soluciones analíticas para problemas reales, integrando modelado estadístico, programación y visualización interpretable, con un enfoque en reproducibilidad y buenas prácticas de ingeniería de software, especialmente en contextos donde el rigor estadístico, la ingeniería de software y el diseño de producto se integran en soluciones reales y sostenibles.

Trabajo principalmente con Python, R, SQL y QGIS, y tengo experiencia en proyectos de:

- Inferencia bayesiana y causal (modelos jerárquicos, mixtos, mixtures, evidencia marginal, NUTPIE)
- Modelos multitemporales y simulación (armónicas temporales, Monte Carlo, TrueSkill Through Time + Kelly)
- Análisis geoespacial y sensores remotos (NDVI/NBR/NDMI, ΔNBR, multitemporal, Sentinel-2, accesibilidad urbana)
- Desarrollo backend transaccional (FastAPI + SQLAlchemy + Alembic + Supabase + Docker)
- Aplicaciones interactivas (Streamlit, visualizaciones geográficas y estadísticas)

## Proyectos destacados

| Proyecto | Descripción | Tecnologías |
|---|---|---|
| [📱 Mediary – Diario de salud offline](https://github.com/mirpuertas/mediary) | Aplicación mobile *privacy-first* para registrar sueño, ánimo y medicación. Funciona completamente offline, sin cuentas ni nube, con recordatorios locales, flujo rápido desde notificaciones y exportación de datos (CSV/PDF/XLSX). Proyecto personal enfocado en diseño de producto, UX y buenas prácticas de ingeniería. | Flutter, Dart, SQLite, Provider |
| [🚲 Modelado bayesiano de la demanda de bicicletas en Seúl](https://github.com/mirpuertas/bayesian-bike-sharing) | Extensión bayesiana del análisis previo, utilizando un GLM Binomial Negativo con armónicas temporales, polinomio cúbico para la temperatura y muestreo eficiente mediante NUTPIE (sampler en Rust). Incluye comparación de modelos vía LOO, diagnóstico MCMC y análisis del patrón horario y estacional. Proyecto académico (Trabajo final – Estadística e Inferencia II, UNSAM). | Python, PyMC, NUTPIE, ArviZ, Statsmodels |
| [📈 Simulador de apuestas con Kelly + TTT](https://github.com/mirpuertas/simulador-apuestas-kelly-trueskill) | Estrategias de apuesta basadas en predicciones de habilidad generadas con TrueSkill Through Time (TTT). Simulación de resultados usando el criterio de Kelly, con una versión online en Streamlit y una interfaz local en Tkinter. Proyecto académico (Trabajo final – Inferencia Bayesiana Causal, UNSAM). | Python, Julia, Streamlit, Tkinter |
| [🧪 Evaluación de CalCause – ACIC 2016](https://github.com/mirpuertas/calcause-acic2016) | Ensamble causal (RF + GP) para estimar el efecto del tratamiento (SATT) en datos simulados. Participación tipo competencia con validación cruzada y bootstrap. Proyecto académico (Trabajo final – Inferencia Bayesiana Causal, UNSAM). | Python, Scikit-learn, SciPy, joblib |
| [🌋 Efectos de la erupción en La Palma – QGIS](https://github.com/mirpuertas/La-Palma-erupcion) | Análisis multitemporal con Sentinel-2 para detectar zonas afectadas por la erupción del volcán Cumbre Vieja (2021). Incluye mapas RGB, análisis NDMI en la costa, y ΔNBR para estimar severidad de cambio. Proyecto académico (Análisis de Datos Espaciales – UNSAM). | QGIS, Sentinel-2, OpenStreetMap |
| [🚲 Predicción de la demanda de bicicletas en Seúl](https://github.com/mirpuertas/seoul-bike-demand) | Modelado de la demanda de bicicletas públicas en función de variables climáticas y horarias, con codificación cíclica, regresión cúbica y Lasso. Proyecto académico (Trabajo final – Intro al Aprendizaje Automático, UNSAM). | Python, Pandas, scikit-learn |
| [🧊 Cubo OLAP en Java](https://github.com/mirpuertas/cubo-olap) | Implementación desde cero de un cubo OLAP modular con medidas agregadas y carga desde CSV. Proyecto académico (Trabajo final – Algoritmos I, UNSAM). | Java |
| [🧑‍💻 Generador automático de usuarios](https://github.com/mirpuertas/user_generator) | Crea nombres de usuario y asigna una VM ficticia a partir de nombre, apellido y área. Permite crear, buscar o eliminar usuarios en una tabla SQLite simulada. | Python, SQLite |

### En desarrollo / cierre académico

| Proyecto | Descripción | Tecnologías |
|---|---|---|
| 🗳️ [Simulador electoral PBA 2025](https://github.com/mirpuertas/simulador-elecciones-pba) | **WIP.** App interactiva para simular elecciones legislativas en la Provincia de Buenos Aires, basada en el sistema de cociente Hare con reparto por residuos. Permite definir intención de voto por sección, elegir entre una simulación aleatoria (Monte Carlo) o una asignación fija (modo determinista), y visualizar los resultados en mapas y gráficos parlamentarios. Incluye edición avanzada por sección, interfaz intuitiva y arquitectura modular pensada para elecciones futuras. | Python, Streamlit, GeoPandas, Plotly, poli_sci_kit |
| 🚇 **Accesibilidad multimodal CABA (2001-2022)** | **WIP.** Caso de estudio de la red de transporte de la Ciudad Autónoma de Buenos Aires (subte, tren, Metrobus y colectivos). Muestra que una métrica clásica como “parada ≤ 800 m” está saturada (> 96 % cobertura) y ya no capta la inequidad real: la brecha actual se manifiesta en la **frecuencia del servicio** y el **tiempo puerta a puerta**. Incluye mapas comparativos 2001-10-22, un logit densidad × alta_bus y discusión metodológica sobre la necesidad de usar GTFS. | Python, GeoPandas, Statsmodels, QGIS |
