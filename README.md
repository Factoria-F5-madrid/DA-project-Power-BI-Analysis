# 🚀 Dashboard Analytics en Power BI

<img width="11520" height="3456" alt="Banner-power-BI" src="https://github.com/user-attachments/assets/80acade7-8274-4f52-8598-b3df2b701642" />


## 🔗 Este proyecto cierra la cadena

Con los mismos equipos, este es el **tercer acto** de un mismo recorrido:

| | Qué hicisteis | Con qué |
| :--- | :--- | :--- |
| **Proyecto III** | Extrajisteis un dataset analítico a mano y decidisteis el grano | SQL |
| **Proyecto IV** | Convertisteis esa extracción en un ETL automático y montasteis un dashboard | Python + Excel |
| **Proyecto V** | **Rehacéis ese mismo dashboard con la herramienta profesional** | Power BI |

Ya conocéis los datos, ya sabéis qué preguntas responde el negocio y ya habéis chocado con los límites de Excel. Aquí tenéis la herramienta que hace lo que allí no podíais: modelo en estrella, medidas DAX, interactividad de verdad.

> [!TIP]
> Sacad la lista de «esto lo quería hacer y el Excel no me dejaba» que anotasteis en el Proyecto IV. Ese es vuestro guion.

## 📜 Briefing

### 🔍 Planteamiento  

Somos el departamento de Business Intelligence de una StartUp de reciente fundación que pretende
desarrollar producto de software propio en el campo inmobiliario. Nuestro principal reclamo
como empresa y de cara a los inversores es que somos una empresa moderna
completamente data driven que incorporamos tecnologías de análisis modernas en nuestros
productos.
Recientemente hemos sido contratados por la empresa AirBnB, quien nos ha cedido
algunos datos de algunas de las ciudades más importantes para que desarrollemos un sistema
de reporting y dashboards que permita extraer información útil de manera ágil y visual. De alguna 
manera es una prueba para contratarnos para futuros proyectos, por lo que cuanto más valor 
podamos proporcionar a través de visualizaciones claras e insights accionables, mejor.
La clave es demostrar nuestra capacidad para transformar datos en información valiosa usando 
herramientas de BI profesionales.

---

## 🎯 Objetivos del Proyecto  

* **Carga y transformación de datos** usando Power Query  
* **Modelado de datos** para análisis multidimensional  
* **Generar dashboards interactivos** en Power BI con visualizaciones profesionales  
* **Extraer insights accionables** para decisiones de negocio  

---

## 👥 Equipos

**Equipos de 3 o 4 personas**, los mismos que en los Proyectos III y IV.

## 📦 Condiciones de Entrega  

Para la fecha de entrega, los equipos deberán presentar:  

✅ **Archivo .pbix de Power BI** completamente funcional y documentado   

✅ **Documentación de ETL** explicando las transformaciones realizadas en Power Query  

✅ **Modelo de datos** diagramado y documentado con relaciones y medidas DAX  

✅ **Demo en vivo** mostrando el funcionamiento del dashboard con navegación y filtros  

✅ **Presentación ejecutiva**, explicando los hallazgos clave y cómo el dashboard responde a preguntas de negocio  

✅ **Tablero Kanban** con la gestión del proyecto (Trello, Jira, Github Project, etc.)  

---

## ⚙️ Tecnologías Obligatorias  

- **Herramienta principal:** Microsoft Power BI Desktop  
- **ETL:** Power Query (M Language)  
- **Análisis:** DAX (Data Analysis Expressions)  
- **Visualización:** Power BI Visuals nativos y personalizados  
- **Control de versiones:** Git / GitHub (para documentación y versiones del archivo .pbix)  
- **Gestión del proyecto:** Trello, Jira, Github Projects  

---
## 🏆 Datos

Elegid **una** de las dos vías:

### 🅰️ Continuidad · Olist *(por defecto)*

Los CSV que genera el ETL de vuestro **Proyecto IV**. Es la opción recomendada: ya conocéis el dominio, el grano está decidido y podéis comparar directamente vuestro dashboard de Excel con el de Power BI.

Si necesitáis recargar la base, el volcado está en la [carpeta de formación en Drive](https://drive.google.com/drive/folders/1apSXjn6eQ5o9RdutbD4skSjvH6ytvR06?usp=sharing) (`olist.sql.gz`).

### 🅱️ Cambio de aire · AirBnB

Si vuestro equipo prefiere empezar con datos nuevos, el planteamiento de arriba —la consultora de BI contratada por AirBnB— sigue vigente con sus propios datos:

[AirBnB ciudades CSV](https://drive.google.com/drive/folders/17sYr63LjEX30-3-KjXIaPP-bRwEmMqpf)

### 🆓 Vuestros propios datos

Como siempre, podéis traer otra fuente. Justificadla en el README y aseguraos de que da para los niveles de entrega.

> [!NOTE]
> Los **niveles de entrega** de más abajo están redactados sobre el caso AirBnB. Si vais por Olist, la equivalencia es directa: precios → `price` y `payment_value`, ubicación → estados y ciudades de Brasil, disponibilidad → estados del pedido y tiempos de entrega, y el análisis comparativo entre ciudades pasa a ser entre **estados o categorías de producto**.

## 🏆 Niveles de Entrega  

### 🟢 **Nivel Esencial:**  
✅ **Carga y limpieza completa** de datos usando Power Query  
- Conexión a todas las fuentes de datos  
- Limpieza de valores nulos y duplicados  
- Transformación de tipos de datos  
- Creación de columnas calculadas básicas  

✅ **Modelo de datos básico** en Power BI  
- Creación de relaciones entre tablas  
- Tablas de dimensión y hecho identificadas  
- Medidas DAX básicas (totales, promedios, conteos)  

✅ **Dashboard con 3-5 visualizaciones clave**  
- Gráficos de distribución de precios  
- Análisis temporal de disponibilidad  
- Mapa de propiedades por ubicación  

✅ **Documentación del proceso ETL**  
- Pasos de transformación documentados  
- Explicación de decisiones de limpieza  
- README en GitHub con instrucciones de uso  

### 🟡 **Nivel Medio:**  
✅ **Dashboard interactivo completo** en Power BI Service  
- Múltiples páginas con temáticas específicas  
- Panel ejecutivo con KPIs principales  
- Filtros interactivos (slicers) aplicados globalmente  
- Navegación entre páginas configurada  

✅ **Modelo de datos optimizado**  
- Tablas de calendario creadas  
- Jerarquías implementadas (ej: ciudad → barrio)  
- Medidas DAX avanzadas (YoY, MoM, ratios)  

✅ **Visualizaciones avanzadas**  
- Gráficos personalizados (bullet charts, KPIs)  
- Tooltips enriquecidos con información adicional  
- Segmentación por múltiples dimensiones  

✅ **Análisis comparativo entre ciudades**  
- Benchmarking de precios y ocupación  
- Tablas comparativas con condicional formatting  

### 🟠 **Nivel Avanzado:**  
✅ **Dashboard completamente parametrizado**  
- Bookmarks para vistas predefinidas  
- Botones de navegación personalizados  
- Modo móvil optimizado  

✅ **ETL automatizado y escalable**  
- Funciones personalizadas en Power Query  
- Parámetros para facilitar mantenimiento  
- Optimización de rendimiento en carga  

✅ **Análisis de segmentación avanzado**  
- Análisis de Pareto (80/20) de propiedades  
- Segmentación por tipo de propiedad y amenities  
- Identificación de outliers con visualizaciones específicas  

✅ **Integración con Power BI Service**  
- Actualización programada configurada  
- Roles de seguridad implementados  
- Alerta de datos configurada  

### 🔴 **Nivel Experto:**  
✅ **Solución de BI completa y profesional**  
- Múltiples dashboards interconectados  
- Informes paginados para reporting formal  
- App de Power BI creada y publicada  

✅ **Automatización completa del pipeline**  
- Power Automate flows para notificaciones  
- Gateway de datos configurado para fuentes locales  
- Pipeline de CI/CD para versiones del dashboard  

✅ **Análisis predictivo visual** (solo con herramientas nativas de Power BI)  
- Líneas de tendencia y forecasting visual  
- Análisis de decomposición temporal  
- Detección visual de anomalías  

✅ **Sistema de governance implementado**  
- Lineage view documentado  
- Impact analysis realizado  
- Performance analyzer optimizado  


## 📋 Requisitos Específicos de Power BI  

1. **Todos los datos deben procesarse exclusivamente en Power Query/DAX**
2. **No se permite uso de Python/R para transformaciones o análisis**
3. **El foco debe estar en capacidades nativas de Power BI**
4. **Se valorará especialmente la usabilidad y diseño profesional**
5. **La solución debe ser fácilmente mantenible y escalable**

