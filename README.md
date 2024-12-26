
# **Análisis de Datos Meteorológicos y Aplicaciones de Inteligencia Artificial**

## **Descripción**
Este proyecto se centra en el análisis de datos meteorológicos utilizando códigos METAR y su aplicación en la toma de decisiones empresariales. El cuaderno Jupyter incluido en este repositorio se desarrolla como parte de una práctica para los alumnos del Máster en Dirección de Empresas, combinando conceptos básicos de ciencia de datos e inteligencia artificial.

## **Contenido del Proyecto**
- **Datos:** El proyecto utiliza códigos METAR correspondientes al Aeropuerto de Madrid-Barajas (LEMD) durante el año 2019.
- **Objetivos principales:**
  1. Cargar y explorar datos meteorológicos codificados en formato METAR.
  2. Limpiar y transformar los datos para su análisis.
  3. Desarrollar modelos de predicción y análisis basados en los datos meteorológicos.
  4. Reflexionar sobre las implicaciones empresariales de los datos y modelos.

## **Estructura**
```
proyecto/
├── data/                # Carpeta para los datos (puede incluirse en Google Drive).
├── notebooks/           # Contiene el cuaderno Jupyter principal.
├── README.md            # Archivo de documentación.
└── requirements.txt     # Lista de dependencias del proyecto.
```

## **Requisitos**
Para ejecutar este proyecto, se necesita:
- **Python 3.8+**
- Bibliotecas requeridas (instalables desde `requirements.txt`):
  - pandas
  - numpy
  - matplotlib
  - gdown (si los datos están en Google Drive)

Para instalar las dependencias, utiliza:
```bash
pip install -r requirements.txt
```

## **Uso**
1. **Clonar el repositorio:**
   ```bash
   git clone https://github.com/tu_usuario/analisis-meteorologico-IA.git
   cd analisis-meteorologico-IA
   ```

2. **Ejecutar el cuaderno Jupyter:**
   - Navega a la carpeta `notebooks` y abre el archivo `.ipynb` en Jupyter Notebook o JupyterLab.

3. **Cargar datos desde Google Drive (si aplica):**
   Si los datos no están incluidos directamente, descárgalos usando el siguiente código dentro del cuaderno:
   ```python
   import gdown
   gdown.download("https://drive.google.com/uc?id=FILE_ID", "data/archivo.pkl", quiet=False)
   ```

4. **Sigue las instrucciones del cuaderno para realizar las tareas y análisis.**

## **Resultados esperados**
- Visualizaciones y análisis de los datos meteorológicos.
- Predicciones y modelos que reflejen relaciones entre las variables meteorológicas.
- Reflexión sobre cómo los datos meteorológicos pueden influir en decisiones estratégicas.

## **Contribuciones**
Las contribuciones son bienvenidas. Por favor, sigue el formato de GitHub Flow y abre un Pull Request con tus sugerencias o mejoras.

## **Licencia**
Este proyecto está disponible bajo la licencia [MIT](https://opensource.org/licenses/MIT).
