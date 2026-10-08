# HRI 15 Gestures — RG-HGR

## Overview

This project focuses on **Human-Robot Interaction (HRI) gesture recognition**, with experimental evaluation performed across multiple gesture-recognition datasets and result configurations.

The work studies the recognition of human gestures and provides a structured collection of experimental outputs for analyzing model performance, learned representations, predictions, robustness, and classification behavior.

The project includes experimental results from:

- **15-Gesture**
- **Net4UC**
- **SHREC'21**

The experiments include results generated using **Seed 11** to provide a fixed experimental configuration for analysis and comparison.

---

## Project Objective

The primary objective is to investigate and evaluate gesture-recognition models for HRI applications.

Gesture recognition is an important component of human-robot interaction because it allows robots and intelligent systems to interpret human actions as meaningful commands or interaction signals.

The project therefore focuses on evaluating how effectively learned models can distinguish between different gesture classes and how their learned representations behave under different evaluation conditions.

---

## Experimental Datasets

### 15-Gesture

The 15-Gesture experiments focus on recognition across a set of fifteen human gesture categories.

The corresponding experimental artifacts include model outputs, predictions, evaluation metrics, learned representations, and visualization results.

### Net4UC

The Net4UC experiments provide an additional evaluation setting for studying gesture-recognition performance.

The saved results allow analysis of predictions, learned representations, classification behavior, and model evaluation.

### SHREC'21

The SHREC'21 experiments provide another benchmark for evaluating gesture-recognition performance.

The associated results contain model outputs and analysis artifacts that can be used to study recognition performance and representation quality.

---

## Experimental Outputs

The project preserves a wide range of experimental artifacts, including:

### Model Artifacts

Saved trained-model files are provided for the corresponding experiments.

These artifacts allow the trained models to be inspected or used for further analysis where the required environment is available.

### Predictions

Prediction files provide the model's outputs for the evaluated data splits.

These can be used to analyze:

- correctly classified samples;
- incorrectly classified samples;
- class-wise behavior;
- prediction distributions;
- model decision patterns.

### Evaluation Metrics

The experiments include saved evaluation metrics for analyzing model performance.

These outputs support quantitative comparison of the experimental results across different evaluation splits and configurations.

### Classification Reports

Classification reports provide detailed class-level evaluation information, allowing analysis beyond overall performance.

They can be used to investigate differences in recognition behavior between gesture classes.

### Training History

Training-history artifacts preserve information about model learning during training.

These outputs can be used to study:

- training behavior;
- validation behavior;
- convergence;
- changes in loss;
- changes in evaluation performance.

---

## Learned Representations

The project also preserves intermediate model representations such as:

- **Embeddings**
- **Logits**

These representations provide insight into the information learned by the model before the final classification stage.

Embedding outputs can be further analyzed to investigate whether different gesture classes form meaningful structures in the learned feature space.

---

## Visualization and Analysis

Several visualization artifacts are included to make the experimental behavior easier to inspect.

These include:

- accuracy plots;
- loss curves;
- confusion matrices;
- 2D t-SNE visualizations;
- 3D t-SNE visualizations;
- corresponding t-SNE sample-index information.

### Confusion Matrices

Confusion matrices provide a class-by-class view of recognition behavior.

They help identify:

- frequently confused gesture classes;
- strong-performing classes;
- difficult gesture classes;
- systematic classification errors.

### t-SNE Visualization

t-SNE projections are used to visualize high-dimensional learned representations in lower-dimensional spaces.

These visualizations provide an intuitive view of how samples from different gesture classes are distributed within the learned representation space.

Both 2D and 3D visualizations are included where available.

---

## Robustness Analysis

The experimental results also include robustness-related outputs.

These results are intended to investigate how recognition performance behaves under different evaluation conditions and to provide additional evidence about the reliability of the learned representations and predictions.

---

## Reproducibility

The project preserves experimental artifacts required for detailed result analysis, including:

- trained models;
- dataset split indices;
- predictions;
- evaluation metrics;
- classification reports;
- training history;
- embeddings;
- logits;
- robustness results;
- visualization outputs.

Using the preserved artifacts, researchers can inspect the experimental results without necessarily regenerating every visualization or evaluation output from the beginning.

Exact reproduction of the experiments may additionally depend on the original preprocessing pipeline, software environment, framework versions, hardware configuration, and training configuration.

---

## Project Structure

The experimental results are organized into three primary groups:

```text
15-Gesture/
└── Seed_11/

Net4UC/
└── Seed_11/

SHREC'21/
└── Seed_11/
```

Each experiment contains its corresponding model outputs, evaluation results, numerical data, and visualization artifacts.

---

## Intended Use

The project is intended for:

- research and experimentation in HRI;
- human gesture-recognition research;
- model-performance analysis;
- comparison of recognition behavior across datasets;
- learned-representation analysis;
- robustness analysis;
- visualization of gesture feature spaces;
- further research and development in gesture-based interaction systems.

---

## Summary

This project provides a structured collection of experimental results for **HRI gesture recognition**, covering the **15-Gesture, Net4UC, and SHREC'21** experimental settings.

By preserving models, predictions, metrics, classification reports, learned representations, robustness results, and visualizations, the project provides a comprehensive basis for examining both the quantitative performance and qualitative behavior of gesture-recognition models.
