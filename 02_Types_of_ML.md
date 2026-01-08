# # Types of Machine Learning 

 ## 1. On the basis of How is the machine learning model trained ? especially on production.

## (i) Batch (Offline) Learning

- A training approach where the model is trained once on a fixed dataset.
- After training, the model is deployed and used for predictions, but it does not learn continuously from new data unless it is retrained again from scratch (or with an updated dataset).

### How It Works (Step-by-Step)

- Collect a large dataset
- Train the model offline (not in real-time)
- Evaluate or Test the model
- Deploy the trained model
- Use it for predictions
- When new data comes → retrain the model again

<img src="https://github.com/user-attachments/assets/79b870c9-febe-4da6-acdd-bdd098802d73"  width="500" height="600">


### Problem/Disadvantages with Batch Learning 

- Model becomes outdated with new data
- Retraining is time-consuming
- Not suitable for real-time systems
- **Hardware Limitation** : Requires high computational resources.

---

## (ii) Online Learning

- A machine learning approach where the model learns continuously, updating itself step-by-step as new data arrives.


### How It Works (Step-by-Step)

- Model is trained with initial data
- New data arrives (one by one or in small batches)
- Model updates its parameters immediately
- Predictions improve over time
- No need to retrain the model from scratch

<img src="https://github.com/user-attachments/assets/4c76872e-56b6-41df-86a1-9434e1b2514f"  width="500" height="600">


### When to Use ?

- Data arrives continuously
- Dataset is very large or infinite
- Hardware resources are limited
- Real-time prediction is required

---

## Offline (Batch) Learning VS Online Learning

<img src="https://github.com/user-attachments/assets/8c02661d-5596-4b4d-947b-ded9be762452"  width="700" height="800">


--- 


## 2. On the Basis of How our model Learns ?

## (i) Instance-Based Learning

- A type of learning where the model stores training examples and makes predictions by comparing new data points with stored instances, instead of learning an explicit general model.
- It predicts the output of a new instance by finding similar instances in the training data.
- It is also called Lazy Learning because no training phase is required.

### How It Works

- Store all training data
- New data point arrives
- Measure similarity (distance) with stored data
- Predict output based on nearest instances


<img src="https://github.com/user-attachments/assets/d8bd04e7-72ec-4f80-82f2-3dcb9d67336a"  width="500" height="600">

> In this figure K-nearest neighbors (KNN) algorithm is used.  
> ❌ (New Instance) is Triangle  
> - When a new instance appears:  
>   - The algorithm calculates the distance between the new instance and nearby training points.
>   - Finds the nearest neighbors.
>   - The class is decided based on the majority of nearest instances.

---

## (ii) Model-Based Learning

- A machine learning approach where the system learns a mathematical model from training data and then uses that learned model to make predictions on new data.
- A generalized model from data and uses this model for future predictions instead of storing all training examples.
- This involves using algorithms like linear regression, logistic regression, random forest, etc.


### How It Works (Step-by-Step)

- Collect training data
- Choose a model (linear, tree, neural network, etc.)
- Train the model (learn parameters)
- Evaluate performance
- Use the trained model for prediction


<img src="https://github.com/user-attachments/assets/f10d34c2-effa-467e-b89d-b9ac7a6ad60f"  width="500" height="600">

> Model draws a boundary  
> This boundary is the model (mathematical representation).  
> On left Triangles and On right Squares  
> ❌ (New Instance) is Triangle  
> - When a new instance appears:
>   - The model checks which side of the boundary it lies on.
>   - The class is predicted without comparing to all data points.

---

## Intance-Based Learning VS Model-Based Learning


<img src="https://github.com/user-attachments/assets/6c0d254a-83d0-40c3-9346-64d2f17b8300"  width="700" height="800">










