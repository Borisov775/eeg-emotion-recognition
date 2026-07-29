# Emotion Recognition through EEG Signals

**Classifying human emotional and functional state from EEG signals — an affective brain–computer-interface (BCI) project.**

> Team/student project developed at ITMO University (2022). It explores the full affective-BCI
> pipeline — from EEG signal to an emotion model — together with the design of an application
> around it. See `EEG_Emotion_Prediction.ipynb` for the machine-learning work.

---

## Overview

Emotions leave measurable traces in brain activity, and — unlike facial expression, speech, or
behavior — physiological signals are hard to mask. This project uses a brain–computer interface
to read EEG signals and infer a person's emotional and functional state: for example, their
readiness to perform a task, or a patient's affective state when other assessment methods are
unavailable. The intended application loads or streams EEG data and produces its estimates in
real time.

## What's in this repository

| File | What it is |
|------|-----------|
| [`EEG_Emotion_Prediction.ipynb`](./EEG_Emotion_Prediction.ipynb) | **Core** — the EEG → features → emotion-classification pipeline (data, preprocessing, model, evaluation) |
| [`App Design/`](./App%20Design%20) | Application design and UI concept |
| [`Emotion_Recognition_using_EEG_signals.pptx`](./Emotion_Recognition_using_EEG_signals.pptx) | Project presentation |
| [`Resources.md`](./Resources.md) | Datasets and references |

## Approach

- **Signal source:** OpenBCI (brain–computer-interface hardware).
- **Pipeline:** EEG acquisition → preprocessing → feature extraction → emotion classification.
- **Modeling:** machine learning / deep learning — full workflow and results in
  [`EEG_Emotion_Prediction.ipynb`](./EEG_Emotion_Prediction.ipynb).
- **Datasets & references:** see [`Resources.md`](./Resources.md).

## Tech stack

`Python` (ML/DL, notebook) · `OpenBCI` · application layer in `Java` / `Kotlin` (Android/iOS) · a bit of `Arduino`

## Team & my role

Four-person student team — two on machine/deep learning and datasets, two on application
development and integration. **My role:** [state clearly what you did — e.g., ML/DL modeling and
dataset selection, or app development and integration].

## Status

Early project: working ML notebook plus application design. Not a production system.

## Context

Part of my broader interest in affective computing and human states, which now informs my work on
human-centered AI and human–AI interaction.

## Author

George Borisov · [email] · [github / website]

## License

MIT
