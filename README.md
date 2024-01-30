# Proyecto de Clasificación de Imágenes con EfficientNetB0

Este proyecto utiliza TensorFlow/Keras y la arquitectura EfficientNetB0 para realizar la clasificación de imágenes en un conjunto de datos de 4 categorías.


## Data Source

The proejct builds a model trained, validated and tested using the dataset from the paper:
["Hard Sample Aware Noise Robust Learning for Histopathology Image Classification"](https://ieeexplore.ieee.org/document/9600806){:target="_blank"}

@article{zhuhard,
  title={Hard Sample Aware Noise Robust Learning for Histopathology Image Classification},
  author={Zhu, Chuang and Chen, Wenkai and Peng, Ting and Wang, Ying and Jin, Mulan},
  journal={IEEE transactions on medical imaging}
}


## Estructura del Repositorio

- `data/`: Contiene los conjuntos de datos de entrenamiento, validación y prueba.
- `notebooks/`: Cuadernos de Jupyter con análisis y visualizaciones adicionales.
- `src/`: Código fuente del proyecto, incluyendo el script de entrenamiento y evaluación.
- `saved_models/`: Directorio para almacenar los modelos entrenados.
- `requirements.txt`: Lista de dependencias y versiones necesarias.


## Configuración del Entorno

Asegúrate de tener Python instalado. Puedes instalar las dependencias utilizando:

```bash
pip install -r requirements.txt
```




## Ajuste de Parámetros
Puedes ajustar los parámetros del modelo editando el archivo src/train_model.py. Experimenta con la tasa de aprendizaje, tamaño del lote, y otros hiperparámetros según sea necesario.

## Resultados
Los resultados del modelo se pueden encontrar en el cuaderno notebooks/analysis.ipynb. Incluye métricas de rendimiento y visualizaciones.

## Contribuciones
Las contribuciones son bienvenidas. Si encuentras problemas o mejoras, crea un problema o envía una solicitud de extracción.

## Licencia
Este proyecto está bajo la licencia MIT.
