# CS247-Empathy-Mental-Health

Welcome to the Empathy Mental Health Evaluator and Generator repository! This repository contains code for both the evaluator and generator modules, along with associated scripts to facilitate their usage.

## Contents

1. [Evaluator](#evaluator)
2. [Evaluator Scripts](#evaluator-scripts)
3. [Generator](#generator)
4. [Generator Scripts](#generator-scripts)

---

## Evaluator

This repository contains codes and dataset access instructions for the [EMNLP 2020 publication](https://arxiv.org/pdf/2009.08441) on understanding empathy expressed in text-based mental health support. This study introduces a computational framework to identify empathy in text-based mental health platforms, utilizing a multi-task RoBERTa-based bi-encoder model and a corpus of annotated conversations within a new dataset, revealing insights into empathy expression and learning behaviors over time.

## Evaluator Scripts

Contains one script which contains training, finetuning, and testing commands on Evaluator. Results are generated via tables and graphs.

## Generator

This repository contains codes and dataset access instructions for the [EMNLP 2021 publication](https://aclanthology.org/2021.findings-emnlp.70.pdf) on empathetic dialogue generation. Current empathetic response generation approaches focus on predicting emotion labels for generating responses, but by ignoring the emotion cause, their proposed framework enhances response quality through emotion cause recognition and incorporation into the generation process, as validated by improved performance in emotion recognition and response generation tasks.

## Generator Scripts

Contains two scripts for generator response pipeline and RL with SFT improvements. The first contains the pipeline to obtain responses from any generator on the reddit test dataset. Will then run these responses through the evaluator to evaluate the effectiveness of a generator in providing empathetic responses. The second implements SFT using EmpatheticDialogues along with RL techniques using a custom reward function.

## Usage

To use the evaluator module, follow these steps:

1. Clone the repository to your local machine.
2. Adjust scripts to navigate to `evaluator` and `generator` directories as needed.
3. Run the evaluation scripts on Kaggle or Google Colab.

