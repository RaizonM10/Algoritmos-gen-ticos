# Algoritmos Genéticos aplicados al Aprendizaje de Máquina

Este repositorio contiene tres ejemplos prácticos del uso de Algoritmos Genéticos (AG) en Machine Learning:

1. **Feature Selection con AG**  
   - Dataset: Breast Cancer (scikit-learn).  
   - Cromosomas: vectores binarios (1 = usar feature, 0 = no usar).  
   - Fitness: accuracy promedio (validación cruzada) usando Regresión Logística.  

2. **Hyperparameter Optimization con AG (Random Forest)**  
   - Dataset: Iris (scikit-learn).  
   - Cromosomas: hiperparámetros (`n_estimators`, `max_depth`, `min_samples_split`, `max_features`).  
   - Fitness: accuracy promedio en validación cruzada.  

3. **Neuroevolution con AG (MLPClassifier)**  
   - Dataset: Digits (scikit-learn).  
   - Cromosomas: arquitectura de red (número de capas, neuronas por capa, activación).  
   - Fitness: accuracy promedio en validación cruzada.  

---

## 🚀 Cómo ejecutar

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/usuario/algoritmos-geneticos-ml.git
   cd algoritmos-geneticos-ml

