[![GitHub followers](https://img.shields.io/github/followers/octocat?style=social)](https://github.com/CriselPy)![Licencia](https://img.shields.io/github/license/CriselPy/Analisis-y-Visualizacion-de-Datos-de-Acciones-e-Ingresos)
![Último Commit](https://img.shields.io/github/last-commit/CriselPy/Analisis-y-Visualizacion-de-Datos-de-Acciones-e-Ingresos)
![Estrellas](https://img.shields.io/github/stars/CriselPy/Analisis-y-Visualizacion-de-Datos-de-Acciones-e-Ingresos)
<a href="https://github.com/CriselPy" target="_blank">
  <img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white" alt="GitHub"/>
</a>
<a href="https://www.linkedin.com/in/cristina-ortega-451750275/" target="_blank">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"/>
</a>

# Análisis y Visualización de Datos de Acciones e Ingresos

Este proyecto analiza y visualiza datos históricos de precios de acciones e ingresos trimestrales para Tesla y GameStop. Utiliza `yfinance` para datos de acciones y técnicas de web scraping para ingresos, y presenta gráficos comparativos interactivos para ilustrar las tendencias en estos dos aspectos.

## Tabla de Contenidos
1. [Introducción](#introducción)
2. [Binder](#binder)
3. [Requisitos](#requisitos)
4. [Instalación](#instalación)
5. [Preguntas y Respuestas](#preguntas-y-respuestas)
6. [Resultados](#resultados)
7. [Contribuciones](#contribuciones)
8. [Licencia](#licencia)
9. [Contacto](#contacto)
10. [Enlaces a Recursos Externos](#enlaces-a-recursos-externos)

## Introducción
Este proyecto tiene como objetivo analizar y visualizar la evolución histórica de los precios de acciones e ingresos trimestrales de Tesla (TSLA) y GameStop (GME). Utilizando la biblioteca `yfinance` para la extracción de datos financieros y técnicas de web scraping para obtener información de ingresos, este proyecto proporciona herramientas para una comparación visual detallada.

## Binder
Puedes ejecutar este proyecto directamente en un entorno interactivo en [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/CriselPy/Analisis-y-Visualizacion-de-Datos-de-Acciones-e-Ingresos/HEAD?filepath=An%C3%A1lisis%20de%20Datos%20Hist%C3%B3ricos%20de%20Ingresos%20y%20Creaci%C3%B3n%20de%20un%20Cuadro%20de%20Mando.ipynb). Esto te permitirá interactuar con el notebook sin necesidad de instalar nada en tu máquina local.

## Requisitos
Este proyecto utiliza las siguientes bibliotecas de Python:
- `yfinance` para la obtención de datos históricos de acciones.
- `pandas` para la manipulación y análisis de datos.
- `requests` y `BeautifulSoup` para la extracción de datos de ingresos mediante web scraping.
- `plotly` para la creación de gráficos interactivos.

## Instalación
Sigue estos pasos para configurar el entorno localmente:
1. Clona el repositorio.
   
   ```bash
   git clone https://github.com/CriselPy/Analisis-y-Visualizacion-de-Datos-de-Acciones-e-Ingresos.git

2. Instala las dependencias:

   ```bash
    pip install -r requirements.txt
   
Instala las dependencias desde el archivo `requirements.txt` utilizando `pip` o `conda`.

   ```bash
   conda install --file requirements.txt

```
## Preguntas y Respuestas
1. **Pregunta 1:** Utilice `yfinance` para extraer datos bursátiles. Restablezca el índice, guarde y visualice las cinco primeras filas del marco de datos `tesla_data` utilizando la función `head`.
   **Captura de Pantalla:**
   ![Pregunta 1: Tesla Data Head](https://github.com/CriselPy/Analisis-y-Visualizacion-de-Datos-de-Acciones-e-Ingresos/blob/main/Pregunta%201%20Tesla%20Data%20Head.png)
2. **Pregunta 2:** Utilizar Webscraping para extraer datos de ingresos de Tesla. Muestre las cinco últimas filas del marco de datos `tesla_revenue` utilizando la función `tail`.
   **Captura de Pantalla:**
   ![Pregunta 2: Tesla Revenue Tail](https://github.com/CriselPy/Analisis-y-Visualizacion-de-Datos-de-Acciones-e-Ingresos/blob/main/Pregunta%202%20Tesla%20Revenue%20Tail.png)

3. **Pregunta 3:** Utilice `yfinance` para extraer datos bursátiles. Restablezca el índice, guarde y visualice las cinco primeras filas del marco de datos `gme_data` utilizando la función `head`.
   **Captura de Pantalla:**
   ![Pregunta 3: GME Data Head](https://github.com/CriselPy/Analisis-y-Visualizacion-de-Datos-de-Acciones-e-Ingresos/blob/main/Pregunta%203%20GME%20Data%20Head.png)

4. **Pregunta 4:** Utilizar Webscraping para extraer datos de ingresos de GameStop. Muestre las cinco últimas filas del marco de datos `gme_revenue` utilizando la función `tail`.
   **Captura de Pantalla:**
   ![Pregunta 4: GME Revenue Tail](https://github.com/CriselPy/Analisis-y-Visualizacion-de-Datos-de-Acciones-e-Ingresos/blob/main/Pregunta%204%20GME%20Revenue%20Tail.png)

5. **Pregunta 5:** Representar gráficamente las acciones de Tesla. Utilice la función `make_graph` para representar gráficamente los datos de las acciones de Tesla, proporcionando también un título para el gráfico.
   **Captura de Pantalla:**
   ![Pregunta 5: Gráfico de Acciones de Tesla](https://github.com/CriselPy/Analisis-y-Visualizacion-de-Datos-de-Acciones-e-Ingresos/blob/main/Pregunta%205%20Gr%C3%A1fico%20de%20Acciones%20de%20Tesla.png)

6. **Pregunta 6:** Representar gráficamente las acciones de GameStop. Utilice la función `make_graph` para representar gráficamente los datos de las acciones de GameStop, proporcionando también un título para el gráfico.
   **Captura de Pantalla:**
   ![Pregunta 6: Gráfico de Acciones de GameStop](https://github.com/CriselPy/Analisis-y-Visualizacion-de-Datos-de-Acciones-e-Ingresos/blob/main/Pregunta%206%20Gr%C3%A1fico%20de%20Acciones%20de%20GameStop.png)

## Resultados
El proyecto proporciona gráficos interactivos que permiten comparar los precios de acciones y los ingresos trimestrales de Tesla y GameStop. Estos gráficos facilitan la visualización de tendencias y patrones a lo largo del tiempo.

## Contribuciones
Este proyecto fue desarrollado por [Cristina Ortega Trujillo](https://github.com/CriselPy) (nombre profesional: Crisel Nublo). La autoría del ejercicio original sin resolver para el Curso de Ciencia de Datos de IBM pertenece a Joseph Santarcangelo.

Si deseas contribuir, sigue estos pasos:
1. Haz un fork del repositorio.
2. Crea una nueva rama para tu característica (`git checkout -b nueva-caracteristica`).
3. Realiza tus cambios y haz un commit (`git commit -am 'Añadida nueva característica'`).
4. Empuja tus cambios (`git push origin nueva-caracteristica`).
5. Crea un pull request para revisar tus cambios.

## Licencia
Este proyecto está licenciado bajo la Licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más detalles.

## Contacto

Para cualquier pregunta o comentario, contacta
# **Cristina Ortega Trujillo** 🪻
<a href="https://github.com/CriselPy" target="_blank">
  <img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white" alt="GitHub"/>
</a>
<a href="https://www.linkedin.com/in/cristina-ortega-451750275/" target="_blank">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"/>
</a>

¡Gracias por tu interés en este proyecto!

## Enlaces a Recursos Externos

Aquí se proporcionan enlaces útiles relacionados con el análisis de datos, visualización y las tecnologías utilizadas en este proyecto:

- [Documentación de yfinance](https://pypi.org/project/yfinance/)
- [Documentación de pandas](https://pandas.pydata.org/docs/)
- [Documentación de requests](https://docs.python-requests.org/en/latest/)
- [Documentación de BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
- [Documentación de plotly](https://plotly.com/python/)

