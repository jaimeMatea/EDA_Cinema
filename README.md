# 🎬 EL ESPEJO DEL MUNDO
### Un viaje por la historia del siglo XX a través del cine y los datos

**Análisis exploratorio de datos (EDA) sobre la representación cinematográfica de las transformaciones sociales, políticas y económicas entre 1919 y 1989.**

---

## 📖 Sobre el proyecto

¿Puede el cine convertirse en un reflejo de la sociedad de su época? ¿Es posible identificar las preocupaciones de una generación a través de las historias que aparecen en la gran pantalla?

**El espejo del mundo** es un proyecto de análisis exploratorio de datos (EDA) que busca explorar la relación entre el cine y el contexto histórico en el que se desarrolla. A través del estudio de películas y de diferentes indicadores sociales, se analizan las principales preocupaciones, conflictos y transformaciones que marcaron distintas sociedades a lo largo del siglo XX.

El proyecto abarca el periodo comprendido entre **1919 y 1989** y se estructura en tres grandes etapas históricas. Cada una de ellas estudia diferentes países y temáticas cinematográficas, relacionando las puntuaciones asignadas a las películas con indicadores externos que permiten contextualizar los resultados.

La idea principal es utilizar el cine como una ventana a la historia: observar qué temas aparecen en las películas, cómo evoluciona su presencia a lo largo del tiempo y si esos cambios coinciden con las transformaciones sociales y políticas de cada época.

**Porque detrás de cada película puede existir una pequeña parte de la historia de la sociedad que la hizo posible.**

---

## 🎯 Objetivos del proyecto

El objetivo principal es explorar cómo se representan determinadas realidades sociales, políticas y económicas en el cine y cómo evoluciona su presencia a lo largo de diferentes periodos históricos.

Para ello, se plantean los siguientes objetivos:

- Analizar la evolución temporal de diferentes temáticas sociales presentes en las películas.
- Comparar las representaciones cinematográficas entre países y periodos históricos.
- Estudiar posibles relaciones entre las temáticas del cine y los indicadores sociales de cada época.
- Identificar cambios y tendencias en la representación de los conflictos, las preocupaciones y las transformaciones de la sociedad.
- Utilizar visualizaciones para comunicar los resultados de forma clara, intuitiva y atractiva.
- Explorar el potencial del cine como fuente complementaria para estudiar la historia y la evolución social.

---

# 🕰️ Estructura del estudio

El proyecto se divide en tres capítulos, cada uno centrado en un contexto histórico diferente.

## CAPÍTULO I — EL MUNDO DE ENTREGUERRAS
**Estados Unidos, Reino Unido y Alemania (1919-1939)**

Tras la Primera Guerra Mundial, las sociedades tuvieron que afrontar profundas transformaciones económicas, políticas y sociales. La inestabilidad, el desempleo, la pobreza y el temor a un nuevo conflicto marcaron el periodo de entreguerras.

En esta primera etapa se estudia cómo aparecen representadas estas preocupaciones en el cine de tres países que vivieron el periodo desde realidades muy diferentes.

### Variables cinematográficas

| Variable | Temática analizada |
|---|---|
| `poverty_score` | Pobreza, desigualdad y dificultades económicas. |
| `unemployment_score` | Desempleo, precariedad e inestabilidad laboral. |
| `political_instability_score` | Crisis políticas, tensiones ideológicas e inestabilidad institucional. |
| `fear_future_score` | Incertidumbre, pesimismo y miedo ante el futuro. |

### Indicadores sociales

| Indicador | Qué permite analizar |
|---|---|
| `GDP per capita` | Evolución del contexto económico y del nivel de producción por habitante. |
| `v2x_polyarchy` | Calidad de la democracia electoral y evolución de las condiciones democráticas. |

**Objetivo del capítulo:** explorar si las preocupaciones económicas y políticas de la sociedad de entreguerras encuentran un reflejo en las temáticas cinematográficas.

---

## CAPÍTULO II — UN MUNDO MARCADO POR LA GUERRA Y SUS CONSECUENCIAS
**Estados Unidos, Italia, Japón y Francia (1940-1960)**

La Segunda Guerra Mundial transformó profundamente el mundo. Millones de personas perdieron la vida, ciudades enteras quedaron destruidas y numerosos países tuvieron que afrontar las consecuencias económicas, sociales y humanas del conflicto.

Tras la guerra, la reconstrucción y el comienzo de la Guerra Fría introdujeron nuevas preocupaciones. El desarrollo de las armas nucleares y la posibilidad de una nueva guerra mundial marcaron el inicio de una etapa de incertidumbre.

Esta segunda parte analiza cómo aparecen representadas la guerra, sus consecuencias y los nuevos temores de la posguerra en el cine de cuatro países.

### Variables cinematográficas

| Variable | Temática analizada |
|---|---|
| `war_score` | Conflictos bélicos, violencia militar, ocupación y destrucción. |
| `poverty_score` | Escasez, hambre, desigualdad y dificultades económicas. |
| `political_repression_score` | Autoritarismo, censura, persecuciones y pérdida de libertades. |
| `trauma_score` | Secuelas psicológicas, sufrimiento, duelo y consecuencias emocionales de la guerra. |
| `nuclear_fear_score` | Temor a las armas atómicas, la destrucción masiva y una posible guerra nuclear. |

### Indicadores sociales

| Indicador | Qué permite analizar |
|---|---|
| `life_expectancy` | Evolución de la esperanza de vida y de las condiciones generales de salud. |
| `infant_mortality` | Mortalidad infantil y condiciones sanitarias y sociales. |
| `civilian_deaths` | Víctimas civiles de la Segunda Guerra Mundial. |
| `military_deaths` | Víctimas militares de la Segunda Guerra Mundial. |

**Objetivo del capítulo:** explorar cómo las consecuencias humanas de la guerra, el deterioro de las condiciones de vida y el miedo a una nueva destrucción aparecen representados en el cine de posguerra.

---

## CAPÍTULO III — ESPAÑA: DE LA REPRESIÓN A LA TRANSFORMACIÓN SOCIAL
**España (1961-1989)**

Entre 1961 y 1989, España experimentó una profunda transformación política, social y cultural. Los últimos años del franquismo, la Transición y la consolidación de la democracia dieron paso a nuevos valores, libertades y formas de entender la sociedad.

La incorporación progresiva de la mujer al mercado laboral, la evolución de las estructuras familiares, los cambios en las relaciones afectivas y la aparición de nuevos fenómenos culturales reflejaron una sociedad en plena transformación.

Esta última etapa estudia cómo aparecen representados estos cambios en el cine español.

### Variables cinematográficas

| Variable | Temática analizada |
|---|---|
| `drug_score` | Consumo de drogas y situaciones relacionadas con sus consecuencias sociales. |
| `women_empowerment_score` | Autonomía femenina, independencia y cuestionamiento de los roles tradicionales. |
| `family_tradition_score` | Modelos familiares tradicionales, matrimonio y valores conservadores. |
| `sexual_freedom_score` | Sexualidad, relaciones afectivas y cuestionamiento de las convenciones sociales. |
| `political_repression_score` | Censura, autoritarismo, persecución ideológica y limitación de libertades. |

### Indicadores sociales

| Indicador | Qué permite analizar |
|---|---|
| `female_activity_rate` | Participación de las mujeres en la población activa. |
| `cannabis` | Evolución del consumo de cannabis. |
| `cocaine` | Evolución del consumo de cocaína. |
| `heroin` | Evolución del consumo de heroína. |
| `anfetaminas` | Evolución del consumo de anfetaminas. |
| `divorce_rate_per_1000` | Número de divorcios por cada 1.000 habitantes. |

### División histórica

Para facilitar la interpretación de los resultados, el periodo se divide en tres etapas:

- **Franquismo (1961-1975):** últimos años de la dictadura y pervivencia de valores sociales tradicionales.
- **Transición (1976-1978):** transformación política e institucional tras la muerte de Franco.
- **Democracia (1979-1989):** consolidación democrática y profundización de los cambios sociales y culturales.

**Objetivo del capítulo:** explorar cómo la transformación de la sociedad española se refleja en el cine, prestando especial atención a los cambios en los roles de género, la familia, la sexualidad, el consumo de drogas y las libertades políticas.

---

# ⚙️ Metodología

El proyecto sigue un proceso de análisis exploratorio de datos que combina información cinematográfica con indicadores sociales e históricos.

### 1. Recopilación de información cinematográfica

Se parte de diferentes conjuntos de datos cinematográficos, principalmente:

- **IMDb:** información sobre títulos, años de estreno, directores y otros metadatos de las películas.
- **CMU Movie Summary Corpus:** información adicional sobre películas y sus argumentos o sinopsis.

Ambas fuentes se utilizan para construir un conjunto de datos cinematográfico que permita trabajar con información de diferentes películas y periodos históricos.

### 2. Limpieza y transformación de datos

Se realiza un proceso de preparación de la información para garantizar que los datos puedan combinarse y analizarse correctamente.

Entre las principales tareas se encuentran:

- Tratamiento de valores ausentes.
- Normalización de títulos y nombres de países.
- Homogeneización de los años de estreno.
- Eliminación y tratamiento de registros duplicados.
- Combinación de diferentes fuentes cinematográficas.
- Transformación de los datos para facilitar las comparaciones por país y año.

### 3. Clasificación temática de las películas

Una de las partes fundamentales del proyecto consiste en asignar puntuaciones a las películas según la presencia de las temáticas seleccionadas en cada periodo.

Cada variable cinematográfica utiliza una escala de **0 a 5**, donde:

- **0:** ausencia de la temática.
- **5:** presencia muy destacada de la temática.

Estas puntuaciones permiten cuantificar la importancia o presencia de los temas analizados en las películas y estudiar su evolución temporal.

Es importante señalar que las puntuaciones miden la presencia de una temática, no necesariamente la postura de la película ante ella. Por ejemplo, una puntuación elevada en pobreza no significa que la película critique o defienda una determinada situación económica, sino que la pobreza tiene una presencia relevante en su contenido.

### 4. Recopilación de indicadores sociales

Para cada etapa se incorporan conjuntos de datos externos relacionados con las principales características sociales, económicas y políticas del periodo.

Los indicadores se preparan para poder relacionarlos con las películas mediante variables comunes, principalmente el país y el año cuando la información está disponible con ese nivel de detalle.

### 5. Análisis exploratorio y visualización

Una vez preparados los conjuntos de datos, se realizan diferentes análisis y visualizaciones para explorar:

- Evolución temporal de las temáticas cinematográficas.
- Comparaciones entre países.
- Diferencias entre etapas históricas.
- Relación entre las puntuaciones cinematográficas y los indicadores sociales.
- Cambios en la representación de las preocupaciones sociales a lo largo del tiempo.

Se utilizan gráficos de líneas, diagramas de dispersión, gráficos de burbujas, mapas de calor, gráficos combinados y otras visualizaciones diseñadas para facilitar la interpretación de los resultados.

---

# 📊 Herramientas y tecnologías

Las principales herramientas utilizadas durante el desarrollo del proyecto son:

| Herramienta | Aplicación |
|---|---|
| **Python** | Lenguaje principal de programación y análisis. |
| **Pandas** | Limpieza, transformación y manipulación de datos. |
| **NumPy** | Operaciones numéricas y tratamiento de datos. |
| **Matplotlib** | Representación gráfica de información. |
| **Seaborn** | Visualización estadística. |
| **Plotly** | Creación de gráficos interactivos y visualizaciones avanzadas. |
| **Jupyter Notebook** | Desarrollo y documentación del análisis exploratorio. |
| **Git y GitHub** | Control de versiones y almacenamiento del proyecto. |

---

# 📁 Estructura del proyecto

El proyecto está organizado en diferentes directorios para separar los datos, los análisis y los recursos utilizados.

Una posible representación de su organización es:

```text
EL_ESPEJO_DEL_MUNDO/
│
├── 1_Data/
│   ├── Raw/
│   │   ├── IMDb/
│   │   ├── CMU/
│   │   └── Social_Data/
│   │
│   └── Processed/
│       ├── Peliculas/
│       └── Indicadores_Sociales/
│
├── 2_Analytics/
│   ├── EDA_estudio_datos_1919_1939.ipynb
│   ├── EDA_estudio_datos_1940_1960.ipynb
│   └── EDA_estudio_datos_1961_1989.ipynb
│
├── 3_Resources/
│   └── ...
│
└── README.md
```

*Nota: el árbol representa una organización orientativa; los nombres y directorios deben ajustarse a la estructura definitiva del repositorio.*

---

# 🔎 Consideraciones y limitaciones

Como todo análisis exploratorio, este proyecto presenta algunas limitaciones que deben tenerse en cuenta al interpretar los resultados:

- **Representatividad cinematográfica:** las películas analizadas constituyen una muestra del cine de cada periodo y país, por lo que no necesariamente representan toda la producción cinematográfica existente.
- **Puntuaciones temáticas:** la clasificación de las películas permite cuantificar la presencia de determinados temas, pero incorpora un componente interpretativo.
- **Indicadores sociales:** las fuentes externas pueden presentar diferencias de cobertura temporal, metodología y disponibilidad de datos entre países.
- **Comparabilidad:** no todos los indicadores tienen la misma periodicidad ni representan exactamente el mismo fenómeno que las variables cinematográficas.
- **Relación y causalidad:** las coincidencias entre las tendencias cinematográficas y los indicadores sociales no demuestran una relación causal. El análisis busca identificar patrones y posibles asociaciones, no establecer que el contexto social determine directamente el contenido de las películas.

En particular, los datos acumulados de víctimas de la Segunda Guerra Mundial no deben interpretarse como cifras anuales, y los valores de divorcios anteriores a su legalización en España no representan la ausencia real de rupturas matrimoniales.

---

# 💡 Conclusiones y propósito final

**El espejo del mundo** pretende mostrar cómo el cine puede utilizarse como una herramienta complementaria para explorar la historia y comprender las preocupaciones de las sociedades que lo producen.

A través de tres etapas históricas, el proyecto recorre casi siete décadas de transformaciones:

- Del mundo de entreguerras y sus tensiones económicas y políticas.
- A las consecuencias de la Segunda Guerra Mundial y el nacimiento de la era nuclear.
- Hasta la transformación social y cultural de España durante el final del franquismo y la consolidación de la democracia.

Más allá de analizar películas de forma individual, el proyecto busca descubrir patrones colectivos y observar cómo determinados temas adquieren mayor o menor presencia según el momento histórico.

**Porque el cine no solo cuenta historias: también conserva las huellas de las sociedades que las imaginaron.**

---

## 👨‍💻 Autor

**Proyecto desarrollado por:** Jaime Matea Polo.

**Ámbito:** Análisis de datos · Exploratory Data Analysis (EDA) · Cine · Historia · Sociedad.

**Tecnologías principales:** Python, Pandas, NumPy, Plotly, Matplotlib y Seaborn.

---

*EL ESPEJO DEL MUNDO — Un recorrido por la historia del siglo XX a través del cine y los datos.*
