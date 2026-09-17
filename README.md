# unsupervised-reinforcement-learning
# Unsupervised and Reinforcement Learning

This repository contains a Google Colab practical demonstrating **Unsupervised Learning** and **Reinforcement Learning** using simple business examples.

## 📌 Project Overview

The notebook covers two main concepts:

1. **Customer Segmentation using K-Means Clustering**
2. **Introduction to Reinforcement Learning using a Delivery Route Example**

The practical focuses on understanding the business meaning of machine learning outputs rather than memorizing Python code.

## 🧠 Part A: Customer Segmentation Using K-Means

An online retailer wants to identify different types of customers based on:

* Monthly Spending
* App Visits

The notebook uses **K-Means Clustering** with `K = 3` to divide customers into three groups.

### Technologies Used

* Python
* Pandas
* Scikit-learn
* Matplotlib
* Google Colab

### Key Concepts

* Unsupervised Learning
* Clustering
* K-Means
* Customer Segmentation
* Business Interpretation
* Data Visualization

The clusters can be interpreted from a business perspective, such as:

* Premium Customers
* Medium-Value Customers
* Low-Engagement Customers

Possible business actions include loyalty rewards, personalized recommendations, and re-engagement campaigns.

## 🤖 Part B: Introduction to Reinforcement Learning

The second part introduces Reinforcement Learning through a simple delivery-route scenario.

Two possible routes are compared:

* Route A
* Route B

The system receives rewards based on delivery performance and uses this feedback to understand which route performs better.

### Reinforcement Learning Concepts

| Concept     | Example                       |
| ----------- | ----------------------------- |
| Agent       | Delivery decision system      |
| Environment | Roads and traffic             |
| Action      | Choosing a route              |
| Reward      | Delivery performance feedback |

The notebook also demonstrates:

* **Exploration** — trying different options
* **Exploitation** — choosing the option known to perform better

## 📊 Machine Learning Comparison

| Machine Learning Type  | Main Idea                      | Business Example          |
| ---------------------- | ------------------------------ | ------------------------- |
| Supervised Learning    | Learn from known answers       | Customer churn prediction |
| Unsupervised Learning  | Discover hidden patterns       | Customer segmentation     |
| Reinforcement Learning | Learn from actions and rewards | Route optimization        |

## 📁 Repository Structure

```text
Unsupervised-and-Reinforcement-Learning/
│
├── part-a/
│   └── unsupervised-learning/
│       └── Unsupervised_and_Reinforcement_Learning_Practical_Name.ipynb
│
├── screenshots/
│   └── customer-segmentation.png
│
└── README.md
```

## 🎯 Learning Outcomes

After completing this practical, you should understand:

* What Unsupervised Learning is
* How clustering works
* What K-Means does
* How customer segmentation can support business decisions
* The basic idea of Reinforcement Learning
* Agent, Action, Environment, and Reward
* Exploration vs Exploitation

## 🚀 How to Run

1. Open the `.ipynb` file in **Google Colab** or Jupyter Notebook.
2. Install the required Python libraries if necessary.
3. Run the notebook cells sequentially.
4. Observe the generated customer clusters and Reinforcement Learning examples.

## 👤 Author

**Your Name**

This project was created as part of a Machine Learning / Artificial Intelligence practical.
