# srd2plantUml_Salesforce_codet5-base

## Overview
This project fine-tunes Salesforce's CodeT5 model on a custom dataset to generate PlantUML source code from Software Requirements Documents (SRD). The model is specialized in generating use case, class, and sequence diagrams directly from SRD inputs.

## Features
- **CodeT5 Fine-Tuning**: Trained on SRD to PlantUML mappings for use case, class, and sequence diagrams.
- **Automated UML Generation**: Generates PlantUML diagrams that visualize system design and architecture based on SRD content.
- **Model Only**: This repository includes only the final fine-tuned model; the training dataset is excluded for data privacy and storage efficiency.

## Model Details
The fine-tuned CodeT5 model translates SRD inputs into PlantUML syntax for:
- **Use Case Diagrams**
- **Class Diagrams**
- **Sequence Diagrams**

## Getting Started

### Prerequisites
- **Transformers Library**: Install the Hugging Face Transformers library for loading the CodeT5 model.
  ```bash
  pip install transformers
