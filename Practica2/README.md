# Práctica 2: Deep Learning 📋

Los diferentes ejercicios a realizar de esta práctica se dividen en varios archivos, nombrados en función del ejercicio que haya sido desarrollado en él.

---

## Ejercicio 1: BaseNNet en CIFAR100 
Construcción de una red neuronal convolucional sencilla, denominada **BaseNet**, trabajando sobre el conjunto de datos **CIFAR100**.

## Ejercicio 2: Mejoras sobre el modelo BaseNet
Se procede a introducir **mejoras sobre el modelo construido** en el ejercicio previo, aplicando **data augmentation**, **batch normalization** y **bloques residuales**, entre otros.

## Ejercicio 3: Transfer Learning y fine-tuning con ResNet50 en el SPR X-Ray Age Prediction Challenge
Se trabajará con el dataset **SPR X-Ray Age Prediction Challenge** de Kaggle, haciendo uso de un modelo ResNet50 pre-entrenado en ImageNet, y siguiendo diferentes estrategias:
- Creación de una cabecera personalizada, y entrenando desde scratch.
- Creación de una cabecera personalizada, entrenando únicamente la cabecera añadida.
- Uso de cabecera por defecto añadida por FastAi, entrenando únicamente la cabecera.
- Uso de cabecera por defecto, entrenando el modelo usando **fine_tune**.

## Ejercicio 4: Primeros pasos de IA explicable aplicada a redes neuronales convolucionales
Se trabajará con el dataset **Caltech-UCSD Birds-200-2011**, usando un modelo ResNet18 preentrenado con ImageNet, realizando un fine-tuning de toda la red.

