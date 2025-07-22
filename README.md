# 💬 Análisis de Sentimientos de Comentarios del New York Times

Este proyecto realiza un análisis de sentimientos sobre comentarios de usuarios del New York Times, utilizando procesamiento de lenguaje natural (NLP) y redes neuronales. Se parte de un dataset extenso de más de 2 millones de comentarios públicos y se construye un pipeline completo de preprocesamiento, anotación de sentimientos y entrenamiento de modelos de clasificación.

---

## 🧪 Objetivo

- Tomar únicamente los comentarios del dataset del NYT.
- Procesarlos y etiquetarlos con una clasificación de **sentimiento**.
- Entrenar una red neuronal que sea capaz de **predecir el sentimiento** de un comentario.

---

## 📚 Descripción del Dataset

El dataset original fue extraído de Kaggle:

🔗 [NYT Comments Dataset – Kaggle](https://www.kaggle.com/datasets/aashita/nyt-comments)

Contiene dos componentes:

- **Comentarios**: +2M filas y 34 columnas con texto, autor, fecha, recomendaciones, etc.
- **Artículos**: ~9,000 entradas con metadatos como título, fecha, URL, sección, etc.

> ⚠️ Este proyecto **se enfoca exclusivamente en los comentarios**.

---

## 🛠️ Requisitos e instalación

### 1. Clonar el repositorio

```bash
git clone https://github.com/jquelas/comment_analysis.git
cd comment_analysis
```

### 2. Crear entorno virtual

```bash
# En sistemas Unix/macOS
python3 -m venv env
source env/bin/activate

# En Windows
python -m venv env
.\env\Scriptsctivate
```

### 3. Instalar dependencias

```bash
pip install -r requirements.txt
```

> Asegúrate de tener Python 3.7+ instalado.

---

## 📦 Librerías utilizadas

| Librería | Función |
|----------|---------|
| `pandas`, `numpy` | Manipulación de datos |
| `nltk`, `spacy` | Procesamiento de texto (tokenización, lematización, stopwords) |
| `sklearn` | Vectorización de texto |
| `tensorflow` | Entrenamiento de modelos de deep learning |
| `matplotlib`, `wordcloud` | Visualizaciones |

---

## 🚀 Proceso general

1. 📥 Carga de datos originales (comentarios)
2. 🧹 Preprocesamiento y limpieza de texto
3. 🔍 Etiquetado de sentimiento para cada comentario
4. 🧠 Entrenamiento de red neuronal con los datos procesados
5. 📊 Evaluación del modelo

---

## 🧑‍💻 Autores

- Proyecto desarrollado por [@jquelas](https://github.com/jquelas)

---

## ⚖️ Licencia

Este proyecto está licenciado bajo los términos de la **GNU General Public License v3.0**.