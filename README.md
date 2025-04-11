# 📦 my_model_package

This modular Python package is designed to represent the basic structure of a Machine Learning model. Its purpose is to demonstrate how to organize files and submodules clearly and maintainably using package-oriented programming.

## 🧠 Project Structure

```
my_model_package/
├── main.py
└── my_model/
    ├── __init__.py
    ├── training/
    │   ├── __init__.py
    │   ├── dataset.py
    │   ├── training_loop.py
    │   └── loss.py
    ├── submission/
    │   ├── __init__.py
    │   ├── submit.py
    │   └── run_context.py
    └── metrics/
        ├── __init__.py
        ├── precision.py
        ├── recall.py
        └── fid_score.py
```

## 🧩 Module Descriptions

### 📁 `training/`
- `dataset.py`: Handles dataset loading and preprocessing.
- `training_loop.py`: Defines the training loop logic.
- `loss.py`: Computes the loss function.

### 📁 `submission/`
- `submit.py`: Responsible for generating and submitting predictions.
- `run_context.py`: Defines the runtime context for inference.

### 📁 `metrics/`
- `precision.py`: Calculates the precision metric.
- `recall.py`: Calculates the recall metric.
- `fid_score.py`: Computes the FID score (used for generative model evaluation).

## ▶️ Usage

To run the package and verify module loading, simply execute:

```bash
python3 main.py
```

This will print messages to the console from each module describing its purpose.

## 💡 Requirements

- Python 3.7+
- Folder structure must follow the scheme above

## 📚 Reference

Inspired by: [LearnPython – Python Packages](https://learnpython.com/blog/most-popular-python-packages/)