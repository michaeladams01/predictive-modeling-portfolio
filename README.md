# predictive-modeling-portfolio

This repository contains a collection of projects developed as part of the UMGC DATA 640 Predictive Modeling course. The goal of these projects is to explore advanced predictive analytics techniques, compare their performance, and document best practices for model selection and evaluation.

## Projects

The `predictive_modeling` folder includes Jupyter notebooks demonstrating the following techniques:

- **Support Vector Machine (SVM) Classification:** Implementation of a support vector machine classifier using Python libraries (scikit‑learn) to predict synthetic outcomes. The notebook walks through data preprocessing, model training, hyperparameter tuning, and evaluation.
- **Ensemble Models (Random Forest):** A notebook implementing a random forest classifier and a gradient boosting ensemble. The project illustrates the advantages of bagging and boosting methods for improving prediction accuracy.
- **Convolutional Neural Network (CNN):** A deep learning notebook using PyTorch (or TensorFlow) to perform image classification on a small image dataset. This project demonstrates how to design, train, and evaluate a CNN model.
- **Reinforcement Learning Agent:** An exploration of reinforcement learning concepts using a simple environment. The notebook implements a Q‑learning or policy gradient agent, highlighting how agents learn to maximize rewards through trial and error.
- **AutoML Comparison:** A report comparing the performance of hand‑built models with automated machine learning (AutoML) output from SAS Enterprise Miner or an open‑source AutoML library. The analysis discusses when automated model selection can be helpful and how to interpret AutoML results.

## Dataset

Each notebook uses either publicly available datasets (e.g., the UCI repository) or synthetic data generated to illustrate the technique. For the CNN project, a small set of labeled images (such as CIFAR‑10 or MNIST) is included. Synthetic tabular data is generated for the SVM, ensemble, and reinforcement learning examples to focus on the modeling process rather than data acquisition.

## Methods & Libraries

The projects use a variety of open‑source libraries to implement predictive modeling techniques:

- **scikit‑learn:** For regression, SVM, random forest, boosting, and general model evaluation.
- **PyTorch/TensorFlow:** For deep learning models such as convolutional neural networks.
- **OpenAI Gym or custom environments:** For reinforcement learning experiments.
- **Matplotlib/Seaborn:** For visualizing data distributions and model performance metrics.

The notebooks include detailed comments and explanations to guide the reader through data preparation, model training, hyperparameter tuning, and performance evaluation. Emphasis is placed on comparing models and discussing the strengths and weaknesses of each approach in line with the course objectives.

## Results & Insights

Through these projects, I gained practical experience using advanced predictive analytics tools to build, assess, and compare models. Key takeaways include:

- Model performance can vary widely depending on data preparation and hyperparameter choices. Systematic model evaluation and cross‑validation are essential.
- Ensemble methods such as random forests and gradient boosting often outperform single models, especially on complex datasets.
- Deep learning models like CNNs can achieve high accuracy on image data but require careful tuning and significant computational resources.
- Reinforcement learning provides a framework for sequential decision‑making problems, and simple agents can learn effective strategies with enough exploration.
- AutoML tools can quickly generate baseline models and are useful for rapid prototyping, but understanding the underlying algorithms is important for interpreting results and making informed model choices.

Feel free to explore the notebooks and modify them for your own datasets or research questions. Feedback and contributions are welcome!
