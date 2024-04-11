# QAPipeline-using-LLMs

This repository contains a Python script for processing books and generating summaries, questions, and answers using large language models (LLMs).

## Overview

The "qa-llamacpp-pipeline" notebook contains all the code required to execute the tasks. The pipeline is designed to allow you to easily extract meaningful insights from books PDF files. We implement three naive LLM chains followed by a regex to generate the dataset.

LLM Chains:
![LLM Chains](https://github.com/lomash-relia/QAPipleline-using-LLMs/blob/main/images/chains.png?raw=true)

Sample Output (without regex):
![Sample](https://github.com/lomash-relia/QAPipleline-using-LLMs/blob/main/images/sample-output.png?raw=true)

## Getting Started

To get started with the QAPipeline using LLMs, follow these steps:

1. Clone this repository to kaggle or your local machine.
2. Open the "qa-llamacpp-pipeline" notebook.
3. Configure notebook environment and input pdf.
4. Run the notebook cells to execute the tasks and generate summaries, questions, and answers.

## Acknowledgments

- This project utilized the compute power generously provided by Kaggle and open large language models available on huggingface using llamacpp.