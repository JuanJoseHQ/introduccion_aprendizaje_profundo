# Introducción al Aprendizaje Profundo

Entregas del curso **Introducción al Aprendizaje Profundo**.

**Equipo:** Juan José Herrera y Santiago Rodríguez

**Repositorio:** https://github.com/JuanJoseHQ/introduccion_aprendizaje_profundo

## Contenido

| Entrega | Cuaderno | Tema |
|---------|----------|------|
| Primera | [Entrega_1.ipynb](primera_entrega/notebooks/Entrega_1.ipynb) | Detección de transacciones fraudulentas con una red neuronal (MLP) en PyTorch |

## Instalación

```bash
python -m venv .venv
.venv\Scripts\activate         # en Linux/macOS: source .venv/bin/activate
pip install -r requirements.txt
```

## Datos

Los `.csv` no se versionan. Para la primera entrega hay que descargar el conjunto [Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) de Kaggle y guardarlo en `primera_entrega/data/creditcard.csv`.

## Ejecución

Los cuadernos usan rutas relativas, así que hay que abrir Jupyter desde su carpeta:

```bash
cd primera_entrega/notebooks
jupyter notebook
```
