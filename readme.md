# Automated Diagnosis of Pneumonia with Neural Networks: Computer Vision

## Descripción del Proyecto
Este proyecto utiliza un modelo de redes neuronales convolucionales (CNNs) para la clasificación automática de imágenes de rayos X del tórax con el objetivo de detectar casos de neumonía. El sistema está diseñado para ayudar en el diagnóstico temprano y preciso de la enfermedad, mejorando los tiempos de respuesta y la eficiencia del personal médico.

## Funcionalidades Principales
- **Detección Automatizada**: El modelo clasifica imágenes de rayos X en dos categorías: Normal y Neumonía, proporcionando una herramienta útil para el diagnóstico médico.
- **Aumentación de Datos**: Implementación de técnicas de aumentación para enriquecer el conjunto de datos y mejorar la robustez del modelo frente a variaciones en las imágenes.
- **Evaluación Exhaustiva**: Análisis del rendimiento del modelo a través de métricas clave, como precisión, recall, f1-score, y visualización de la matriz de confusión para una comprensión detallada de los resultados.
- **Optimización del Modelo**: Ajuste de hiperparámetros y reducción de la tasa de aprendizaje para maximizar el rendimiento del modelo en el conjunto de validación.

## Tecnologías Utilizadas
- **Python**: Lenguaje principal utilizado para la manipulación y análisis de datos.
- **Pandas**: Biblioteca para la manipulación y análisis de datos.
- **Numpy**: Librería fundamental para operaciones numéricas y manejo de arrays.
- **Matplotlib/Seaborn**: Bibliotecas utilizadas para la visualización de datos.
- **TensorFlow/Keras**: Frameworks de Deep Learning para la construcción y entrenamiento del modelo de CNN.
- **ImageDataGenerator de Keras**: Utilizado para la aumentación de imágenes y preparación de datos.
- **Scikit-learn**: Implementación de métricas y evaluación del modelo.
- **Jupyter Notebook**: Entorno de desarrollo interactivo para la implementación del proyecto.

## Instrucciones de Uso

1. **Clonar el repositorio:**

   ```bash
   git clone https://github.com/kelvin-lab/Automated-Diagnosis-of-Pneumonia-with-Neural-Networks-Computer-Vision.git
   ```

2. **Instalar dependencias:**

   Asegúrate de tener un entorno virtual configurado, luego instala las dependencias:

   ```bash
   pip install -r requirements.txt
   ```

3. **Abrir el notebook en Jupyter:**

   Ejecuta Jupyter Notebook desde la terminal o utiliza una plataforma como Google Colab para abrir el archivo `.ipynb`:

   ```bash
   jupyter notebook
   ```

4. **Ejecutar las celdas:**

   Sigue el flujo de trabajo desde la limpieza de datos hasta el análisis y la visualización de los resultados.

## Contribuciones
Las contribuciones para mejorar el análisis o agregar nuevas funcionalidades son bienvenidas. Sigue estos pasos para contribuir:
1. Haz un fork del repositorio.
2. Crea una nueva rama (`git checkout -b feature/nueva-funcionalidad`).
3. Realiza tus cambios y haz commit (`git commit -am 'Añadir nueva funcionalidad'`).
4. Haz push a la rama (`git push origin feature/nueva-funcionalidad`).
5. Abre un Pull Request para revisión.

## Autores
Este proyecto fue desarrollado por **Kelvin Trujillo**.

## Licencia
Este proyecto está bajo la Licencia MIT. Para más información, revisa el archivo [LICENSE](./LICENSE).

## Conclusiones

El modelo desarrollado en este proyecto logró una precisión del 81.7% en el conjunto de prueba, lo que demuestra un rendimiento sólido en la detección de neumonía a partir de imágenes de rayos X. Este proyecto muestra el potencial de la inteligencia artificial para mejorar la atención médica mediante diagnósticos más rápidos y precisos.