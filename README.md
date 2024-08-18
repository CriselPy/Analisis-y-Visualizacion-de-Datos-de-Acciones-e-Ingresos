# Análisis y Visualización de Datos de Acciones e Ingresos

Este proyecto se centra en la extracción y visualización de datos históricos de acciones e ingresos para Tesla y GameStop. Utilizando la biblioteca `yfinance` para datos de acciones y técnicas de web scraping para ingresos, creamos gráficos comparativos que ilustran las tendencias de precios de acciones y los ingresos trimestrales de ambas compañías.

## Tabla de Contenidos
1. [Introducción](#introducción)
2. [Requisitos](#requisitos)
3. [Instalación](#instalación)
4. [Uso](#uso)
5. [Preguntas y Respuestas](#preguntas-y-respuestas)
6. [Resultados](#resultados)
7. [Ejemplos Avanzados](#ejemplos-avanzados)
8. [Capturas de Pantalla](#capturas-de-pantalla)
9. [Estado del Proyecto](#estado-del-proyecto)
10. [Roadmap](#roadmap)
11. [Contribuciones](#contribuciones)
12. [Licencia](#licencia)
13. [Contacto](#contacto)
14. [Recursos Adicionales](#recursos-adicionales)
15. [Vídeos y Tutoriales](#vídeos-y-tutoriales)
16. [Badges y Estado de Construcción](#estado-del-proyecto)

## Introducción
En este proyecto, extraemos datos históricos de precios de acciones e ingresos trimestrales para Tesla (TSLA) y GameStop (GME). Estos datos se visualizan mediante gráficos interactivos para permitir una comparación clara entre el rendimiento de las acciones y los ingresos de las empresas.

## Requisitos
Este proyecto requiere las siguientes bibliotecas:
- `yfinance`
- `pandas`
- `requests` y `BeautifulSoup`
- `plotly`

Puedes instalar estas bibliotecas utilizando pip:
```bash
pip install yfinance requests beautifulsoup4 pandas plotly
## Instalación

Para ejecutar el proyecto localmente, sigue estos pasos:

1. **Clona el Repositorio:**
   ```bash
   git clone https://github.com/tu_usuario/tu_repositorio.git
   cd tu_repositorio
# Guía de Instalación

Para configurar y ejecutar el proyecto localmente, sigue estos pasos:

## 2. Crea un Entorno Virtual (opcional pero recomendado)

El uso de un entorno virtual te ayudará a gestionar las dependencias del proyecto de manera aislada. Puedes crear un entorno virtual utilizando `venv` o `conda`.

- **Con `venv`:**
  ```bash
  python -m venv env
  source env/bin/activate  # En Windows usa `env\Scripts\activate`

