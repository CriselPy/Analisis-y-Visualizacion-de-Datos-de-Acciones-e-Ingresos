# Análisis y Visualización de Datos de Acciones e Ingresos

Este proyecto analiza y visualiza datos históricos de precios de acciones e ingresos trimestrales para Tesla y GameStop. Utiliza `yfinance` para datos de acciones y técnicas de web scraping para ingresos, y presenta gráficos comparativos interactivos para ilustrar las tendencias en estos dos aspectos.

## Tabla de Contenidos
1. [Introducción](#introducción)
2. [Requisitos](#requisitos)
3. [Instalación](#instalación)
4. [Uso](#uso)
5. [Preguntas y Respuestas](#preguntas-y-respuestas)
6. [Resultados](#resultados)
7. [Contribuciones](#contribuciones)
8. [Licencia](#licencia)
9. [Contacto](#contacto)
10. [Galería de Imágenes](#galería-de-imágenes)
11. [Badges](#badges)
12. [Visualizaciones Interactivas](#visualizaciones-interactivas)
13. [Tutoriales y Recursos Adicionales](#recursos-adicionales)
14. [Demostraciones en Vídeo](#demostraciones-en-vídeo)
15. [Diagrama de Flujo del Proyecto](#diagrama-de-flujo)
16. [Estado del Proyecto](#estado-del-proyecto)
17. [Comentarios de Usuarios](#comentarios-de-usuarios)
18. [Problemas Conocidos y Soluciones](#problemas-conocidos-y-soluciones)
19. [Historial de Cambios](#historial-de-cambios)
20. [Ejemplos de Datos](#ejemplos-de-datos)
21. [Enlaces a Recursos Externos](#enlaces-a-recursos-externos)

# Análisis y Visualización de Datos de Acciones e Ingresos

Este repositorio contiene un ejercicio sobre análisis y visualización de datos bursátiles y de ingresos. A continuación, se muestran las capturas de pantalla correspondientes a cada pregunta del ejercicio.

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

## Enlaces

- [Enlace a la tarea en Watson Studio](https://watson-studio-url)

Asegúrate de reemplazar `https://watson-studio-url` con la URL correcta de tu tarea en Watson Studio y verifica que las rutas de las imágenes sean correctas.

## Introducción
Este proyecto tiene como objetivo analizar y visualizar la evolución histórica de los precios de acciones e ingresos trimestrales de Tesla (TSLA) y GameStop (GME). Utilizando la biblioteca `yfinance` para la extracción de datos financieros y técnicas de web scraping para obtener información de ingresos, este proyecto proporciona herramientas para una comparación visual detallada.


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

### 6. Uso

**Guía de Uso:**

## Uso
Para ejecutar el análisis y generar gráficos, sigue estos pasos:

1. Abre el script o notebook principal.
2. Ejecuta las celdas en el orden proporcionado para extraer y visualizar los datos.
3. Los gráficos interactivos se generarán automáticamente al ejecutar las celdas correspondientes.

### Ejemplos de Ejecución:
1. **Extracción de Datos de Tesla:**
   - Ejecuta el código para obtener datos históricos de Tesla.
2. **Extracción de Ingresos de Tesla:**
   - Usa técnicas de web scraping para obtener datos de ingresos trimestrales.
3. **Visualización de Datos de Tesla y GameStop:**
   - Ejecuta las celdas para generar gráficos comparativos.
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
Este proyecto fue desarrollado por [Cristina Ortega Trujillo](https://github.com/tu_usuario) (nombre profesional: Crisel Nublo). La autoría del ejercicio original pertenece a Joseph Santarcangelo.

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
## Badges
Puedes añadir badges a tu README para mostrar información relevante sobre tu proyecto, como el estado del build, cobertura de pruebas, etc.

![Estado del Build](https://img.shields.io/github/workflow/status/tu_usuario/tu_repositorio/Build)
![Licencia](https://img.shields.io/github/license/tu_usuario/tu_repositorio)

### Cómo añadir elementos interactivos

1. **Badges**: Puedes usar sitios como [Shields.io](https://shields.io/) para generar badges que muestren el estado del build, la cobertura de pruebas, entre otros.

2. **Gráficos Interactivos**: Si usas herramientas como Plotly para generar gráficos, puedes incluir enlaces a dashboards interactivos o imágenes que representen estos gráficos.

3. **Enlaces a Recursos**: Puedes añadir enlaces a tutoriales, documentación o recursos externos que puedan ser útiles para entender mejor el proyecto o para aprender sobre las tecnologías utilizadas.

Recuerda actualizar los enlaces y rutas de las imágenes según corresponda a tu proyecto y estructura de carpetas. ¡Espero que esto te ayude a tener un README.md completo y atractivo para tu repositorio en GitHub!
# Análisis y Visualización de Datos de Acciones e Ingresos

Descripción breve del proyecto.

## Badges

### Estado del Build
![Estado del Build](https://img.shields.io/github/workflow/status/CriselPy/An-lisis-y-Visualizaci-n-de-Datos-de-Acciones-e-Ingresos/Build)

### Licencia
![Licencia](https://img.shields.io/github/license/CriselPy/An-lisis-y-Visualizaci-n-de-Datos-de-Acciones-e-Ingresos)

### Último Commit
![Último Commit](https://img.shields.io/github/last-commit/CriselPy/An-lisis-y-Visualizaci-n-de-Datos-de-Acciones-e-Ingresos)

### Versión del Proyecto
![Versión](https://img.shields.io/github/v/release/CriselPy/An-lisis-y-Visualizaci-n-de-Datos-de-Acciones-e-Ingresos)

### Número de Estrellas
![Estrellas](https://img.shields.io/github/stars/CriselPy/An-lisis-y-Visualizaci-n-de-Datos-de-Acciones-e-Ingresos)

### Descargas del Paquete (Si aplica)
![Descargas](https://img.shields.io/pypi/dm/tu_paquete)
## Visualizaciones Interactivas
Explora las visualizaciones interactivas en los siguientes enlaces:
- [Gráficos Interactivos de Tesla](https://mi_plataforma_de_visualizacion.com/tesla)
- [Gráficos Interactivos de GameStop](https://mi_plataforma_de_visualizacion.com/gamestop)

## Recursos Adicionales
- [Tutorial de `yfinance`](https://www.example.com/tutorial-yfinance)
- [Guía de Web Scraping con BeautifulSoup](https://www.example.com/tutorial-beautifulsoup)
- [Documentación de Plotly](https://plotly.com/python/)

## Demostraciones en Vídeo
- [Vídeo de Introducción al Proyecto](https://www.example.com/video-introduccion)
- [Tutorial Paso a Paso en YouTube](https://www.example.com/video-tutorial)

## Diagrama de Flujo
![Diagrama de Flujo del Proyecto](ruta/a/tu/diagrama_flujo.png)

## Estado del Proyecto
![Coverage](https://img.shields.io/codecov/c/github/tu_usuario/tu_repositorio)
![Tests](https://img.shields.io/github/workflow/status/tu_usuario/tu_repositorio/Tests)

## Comentarios de Usuarios
- "Una herramienta increíble para analizar acciones. ¡Muy útil!" – [Usuario1](https://github.com/usuario1)
- "Me encantó la visualización interactiva de ingresos." – [Usuario2](https://github.com/usuario2)

## Problemas Conocidos y Soluciones
- **Problema:** Error al obtener datos de ingresos.
  **Solución:** Asegúrate de que la URL del scraping esté actualizada.

- **Problema:** Problemas con la visualización interactiva.
  **Solución:** Verifica que las bibliotecas de Plotly estén actualizadas a la última versión.

## Historial de Cambios
Consulta el archivo [CHANGELOG.md](CHANGELOG.md) para detalles sobre las versiones y cambios del proyecto.

## Ejemplos de Datos
Aquí hay un ejemplo de cómo se ven los datos de precios de acciones:

    ```python
import yfinance as yf
data = yf.download('TSLA', start='2020-01-01', end='2023-01-01')
print(data.head())

