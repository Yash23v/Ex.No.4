# Ex.No.4-EXP 4 Generate the Prompt and evaluate that for following prompt patterns - Zero-shot Prompting.•	Few-shot Prompting - Chain of Thought -	Persona Pattern - Reverse Prompting - Graph Prompting - Active Prompting
### DATE: 28-08-2026
### REGISTER NUMBER : 212225040498
### Aim: To write the prompt for the following prompt types and compare that with different AI tools and evaluate that using any one evaluation method (Ex. Rubrics). 
Zero-shot Prompting
Few-shot Promptingt
Chain of Thought
Persona Pattern
Reverse Prompting
Graph Prompting
Active Prompting 

## Objective:
1.To understand different prompt engineering techniques.
2.To design effective prompts for a given task.
3.To observe how the response changes based on the prompting technique.
4.To compare the quality, accuracy, relevance, and clarity of generated responses.

## Requirements:
1.Generative AI tool such as ChatGPT
2.Internet connection
3.Computer/laptop
4.A common problem/task for testing all prompting techniques

## Procedure:
A common task is selected and prompts are designed using seven prompting techniques: Zero-shot, Few-shot, Chain-of-Thought, Persona, Reverse, Graph, and Active Prompting. Each prompt is given separately to a Generative AI tool, and the corresponding outputs are recorded. The generated responses are evaluated based on accuracy, relevance, clarity, completeness, and overall quality. Finally, the results are compared to determine the effectiveness of each prompting technique.

## Task:
Explain the concept of Machine Learning to a college student.
Give the AI the task directly without examples.

## Zero-Shot Prompting:
### Prompt:
Explain Machine Learning in simple terms suitable for a college student. Give its definition, types, applications, advantages, and limitations.
### Output:
Machine Learning (ML) is a branch of Artificial Intelligence that enables computers to learn from data and make predictions or decisions without being explicitly programmed for every task.

Types of Machine Learning:

Supervised Learning – The model learns from labeled data. Example: predicting house prices. Unsupervised Learning – The model finds patterns in data without labeled answers. Example: customer segmentation. Reinforcement Learning – The model learns by interacting with an environment and receiving rewards or penalties. Example: game-playing AI.

Working Process: Data is collected and prepared before being given to a machine learning algorithm. The algorithm identifies patterns in the training data and creates a model. The model is then tested using new data to make predictions or decisions.

Applications: Machine Learning is used in healthcare, banking, recommendation systems, fraud detection, speech recognition, and autonomous vehicles.

Advantages: It can automate tasks, identify complex patterns, make predictions, and improve with more data.

Limitations: It requires quality data, can be computationally expensive, and may produce biased results if the training data is biased.

## Few-shot Prompting:
### Prompt:
Example 1: Topic: Artificial Intelligence Explanation: Artificial Intelligence is the ability of machines to perform tasks that normally require human intelligence
Example 2: Topic: Deep Learning Explanation: Deep Learning is a subset of Machine Learning that uses neural networks with multiple layers.
Now explain Machine Learning in the same style. Include its definition, types, applications, advantages, and limitations.

### Output:
Topic: Machine Learning

Explanation: Machine Learning is a subset of Artificial Intelligence that allows computers to learn patterns from data and make predictions or decisions without being explicitly programmed for every situation.

Types:
Supervised Learning: Learns from labeled data. Unsupervised Learning: Identifies patterns in unlabeled data. Reinforcement Learning: Learns through rewards and penalties.
Working: Machine Learning systems collect data, preprocess it, train a model using an algorithm, and use the trained model to make predictions on new data.
Applications: It is widely used in recommendation systems, healthcare, finance, image recognition, spam detection, and autonomous systems.
Advantages: It automates decision-making, identifies patterns, and can improve its performance with suitable data.
Limitations: It depends heavily on data quality, can be computationally demanding, and may produce inaccurate or biased results.

## Chain-of-Thought Prompting:
### Prompt:
Explain Machine Learning to a college student. Break the explanation into logical steps, starting from its basic concept, then explain how it works, its types, applications, advantages, and limitations. Provide the reasoning in a structured step-by-step manner.

### Output:
Step 1 – Understand the Basic Concept
Machine Learning is a technology that allows computers to learn from examples and data instead of being explicitly programmed for every possible situation.
Step 2 – Understand the Input
A Machine Learning system requires data. For example, a system designed to identify spam emails can be trained using previously identified spam and non-spam emails.
Step 3 – Train the Model
A Machine Learning algorithm analyzes the training data and identifies patterns. These patterns are used to create a trained model.
Step 4 – Test the Model
The trained model is given new data that it has not seen before. Its predictions are evaluated to determine its performance.
Step 5 – Identify the Types
The major types are supervised learning, unsupervised learning, and reinforcement learning.
Step 6 – Understand Applications
Machine Learning is used for recommendation systems, medical diagnosis support, fraud detection, image recognition, and voice assistants.
Step 7 – Advantages and Limitations
It can automate complex tasks and identify patterns efficiently. However, it requires appropriate data and may produce poor results when the training data is insufficient or biased.

## Persona Pattern Prompting:
### Prompt:
Act as an experienced college professor teaching an introductory Artificial Intelligence course. Explain Machine Learning to first-year college students using simple language and practical examples. Cover its definition, working, types, applications, advantages, and limitations.

### Output:
Professor's Explanation:
Imagine that you are teaching a computer how to recognize whether an email is spam. Instead of writing rules for every possible spam email, you give the computer many examples of spam and normal emails. The computer learns patterns from these examples. This is the basic idea behind Machine Learning.

Definition
Machine Learning is a branch of Artificial Intelligence in which computers learn patterns from data and use those patterns to make predictions or decisions.

How does it work?

The process generally involves:
Collecting data. Cleaning and preparing the data. Training a Machine Learning model. Testing the model. Using the model to make predictions. Types Supervised Learning: Learning using labeled examples. Unsupervised Learning: Finding hidden patterns in data. Reinforcement Learning: Learning through rewards and penalties. Applications

Machine Learning is used in Google search, online recommendations, healthcare, banking, cybersecurity, and speech recognition.

Advantages
It can automate repetitive tasks, identify patterns, and make predictions from large datasets.

Limitations
It needs good-quality data and sufficient computing resources. Incorrect or biased training data can result in incorrect predictions.
In simple words: Machine Learning means teaching computers to learn from data and improve their decisions based on what they have learned.

## Reverse Prompting:
### Prompt:
I want to learn Machine Learning as a college student. First, determine what information should be included in an ideal explanation of Machine Learning. Then create an effective prompt that can be used to generate that explanation. Finally, use that prompt to provide the answer.

### Output:
Step 1 – Required Information
An ideal explanation should include:
Definition of Machine Learning Basic working process Major types Practical examples Applications Advantages Limitations Step 2 – Generated Prompt
"Explain Machine Learning to a college student using simple language. Define Machine Learning, explain how it works, describe supervised, unsupervised, and reinforcement learning, provide practical examples, discuss applications, and explain its advantages and limitations."
Step 3 – Generated Answer
Machine Learning is a branch of Artificial Intelligence that enables computers to learn from data and make predictions or decisions without requiring explicit programming for every situation.
For example, a spam detection system can learn from previously classified emails and identify whether a new email is likely to be spam.
The main types are supervised learning, unsupervised learning, and reinforcement learning. Supervised learning uses labeled data, unsupervised learning discovers patterns in unlabeled data, and reinforcement learning learns through rewards and penalties.
Machine Learning is used in healthcare, banking, recommendation systems, image recognition, fraud detection, and autonomous systems.
Its major advantages include automation, pattern recognition, and predictive analysis. Its limitations include dependency on data quality, computational requirements, and the possibility of biased predictions.

##  Graph Prompting:
### Prompt:
Explain Machine Learning using a graph-like structure. Represent the relationships as:
Machine Learning → Types → Supervised, Unsupervised, Reinforcement Machine Learning → Applications → Healthcare, Finance, Education Machine Learning → Process → Data → Training → Model → Prediction
Expand these relationships and explain each concept in simple terms suitable for a college student.

### Output:
Machine Learning – Graph Structure
<img width="562" height="287" alt="image" src="https://github.com/user-attachments/assets/ae3ef855-accd-48fa-85d4-bc09da8c6db4" />

Machine Learning → Types
Supervised Learning: Uses labeled data to learn a relationship between inputs and outputs. Unsupervised Learning: Finds patterns or groups within unlabeled data. Reinforcement Learning: Learns actions by receiving rewards or penalties.

Machine Learning → Process
The process begins with data. The data is used to train a Machine Learning algorithm. Training produces a model, which can then analyze new data and generate a prediction.

Machine Learning → Applications
Healthcare: Disease prediction and medical image analysis. Finance: Fraud detection and risk analysis. Education: Personalized learning and student performance analysis.

This graph shows how the major concepts of Machine Learning are connected.

## Active Prompting:
### Prompt:
I need an explanation of Machine Learning for a college assignment. Before answering, ask me 3 important questions about my required level, answer length, and preferred examples. After I answer, generate the final explanation based on my responses.

### Output:
Questions - What is your educational level and how much technical knowledge do you have? How long should the explanation be? Would you prefer real-world examples, technical examples, or both?
Student's Response - I am a college student with basic technical knowledge. I need approximately 300 words. I prefer both real-world and technical examples. Final AI Output.

Machine Learning
Machine Learning is a branch of Artificial Intelligence that enables computers to learn from data and make predictions or decisions without being explicitly programmed for every situation.
For example, a recommendation system on an online shopping platform analyzes a user's previous searches and purchases to recommend products that the user may be interested in.
Machine Learning generally works by collecting data, preparing the data, training a model, testing the model, and using the trained model to make predictions.

There are three major types of Machine Learning:
Supervised Learning: The model learns from labeled data. For example, a system can learn to identify spam emails from previously labeled emails. Unsupervised Learning: The model finds patterns in data without predefined labels. Customer segmentation is a common example. Reinforcement Learning: The model learns by receiving rewards or penalties for its actions. Game-playing systems are an example.
Machine Learning is used in healthcare, finance, education, cybersecurity, recommendation systems, image recognition, and voice assistants.
The main advantages of Machine Learning are automation, pattern recognition, and predictive analysis. However, it requires good-quality data and may produce inaccurate or biased results when the training data is poor.

## Evaluation:
| Technique        | Accuracy | Relevance | Clarity | Detail | Overall Quality |
| ---------------- | -------: | --------: | ------: | -----: | --------------: |
| Zero-shot        |      4/5 |       4/5 |     4/5 |    3/5 |             4/5 |
| Few-shot         |      4/5 |       5/5 |     5/5 |    4/5 |             5/5 |
| Chain of Thought |      5/5 |       5/5 |     4/5 |    5/5 |             5/5 |
| Persona          |      5/5 |       5/5 |     5/5 |    4/5 |             5/5 |
| Reverse          |      4/5 |       4/5 |     4/5 |    4/5 |             4/5 |
| Graph            |      4/5 |       5/5 |     4/5 |    5/5 |             5/5 |
| Active           |      5/5 |       5/5 |     5/5 |    5/5 |             5/5 |

# Result: 
The various types of Prompts are executed successfully with generated the report.
