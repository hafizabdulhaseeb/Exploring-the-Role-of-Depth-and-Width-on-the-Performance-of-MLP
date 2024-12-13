# Exploring the Role of Depth and Width on the Performance of MLP

The novelty of this project closely relates to how architectural parameters, especially depth and width—the number of hidden layers and neurons per layer, respectively—impact the performance, learning capabilities, and generalization capacity of Multi-Layer Perceptrons (MLPs). Employing a systematic experimental design, the study examines the chosen space of model complexity and its relation to performance to guide the process of building efficient neural networks.

## Project Objectives
- To compare the suitability of the model when depth, which is the number of hidden layers, is increased or decreased.
- To observe the effects of varying the number of neurons per layer (width) on learning ability and the risk of overfitting.
- To derive general principles regarding the architecture of MLP networks for binary classification tasks.

## Methodology
### Dataset
Artificial binary classification data was created using the `make_classification` tool from the scikit-learn library. The dataset consists of:
- **Samples**: A dataset of 1000 samples, each with 20 numerical attributes.
- **Features**: Informative features combined with redundant and noisy factors for realism.
- **Train-Test Split**: 
  - Training set: 80% of samples used for training.
  - Testing set: 20% of samples used to investigate generalization performance.

### MLP Architectures
- **Depth Configurations**: 1 to 5 hidden layers.
- **Width Configurations**: 5, 10, 20, 50, and 100 neurons per layer.
- **Total Configurations**: 25 unique depth-width combinations were systematically evaluated.

### Performance Metrics
The models were assessed on:
- Accuracy in classification tasks.
- Efficiency in learning new patterns.
- Ability to generalize to unseen data.
- Risk factors such as overfitting and underfitting.

## Significance
The findings of this project present a logical framework for evaluating and optimizing MLP architectural trade-offs. The insights gained are not restricted to the dataset used in this study and can be applied to other machine learning tasks involving neural networks.

## Contents
- **Code**: Implementations of MLP architectures and training algorithms, written in Python.
- **Data**: Scripts for synthetic dataset generation and preprocessed training/testing datasets.
- **Results**: 
  - Performance evaluation charts.
  - Bar diagrams.
  - Detailed analysis of various architectural configurations.
- **Documentation**: Comprehensive explanations of the research study, experiments, and findings.

## Potential Applications
This project is valuable for:
- **Machine Learning Practitioners**: Those designing neural networks for classification tasks.
- **Researchers**: Interested in both the theoretical and practical considerations of MLP architectures.
- **Educators**: Looking for examples of depth-width trade-offs in neural networks.


## How to Use This Repository

### Clone the Repository
Open a terminal and run the following command to clone the repository to your local machine:

```bash
git clone https://github.com/your-username/your-repo-name.git


---
