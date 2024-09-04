## Descripción

Este proyecto utiliza un modelo de aprendizaje automático para clasificar frutas y determinar si una fruta es una fresa. El script entrena un modelo de red neuronal utilizando un conjunto de datos de frutas y evalúa su precisión.

## Características

- **Cargado de datos:** El script carga un conjunto de datos de frutas desde un archivo CSV.
- **Preprocesamiento:** Los datos se normalizan utilizando `StandardScaler` para mejorar el rendimiento del modelo.
- **Modelo:** Se entrena un `MLPClassifier` (Perceptrón Multicapa) para la clasificación.
- **Evaluación:** Se calcula la precisión del modelo en el conjunto de datos de prueba.

## Requisitos

Para ejecutar este script, asegúrate de tener las siguientes bibliotecas de Python instaladas:

- `pandas`
- `scikit-learn`

Puedes instalar las dependencias necesarias con pip:

```bash
pip install pandas scikit-learn
```

## Uso

1. **Cargar los datos:** Asegúrate de que el archivo `datosFrutas.csv` esté disponible en el directorio de trabajo.
2. **Ejecutar el script:** Ejecuta el script para entrenar el modelo y evaluar su precisión.
3. **Resultados:** El script imprimirá la precisión del modelo en el conjunto de datos de prueba.

```bash
python modelo_para_saber_si_la_fruta_es_una_fresa.py
```

## Conjunto de Datos

El conjunto de datos utilizado debe contener características relevantes de diferentes frutas, como tamaño, color, y textura, y una etiqueta que indique si la fruta es una fresa.
