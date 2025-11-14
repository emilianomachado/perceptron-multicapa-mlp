# Perceptrón Multicapa (MLP)

Implementación de un **Perceptrón Multicapa** (Multilayer Perceptron, MLP) utilizando Python en Google Colab.  
Este proyecto muestra cómo construir y entrenar una red neuronal sencilla desde cero, sin usar frameworks de alto nivel como TensorFlow o PyTorch, para comprender los fundamentos del aprendizaje profundo.

---

## 🧠 ¿Qué es un Perceptrón Multicapa?

Un **MLP** es una red neuronal feedforward compuesta por:

- Una capa de entrada
- Una o más capas ocultas
- Una capa de salida

Cada neurona aplica una función de activación no lineal (por ejemplo, sigmoide o ReLU), lo que permite al modelo aprender problemas más complejos y **no linealmente separables**, a diferencia del perceptrón simple.

El entrenamiento se realiza mediante:

- **Propagación hacia adelante (forward propagation)**
- **Retropropagación del error (backpropagation)**  
  ajustando los pesos con gradiente descendente.

---

## 📂 Contenido del proyecto

Este repositorio incluye:

- `Perceptron_Multicapa.ipynb`  
  Notebook con:
  - Implementación completa del MLP
  - Definición de arquitectura: capas, neuronas y funciones de activación
  - Cálculo del forward pass
  - Implementación de backpropagation desde cero
  - Entrenamiento con distintas épocas y tasas de aprendizaje
  - Evaluación del desempeño del modelo
  - Gráficos y análisis (si corresponden)

---

## 🚀 ¿Cómo ejecutar el proyecto?

1. Abrí el notebook en Google Colab.
2. Ejecutá todas las celdas en orden.
3. Podés modificar:
   - Cantidad de capas ocultas
   - Número de neuronas por capa
   - Función de activación
   - Tasa de aprendizaje
   - Número de iteraciones (epochs)
   - Dataset

Para experimentar con distintas arquitecturas y observar cómo cambia el rendimiento.

---

## 🛠 Requisitos

El notebook está pensado para ejecutarse directamente en Google Colab.

Librerías utilizadas (todas vienen instaladas por defecto en Colab):

- NumPy  
- Matplotlib (si incluye gráficos)

---

## 📈 Resultados

El notebook permite visualizar:

- La evolución del error/función de costo
- Pesos finales aprendidos
- Salidas del modelo
- Comparación entre predicciones y valores reales
- Comprobación de capacidad de generalización

---

## 🧪 Conceptos clave implementados

- Redes feedforward
- No linealidad mediante funciones de activación
- Regla de actualización por gradiente descendente
- Backpropagation manual
- Entrenamiento supervisado
- Evaluación sobre nuevos patrones

---

## 📄 Licencia

Este proyecto es de uso libre para fines educativos y experimentales.

---

## ✨ Autor

Proyecto realizado por **Emiliano Machado** como parte del estudio de redes neuronales y aprendizaje profundo.
