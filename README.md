# Beispielcode zum Talk "Scalable OCR" vom DevDay 2018 in Dresden
Der Beispielcode zum Talk "Skalierbare OCR Pipelines mit Python, Tensorflow und Tesseract"

## Requirements installieren
Die Jupyter-Notebooks nutzen verschiedene Python Pakete, von Jupyter über Numpy zu OpenCV und Tensorflow. Die Pakete können mit

```bash
pip install -r requirements.txt --user
```

installiert werden.

## Tesseract
Damit das Tesseract-Notebook ausgeführt werden kann muss Tesseract installiert sein.

Der Link: [Tesseract](https://github.com/tesseract-ocr/tesseract/wiki)

## Tensorflow:
Da das trainierte Modell nicht veröffentlicht werden kann möchte ich für die Tensorflow/Keras Beispiele
auf das Jupyter Notebook von François Chollet aus dem Buch "Deep Learning with Python" verweisen.

Das Notebook zeigt wie

- Convolutions visualisiert werden 
- Mit Grad-CAM Heatmaps über die Features im Bild generiert werden die zur Aktivierung geführt haben

Zum [Notebook](https://github.com/fchollet/deep-learning-with-python-notebooks/blob/master/5.4-visualizing-what-convnets-learn.ipynb)