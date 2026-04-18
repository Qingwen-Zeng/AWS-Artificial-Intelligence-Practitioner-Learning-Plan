\documentclass[11pt, a4paper]{article}

\usepackage[utf8]{inputenc}
\usepackage[T1]{fontenc}
\usepackage[margin=2.5cm]{geometry}
\usepackage{hyperref}

\hypersetup{colorlinks=true, linkcolor=black, urlcolor=blue}

\title{\textbf{AWS Artificial Intelligence Practitioner} \\ Learning Plan}
\author{}
\date{}

\begin{document}

\maketitle
\tableofcontents
\newpage

\section{Fundamentals of Machine Learning and Artificial Intelligence}

\subsection{Machine Learning Fundamentals}

\subsubsection{Training Data}

\paragraph{Labeled Data}
A dataset where each instance is accompanied by a \textbf{label} or \textbf{target variable} that represents the desired output or classification. These labels are typically provided by human experts or obtained through a reliable process.

\textit{Example: In an image classification task, labeled data would consist of images along with their corresponding class labels (e.g., cat, dog, car).}

\paragraph{Unlabeled Data}
A dataset where the instances do not have any associated labels or target variables. The data consists only of input features, without any corresponding output or classification.

\textit{Example: A collection of images without any labels or annotations.}

\subsubsection{Learning Paradigms}

\paragraph{Supervised Learning}
A type of ML where the model is trained on labeled data. The algorithm learns a mapping from inputs to outputs by minimizing the error between predicted and actual labels.

\textit{Example: Predicting house prices based on features like square footage, number of bedrooms, and location.}

\paragraph{Unsupervised Learning}
A type of ML where the model is trained on unlabeled data. The algorithm discovers hidden patterns, groupings, or structures without explicit guidance.

\textit{Example: Clustering customers into segments based on purchasing behavior.}

\paragraph{Reinforcement Learning}
A type of ML where an agent learns by interacting with an environment, receiving rewards or penalties. It learns a policy that maximizes cumulative reward over time.

\textit{Example: Training a robot to navigate a maze by rewarding it for reaching the exit.}

\subsubsection{Model Evaluation}

\paragraph{Overfitting}
When a model learns the training data too well, including noise and outliers, resulting in poor generalization to unseen data.

\textit{Example: A decision tree that memorizes every training sample instead of learning general patterns.}

\paragraph{Underfitting}
When a model is too simple to capture the underlying patterns in the data. It performs poorly on both training and test data.

\textit{Example: Using a linear model to fit highly non-linear data.}

\end{document}