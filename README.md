# K-Nearest Neighbors (KNN) with Streamlit - Fruit Classification
### App Link
- https://knn-fruit-classification.streamlit.app/
---
### What is K-Nearest Neighbors (KNN)?
- KNN is a **machine learning algorithm** that finds the **closest data points** to make a decision.
- **Real-Life Example:** If you're new in school, you’ll likely make friends with students **sitting near you**. Similarly, KNN also looks at **nearest neighbors** to make a decision.
- KNN is called a **lazy algorithm** because it **doesn’t learn until asked**.
- KNN works well with **small datasets**.
- KNN is easy to understand and is **based on distance**.
---
### Required Python Packages
- **`scikit-learn`** - To build machine learning models
- **`streamlit`** - To build data apps
- **`pandas`** - To work with the dataset
---
### Example Problem
- Classify **Fruit** Based on **Size** and **Weight**
- We have data about **Fruit Size**, **Weight**, and the **Type of Fruit** (Apple or Orange).

| Size | Weight | Fruit  |
| ---- | ------ | ------ |
| 7    | 150    | Apple  |
| 6    | 140    | Apple  |
| 5    | 130    | Apple  |
| 9    | 180    | Orange |
| 10   | 200    | Orange |

---
### How It Works
- KNN finds the **3 closest neighbors** to the input.
- It looks at their **labels** (Apple or Orange).
- The **majority wins** and becomes the prediction.
---
