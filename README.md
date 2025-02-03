# 📊 Proyecto de Análisis de Datos Multifuente

## 📌 Descripción del Proyecto
Este proyecto tiene como objetivo la integración, análisis y visualización de datos provenientes de múltiples bases de datos relacionales y no relacionales. Se trabajó con **MySQL, SQLite, MongoDB y Redis**, consolidando finalmente los datos en **SQL Server** para una mejor organización y análisis.

🔍 Características Principales
✅ Integración de datos desde 10+ fuentes en bases relacionales (MySQL, SQLite, SQL Server) y NoSQL (MongoDB, Redis).
✅ Análisis y limpieza de datos utilizando Python y Jupyter Notebook.
✅ Dashboards en Power BI para visualización interactiva de tendencias y patrones.
✅ Implementación de análisis de sentimientos sobre datos de redes sociales y eventos.
✅ Gestión de datos en entornos locales y en la nube.

## 🔍 Tecnologías Utilizadas
- **Bases de datos:** MySQL, SQLite, MongoDB, Redis, SQL Server  
- **Lenguaje de programación:** Python  
- **Bibliotecas:** Pandas, Matplotlib, Seaborn, Plotly, SQLAlchemy, PyMongo  
- **Herramientas de visualización:** Power BI, Jupyter Notebook  

## 📂 Fuentes de Datos
Los datasets utilizados en el proyecto provienen de diversas fuentes abiertas:

- **Exceso de velocidad:** [🔗 Enlace](https://n9.cl/wh8qjd)
- **Migración:** [🔗 Enlace](https://acortar.link/S7ZO8M)
- **Hábitos de consumo:** [🔗 Enlace](https://acortar.link/F0OJ2Y)
- **Hábitos estudiantiles:** [🔗 Enlace](https://n9.cl/fbb4l)
- **Mundial 2022:** [🔗 Enlace](https://n9.cl/llf44h)
- **Ranking de equipos:** [🔗 Enlace](https://n9.cl/juzt1y)
- **Social Media:** [🔗 Enlace](https://acortar.link/ej9aLz)
- **Zomato Restaurantes:** [🔗 Enlace](https://acortar.link/CaPAyb)

## 🏗️ Estructura del Proyecto
- **📁 data/** → Archivos CSV y JSON originales 
- **📁 notebooks/** → Notebooks de Jupyter con análisis exploratorio
- **📁 dashboards/** → Informes generados en Power BI
- **📁 README.md/** → Documentación detallada del proyecto.
- **📁 requirements.txt/** → Librerías necesarias para correr el Jupyter Notebook.

  📌 Explicación de las Librerías
✅ Manejo de Datos
pandas → Para trabajar con DataFrames.
✅ Bases de Datos
sqlite3 → Módulo nativo para SQLite.
mysql-connector-python → Para conectarte a MySQL.
pymysql → Alternativa para conexión MySQL.
pymongo → Para conectarte a MongoDB.
redis → Para manejar Redis.
sqlalchemy → ORM para manejar bases de datos SQL.
✅ Análisis de Sentimientos
nltk → Procesamiento de lenguaje natural.
textblob → Análisis de sentimiento fácil de usar.
✅ Extracción y Manejo de Datos
json → Para manejar datos en formato JSON.
✅ Jupyter Notebook
jupyter → Para ejecutar el Notebook.



## 📊 Análisis y Resultados
Se realizaron diversos análisis de datos, incluyendo:
- **Violaciones de tránsito en Ecuador:** Identificación de provincias con más infracciones y tendencias de velocidad.
- **Mundial 2022:** Análisis de goles por partido y efectividad de los equipos.
- **Hábitos estudiantiles:** Relación entre tiempo de estudio y rendimiento académico.
- **Social Media:** Impacto de las redes sociales en la productividad y satisfacción laboral.
- **Migración:** Distribución de flujos migratorios y tendencias por género y nacionalidad.
- **Hábitos de consumo:** Preferencias de gasto y métodos de pago más utilizados.
- **Restaurantes:** Relación entre calificación y costo promedio de los restaurantes.

## 🛠️ Instalación y Uso
Para ejecutar el proyecto en tu máquina local:
1. Clona este repositorio:
   ```bash
   git clone https://github.com/tu_usuario/nombre_repositorio.git
   ```
2. Instala las dependencias:
   ```bash
   pip install -r requirements.txt
   ```
3. Ejecuta los scripts de ETL:
   ```bash
   python scripts/etl.py
   ```
4. Explora los análisis en Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

## 📜 Licencia
Este proyecto se distribuye bajo la licencia MIT. Puedes utilizarlo y modificarlo libremente con atribución adecuada.

## 📧 Contacto
Si tienes preguntas o sugerencias, no dudes en contactarme a través de GitHub.

---
🚀 **¡Gracias por visitar este proyecto!**
