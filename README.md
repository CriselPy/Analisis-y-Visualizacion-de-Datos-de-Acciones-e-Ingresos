![Estado del Build](https://img.shields.io/github/workflow/status/CriselPy/An-lisis-y-Visualizaci-n-de-Datos-de-Acciones-e-Ingresos/Build)
![Licencia](https://img.shields.io/github/license/CriselPy/An-lisis-y-Visualizaci-n-de-Datos-de-Acciones-e-Ingresos)
![Último Commit](https://img.shields.io/github/last-commit/CriselPy/An-lisis-y-Visualizaci-n-de-Datos-de-Acciones-e-Ingresos)
![Versión](https://img.shields.io/github/v/release/CriselPy/An-lisis-y-Visualizaci-n-de-Datos-de-Acciones-e-Ingresos)
![Estrellas](https://img.shields.io/github/stars/CriselPy/An-lisis-y-Visualizaci-n-de-Datos-de-Acciones-e-Ingresos)
# Análisis y Visualización de Datos de Acciones e Ingresos

Este proyecto analiza y visualiza datos históricos de precios de acciones e ingresos trimestrales para Tesla y GameStop. Utiliza `yfinance` para datos de acciones y técnicas de web scraping para ingresos, y presenta gráficos comparativos interactivos para ilustrar las tendencias en estos dos aspectos.

## Tabla de Contenidos
1. [Introducción](#introducción)
2. [Requisitos](#requisitos)
3. [Instalación](#instalación)
5. [Preguntas y Respuestas](#preguntas-y-respuestas)
6. [Resultados](#resultados)
7. [Contribuciones](#contribuciones)
8. [Licencia](#licencia)
9. [Contacto](#contacto)
10. [Galería de Imágenes](#galería-de-imágenes)
12. [Visualizaciones Interactivas](#visualizaciones-interactivas)
16. [Estado del Proyecto](#estado-del-proyecto)
21. [Enlaces a Recursos Externos](#enlaces-a-recursos-externos)
    
## Introducción
Este proyecto tiene como objetivo analizar y visualizar la evolución histórica de los precios de acciones e ingresos trimestrales de Tesla (TSLA) y GameStop (GME). Utilizando la biblioteca `yfinance` para la extracción de datos financieros y técnicas de web scraping para obtener información de ingresos, este proyecto proporciona herramientas para una comparación visual detallada.

## Binder
Puedes ejecutar este proyecto directamente en un entorno interactivo en [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/CriselPy/An-lisis-y-Visualizaci-n-de-Datos-de-Acciones-e-Ingresos/HEAD?filepath=An%C3%A1lisis%20de%20Datos%20Hist%C3%B3ricos%20de%20Ingresos%20y%20Creaci%C3%B3n%20de%20un%20Cuadro%20de%20Mando.ipynb). Esto te permitirá interactuar con el notebook sin necesidad de instalar nada en tu máquina local.

## Requisitos
Este proyecto utiliza las siguientes bibliotecas de Python:
# Análisis y Visualización de Datos de Acciones e Ingresos

A continuación, se muestran las capturas de pantalla correspondientes a cada pregunta del ejercicio.

## Pregunta 1: Utilice yfinance para extraer datos bursátiles

Restablezca el índice, guarde y visualice las cinco primeras filas del marco de datos `tesla_data` utilizando la función `head`.

**Captura de Pantalla:**
![Pregunta 1: Tesla Data Head](https://github.com/CriselPy/An-lisis-y-Visualizaci-n-de-Datos-de-Acciones-e-Ingresos/raw/main/capturas/tesla_data_head.png)

## Pregunta 2: Utilizar Webscraping para extraer datos de ingresos de Tesla

Muestre las cinco últimas filas del marco de datos `tesla_revenue` utilizando la función `tail`.

**Captura de Pantalla:**
![Pregunta 2: Tesla Revenue Tail](https://github.com/CriselPy/An-lisis-y-Visualizaci-n-de-Datos-de-Acciones-e-Ingresos/raw/main/capturas/tesla_revenue_tail.png)

## Pregunta 3: Utilice yfinance para extraer datos bursátiles

Restablezca el índice, guarde y visualice las cinco primeras filas del marco de datos `gme_data` utilizando la función `head`.

**Captura de Pantalla:**
![Pregunta 3: GME Data Head](https://github.com/CriselPy/An-lisis-y-Visualizaci-n-de-Datos-de-Acciones-e-Ingresos/raw/main/capturas/gme_data_head.png)

## Pregunta 4: Utilizar Webscraping para extraer datos de ingresos de GameStop

Muestre las cinco últimas filas del marco de datos `gme_revenue` utilizando la función `tail`.

**Captura de Pantalla:**
![Pregunta 4: GME Revenue Tail](https://github.com/CriselPy/An-lisis-y-Visualizaci-n-de-Datos-de-Acciones-e-Ingresos/raw/main/capturas/gme_revenue_tail.png)

## Pregunta 5: Representar gráficamente las acciones de Tesla

Utilice la función `make_graph` para representar gráficamente los datos de las acciones de Tesla, proporcionando también un título para el gráfico.

**Captura de Pantalla:**
![Pregunta 5: Gráfico de Acciones de Tesla](https://github.com/CriselPy/An-lisis-y-Visualizaci-n-de-Datos-de-Acciones-e-Ingresos/raw/main/capturas/acciones_tesla.png)

## Pregunta 6: Representar gráficamente las acciones de GameStop

Utilice la función `make_graph` para representar gráficamente los datos de las acciones de GameStop, proporcionando también un título para el gráfico.

**Captura de Pantalla:**
![Pregunta 6: Gráfico de Acciones de GameStop](https://github.com/CriselPy/An-lisis-y-Visualizaci-n-de-Datos-de-Acciones-e-Ingresos/raw/main/capturas/acciones_gme.png)


## Requisitos
Este proyecto utiliza las siguientes bibliotecas de Python:
- `yfinance` para la obtención de datos históricos de acciones.
- `pandas` para la manipulación y análisis de datos.
- `requests` y `BeautifulSoup` para la extracción de datos de ingresos mediante web scraping.
- `plotly` para la creación de gráficos interactivos.

Instala las dependencias con el siguiente comando:

    ```bash pip install yfinance requests beautifulsoup4 pandas plotly

### 5. Instalación

**Instrucciones de Instalación:**

## Instalación
1. Clona el repositorio:

   ```bash
   git clone https://github.com/tu_usuario/tu_repositorio.git
   cd tu_repositorio


2. Instala las dependencias:

   ```bash
   pip install -r requirements.txt

Si estás utilizando un entorno de Anaconda, puedes instalar las dependencias directamente desde el archivo requirements.txt usando:
    ```bash
   conda install --file requirements.txt

## Preguntas y Respuestas
1. **Pregunta 1:** ¿Cómo extraer datos históricos de acciones de Tesla usando `yfinance`?
2. **Pregunta 2:** ¿Cómo obtener ingresos trimestrales de Tesla mediante web scraping?
3. **Pregunta 3:** ¿Cómo extraer datos de acciones de GameStop con `yfinance`?
4. **Pregunta 4:** ¿Cómo recopilar datos de ingresos de GameStop mediante web scraping?
5. **Pregunta 5:** ¿Cómo crear un gráfico de precios de acciones de Tesla?
6. **Pregunta 6:** ¿Cómo generar un gráfico de precios de acciones de GameStop?

## Resultados
El proyecto proporciona gráficos interactivos que permiten comparar los precios de acciones y los ingresos trimestrales de Tesla y GameStop. Estos gráficos facilitan la visualización de tendencias y patrones a lo largo del tiempo.

### Ejemplos de Gráficos:
- **Gráfico de Acciones de Tesla**
  ![Tesla Stock](ruta/a/tu/imagen_tesla.png)
- **Gráfico de Ingresos de Tesla**
  ![Tesla Income](ruta/a/tu/imagen_ingresos_tesla.png)
- **Gráfico de Acciones de GameStop**
  ![GameStop Stock](ruta/a/tu/imagen_gamestop.png)
- **Gráfico de Ingresos de GameStop**
  ![GameStop Income](ruta/a/tu/imagen_ingresos_gamestop.png)

## Contribuciones
Este proyecto fue desarrollado por [Cristina Ortega Trujillo](https://github.com/CriselPy) (nombre profesional: Crisel Nublo). La autoría del ejercicio original pertenece a Joseph Santarcangelo.

Si deseas contribuir, sigue estos pasos:
1. Forkea el repositorio.
2. Crea una rama para tu característica (`git checkout -b nueva-caracteristica`).
3. Realiza tus cambios y confirma (`git commit -am 'Añadida nueva característica'`).
4. Empuja tus cambios (`git push origin nueva-caracteristica`).
5. Crea un pull request para revisar tus cambios.
## Licencia
Este proyecto está licenciado bajo la Licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más detalles.
## Contacto
Para cualquier pregunta o comentario, contacta a [Cristina Ortega Trujillo](mailto:tu_email@ejemplo.com).

¡Gracias por tu interés en este proyecto!
## Galería de Imágenes
Aquí puedes ver algunos ejemplos de los gráficos generados por el proyecto:

- **Gráfico de Acciones de Tesla:**
  ![Tesla Stock](ruta/a/tu/imagen_tesla.png)
- **Gráfico de Ingresos de Tesla:**
  ![Tesla Income](ruta/a/tu/imagen_ingresos_tesla.png)
- **Gráfico de Acciones de GameStop:**
  ![GameStop Stock](ruta/a/tu/imagen_gamestop.png)
- **Gráfico de Ingresos de GameStop:**
  ![GameStop Income](ruta/a/tu/imagen_ingresos_gamestop.png)
