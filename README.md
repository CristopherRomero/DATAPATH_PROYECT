# Proyecto Integrador: Plataforma Analítica Inmobiliaria - **BrickVista S.A.**

## Descripción del Proyecto
Este proyecto busca crear una plataforma analítica avanzada para **BrickVista S.A.**, una empresa (ficticia) de desarrollo y comercialización de proyectos inmobiliarios en América Latina. El objetivo es integrar y analizar datos de ventas, marketing, leads, propiedades y campañas publicitarias, con el fin de optimizar la toma de decisiones en cuanto a precios, desempeño comercial y retorno de inversión publicitaria.

## Objetivos Principales
- Construcción de una plataforma en **Microsoft Fabric** para integrar, procesar y analizar datos clave del negocio inmobiliario.
- Optimización de análisis de precios, rendimiento comercial y efectividad de campañas publicitarias.
  
## Arquitectura

### 1. **Modelo Lakehouse**
Estructura de datos organizada en tres niveles:
- **Bronze**: Datos crudos y sin procesar.
- **Silver**: Datos limpios, transformados y con calidad.
- **Gold**: Datos totalmente refinados, listos para análisis y toma de decisiones.

### 2. **Transformaciones con PySpark**
Procesamiento de datos en **Notebooks PySpark** para aplicar transformaciones y limpieza, garantizando datos listos para su análisis en el **Data Warehouse**.

### 3. **Modelo snowflake en el Data Warehouse**

### 4. **Power BI para Visualización**
Dashboards en **Power BI** para la visualización de KPIs clave, como el análisis de precios, ROI de campañas, inventarios de propiedades y desempeño general.

### 5. **Ingesta Diaria Automática**
Pipeline de carga diaria de datos (a las 00:30 a.m.) desde **Azure Data Lake Storage Gen2** hacia el Lakehouse y el Data Warehouse.

---

## Tecnologías Utilizadas
- **Microsoft Fabric**
- **Azure Data Lake Storage Gen2 (ADLS)**
- **PySpark**
- **SQL (para el modelado estrella en el Data Warehouse)**
- **Power BI**

---

## Lecciones Aprendidas

- **Arquitectura Moderna**: La implementación de un **Lakehouse** y un **modelo estrella** permite una gestión eficiente y escalable de los datos.
- **Transformación y Limpieza de Datos**: La limpieza y desnormalización de datos es crucial para asegurar su calidad y trazabilidad.
- **Visualización Avanzada con Power BI**: La integración de Power BI con el modelo de datos proporciona una visión clara y en tiempo real de KPIs clave, facilitando la toma de decisiones estratégicas.
- **Automatización del Pipeline**: La ingesta diaria de datos asegura que los análisis siempre se basen en datos frescos y actualizados.

---

## Contribuciones

Si deseas contribuir a este proyecto, por favor sigue los pasos a continuación:

1. Fork del repositorio.
2. Crea una rama nueva para tus cambios (`git checkout -b feature/nueva-funcionalidad`).
3. Realiza tus cambios y haz commit de ellos (`git commit -am 'Añadí nueva funcionalidad'`).
4. Empuja los cambios a tu repositorio (`git push origin feature/nueva-funcionalidad`).
5. Abre un Pull Request para que revisemos tus cambios.

---

## Licencia
Este proyecto está bajo la licencia **MIT**.

