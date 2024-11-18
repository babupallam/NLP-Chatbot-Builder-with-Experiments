# NLP Chatbot Development Project

## Overview

This repository contains the code, documentation, and resources related to an NLP-based chatbot development project. The project aims to build an intelligent conversational agent using different neural network architectures including RNN, CNN, MLP, and Transformer-based models. The chatbot is developed in Python, and the implementation is documented using Jupyter notebooks.

### Key Objectives:
- Develop a chatbot that can carry out effective conversations using advanced neural network models.
- Experiment with different architectures and techniques, such as transfer learning and hyperparameter tuning.
- Integrate business-specific data to demonstrate practical use cases.

## Repository Structure

The repository is organized into the following directories:

### 1. Notebooks

This directory contains Jupyter notebooks for different stages of the project:
- `00_Baseline_Chatbot.ipynb`: Baseline model implementation.
- `00_data_download_and_save.ipynb`: Download and save data for the chatbot.
- `01_Data_Preprocessing.ipynb`: Data preprocessing tasks.
- `02_RNN_Hyperparameter_Tuning.ipynb`: Hyperparameter tuning for the RNN model.
- `03_Alternative_Network_Architectures_CNN.ipynb`: Implementing and testing the CNN architecture.
- `04_Alternative_Network_Architectures_MLP.ipynb`: Implementing and testing the MLP architecture.
- `05_Non_AI_Baseline_Chatbots.ipynb`: Implementation of a simple, non-AI chatbot.
- `06_Alternative_Datasets_Persona_Chat.ipynb`: Using an alternative dataset like Persona Chat for training.
- `07_Transformer_Encoder_Decoder_Chatbot.ipynb`: Transformer-based encoder-decoder chatbot.
- `08_Transfer_Learning_Used_Chatbot.ipynb`: Utilizing transfer learning for improving the chatbot.
- `09_Comparison_of_Different_Approaches.ipynb`: Comparison of the different approaches used for chatbot development.

### 2. `src/`

Contains source code for key components of the project:
- `data_processing.py`: Functions for cleaning and preparing data.
- `model_architectures.py`: Implementations of various neural network architectures.
- `hyperparameter_tuner.py`: Utility functions for hyperparameter tuning.
- `utils.py`: Utility functions, including BLEU score and cosine similarity calculations.

### 3. `data/`

Stores the datasets used for training and testing:
- `cornell_movie_dialogs/`: Cornell Movie-Dialogs dataset.
- `dailydialog/`: DailyDialog dataset.
- `custom_business_data/`: Custom datasets for business-specific cases.
- `processed/`: Contains pre-processed versions of the above datasets.

### 4. `results/`

Stores results and observations from different experiments:
- `figures/`: Graphs and visualizations generated during the experiments.
- `hyperparameter_logs/`: Logs and outputs generated during hyperparameter tuning.
- `observations.txt`: Summary of key findings and observations from the experiments.

### 5. `report/`

Contains the final project report and related documents:
- `NLP_Coursework_Report.pdf`: The final report for the coursework.
- `NLP_Coursework_Report.tex`: The LaTeX source of the report.
- `NLP_Coursework_Report_Latex.zip`: Zip file containing all LaTeX source files for the report.

### 6. `presentation/`

Contains the presentation files for the coursework:
- `chatbot_presentation.pdf`: The presentation used for demonstrating the project.
- `chatbot_presentation_Latex.zip`: LaTeX source files for generating the presentation.

## Requirements

To run the code in this repository, you need to install the dependencies listed in `requirements.txt`:

```
torch
numpy
pandas
scikit-learn
matplotlib
```

Install the requirements using:

```
pip install -r requirements.txt
```

## Getting Started

1. Clone this repository to your local machine:
   ```
   git clone <repository_url>
   ```

2. Navigate to the project directory and install the dependencies.

3. Start Jupyter Notebook to explore the notebooks:
   ```
   jupyter notebook
   ```

4. Begin with the baseline model (`00_Baseline_Chatbot.ipynb`) and progress through the other notebooks to experiment with different techniques.

## How to Use This Repository

- **Baseline Implementation**: Start by understanding the `00_Baseline_Chatbot.ipynb` to see the fundamental chatbot implementation.
- **Model Experiments**: Explore how CNN, MLP, and Transformer models were integrated (`03`, `04`, `07` notebooks).
- **Hyperparameter Tuning**: Use `02_RNN_Hyperparameter_Tuning.ipynb` to see how model performance was optimized.
- **Transfer Learning**: The `08_Transfer_Learning_Used_Chatbot.ipynb` notebook uses transfer learning to enhance chatbot capabilities.
- **Compare Approaches**: Finally, check `09_Comparison_of_Different_Approaches.ipynb` for a detailed comparison of all methods.

## Contributions

If you would like to contribute to this project, feel free to fork the repository, create a new branch, and submit a pull request. Any contributions, whether code, documentation, or improvements, are welcome.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Contact
