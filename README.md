# 2025-2_sw
pneumonia

# Overview
This repository provides an implementation of an interpretable Chest X-ray Visual Question Answering (CXR-VQA) system using Group Relative Policy Optimization (GRPO) fine-tuning on top of the Qwen2.5-VL-3B model.
Unlike conventional black-box VLMs, our approach encourages models to generate explicit, structured reasoning prior to answering Yes/No clinical queries, improving transparency and trustworthiness in medical AI.

![fig1](./asset/fig1.jpg)

# Datasets

We utilized the Chest X-ray Pneumonia dataset provided on Kaggle to construct a binary Yes/No visual question answering task. Labels indicating the presence or absence of pneumonia were converted into structured question–answer pairs suitable for reinforcement-learning–based reasoning evaluation.

Dataset link: https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia
