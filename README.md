# Proyecto MLOps - Clasificación con MLP y MLflow

Este repositorio contiene la implementación de un modelo base de red neuronal (Perceptrón Multicapa) utilizando `scikit-learn`, integrado con `MLflow` para el seguimiento de experimentos, registro de métricas e hiperparámetros.

## Equipo de Trabajo y Roles

* 1 (Infraestructura y Configuración)
* 2 (Desarrollo del Modelo Base)
* 3 (Integración de Tracking - MLflow)
* 4 (Experimentación y Consolidación)

## Tecnologías Utilizadas
* Python 3
* Scikit-Learn (Modelado y Datasets)
* Pandas (Manipulación de datos)
* MLflow (Tracking de experimentos y MLOps)

---

##  Guía de Inicio Rápido

Para colaborar en este proyecto, sigue estos pasos en tu terminal para replicar el entorno de desarrollo exacto.

### 1. Clonar el repositorio

```bash
git clone https://github.com/jhordanfree/proyecto-mlops-equipo6.git
cd proyecto-mlops-equipo6
```

### 2. Crear y activar el entorno virtual
Es indispensable usar el entorno virtual para no generar conflictos con las versiones de las librerías.

* **Usar:**
  
```bash
python -m venv venv
venv\Scripts\activate
```

### 3. Instalar dependencias
Con el entorno activado (debes ver (venv) en tu terminal), instala los paquetes requeridos:

* **Usar:**

```bash
pip install -r requirements.txt
```

### 4. Levantar el servidor de MLflow
Para visualizar la interfaz gráfica y los registros de los experimentos, ejecuta:

* **Usar:**
  mlflow ui
  El servidor estará disponible en tu navegador web ingresando a http://localhost:5000 o http://127.0.0.1:5000.
