<div align="center">

# NLP Quickbook: Text Classification with Flask

A Python NLP project for building, saving, reusing, and serving a small text classification model through a Flask API.

</div>

## 📌 Overview

NLP Quickbook demonstrates a compact machine learning workflow for natural language processing in Python. The project focuses on a text classification example using the Scikit-Learn stack and exposes the trained model through a Flask API.

The workflow described by the project includes:

- Building a small text classification model
- Writing the trained model to disk
- Loading and reusing the saved model for prediction
- Serving predictions through a Flask-based API
- Providing a simple web page for classifying new movie reviews

The original project description is: **NLP in Python with Deep Learning**.

## 🧰 Technology Stack

| Technology | Purpose |
|---|---|
| Python 3 | Runtime environment |
| Scikit-Learn | Machine learning stack for the text classification model |
| Flask | API and simple web interface |
| pip | Python dependency installation |

## ✨ Features

- Text classification workflow for movie review-style input
- Model training step that saves the trained model to disk
- Prediction step that reuses the saved model
- Flask API for serving model predictions
- Simple local web page for entering and classifying new reviews
- Lightweight structure suitable for learning deployment basics

## 🚀 Running Locally

To run the project locally, use the workflow described in the project documentation:

1. Install Python 3 and pip.
2. Clone the repository.
3. Navigate to the working directory.
4. Install dependencies:

```bash
pip install -r requirements.txt
```

5. Run the Flask API:

```bash
python api.py
```

6. Open a browser and visit:

```text
http://localhost:8000
```

## 🧪 Project Workflow

The project is organized around a simple machine learning deployment flow:

1. `model_train.py` builds a small text classification model and writes it to disk.
2. `model_predict.py` reloads the saved model and uses it for prediction.
3. `api.py` exposes the prediction workflow through Flask.

This makes the project useful as a practical example of moving from a trained NLP model to a locally served API.

## 🎯 Use Cases

NLP Quickbook is relevant for learning and demonstration scenarios such as:

- Understanding how text classification models can be trained in Python
- Practicing model persistence and reuse
- Learning how Flask can expose machine learning predictions
- Creating a small local web interface for NLP classification
- Demonstrating a basic end-to-end machine learning deployment workflow

## ❓ FAQ

### What does this project classify?

The README describes a small text classification model used to classify new movie reviews.

### Is this a Flask API project?

Yes. The model is exposed using Flask through `api.py`.

### Does the project include model training?

Yes. The workflow includes training a text classification model in `model_train.py`.

### Can the trained model be reused?

Yes. The trained model is written to disk and reused by `model_predict.py`.

### What URL is used locally?

When the API is running locally, the documented browser URL is `http://localhost:8000`.

## 📄 License

No license information was provided in the available project description.
