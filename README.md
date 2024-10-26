# HackMXBucleInfinito24
Para subir y trabajar todo lo relativo al reto del HackMX, 2024.

## Reto Thales : Análisis y Visualización de Datos Abiertos en Mapa

### Objetivos.
Aplicar  nuevas tecnologías como el Data Analysis, Big Data y Prediction en seguridad y combate al crimen para el bien de la ciudadanía.

### Descripción
Laa Fiscalía de la Ciudad de México publica en internet datos abiertos sobre carpetas de investigación, compartiendo así la cantidad y tipo de delitos que se investigan en la CDMX. El link es: https://datos.cdmx.gob.mx/dataset/carpetas-de-investigacion-fgj-de-la-ciudad-de-mexico

Estos datos incluyen las columnas de fecha, tipo de delito y localización (latitud y longitud), y abarcan un periodo de 4 años.

#### Etapas del Reto
- Ingestar los datos y desplegarlos en un mapa, ya sea con puntos o *hotspots* (zonas). La interfaz debe permitir al usuario seleccionar el mes o día de visualización, así como filtrar por tipo de delito. Se seleccionarán sólo ciertos tipos de delito para facilitar un poco este paso.
- Aplicar algún algoritmo de Predicción (*Random Forest, K-Nearest*, ..) para predecir la ocurrencia de cierto tipo de delito en el futuro, visualizándolo en el mapa.
Para esto es posible que se tengan que crear sectores sobre el mapa de la Ciudad de México, y la aplicación haría como preguntas en cada sector para, con el algoritmo, predecir la probabilidad de ocurrencia de cierto delito en ese sector. Pero depende de la solución escogida.
