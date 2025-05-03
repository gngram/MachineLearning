## Stage 1: Foundations (Week 1–2)

### Goal: Understand the basics without math overload

#### What is Machine Learning?

**Types:** Supervised, Unsupervised, Reinforcement

**Use cases:** spam filtering, recommendation systems, etc.

**Watch:** “Machine Learning for Everyone” (YouTube - freeCodeCamp / StatQuest)

**Read:** Google's ML Crash Course (Intro sections)

#### Basic Python for ML

Lists, loops, functions, NumPy, pandas
Practice: Kaggle’s Python course



# Stage 2: Core Machine Learning Algorithms (Weeks 3–5)

**Goal**: Learn how basic machine learning models work, what problems they solve, and how to apply them using Python and scikit-learn.

---

## 1. 🔢 Linear Regression – *Predicting Numbers*

**Use case**: Predict a continuous value (like house prices, temperatures, salaries)

- **Concept**: Draw a straight line that best fits the data points.
- **Idea**: If you know the size of a house, you can estimate its price.
- **Tools**:
  - `LinearRegression` from `sklearn.linear_model`
  - `matplotlib` to visualize line fit
- **What to Learn**:
  - What are *features* (inputs) and *labels* (outputs)?
  - How to evaluate model accuracy using Mean Squared Error (MSE)
- ✅ **Mini Project**: Predict house prices using features like number of rooms, location, etc.

---

## 2. ✔️ Logistic Regression – *Binary Classification*

**Use case**: Predict categories like yes/no, spam/ham, pass/fail

- **Concept**: Instead of fitting a line, fit a curve (sigmoid) that outputs probabilities.
- **Idea**: Will a student pass based on study hours?
- **Tools**:
  - `LogisticRegression` from `sklearn.linear_model`
- **What to Learn**:
  - What is a sigmoid curve and probability threshold (usually 0.5)
  - How to evaluate using *accuracy*, *confusion matrix*, *precision* and *recall*
- ✅ **Mini Project**: Predict if an email is spam based on words used

---

## 3. 🌳 Decision Trees & Random Forests – *Tree-Based Models*

**Use case**: Models that make decisions like a flowchart

- **Concept**: If-else rules like “If age > 18 and income > 50k → loan approved”
- **Random Forest**: Combines many trees for better accuracy and stability
- **Tools**:
  - `DecisionTreeClassifier`, `RandomForestClassifier` from `sklearn.tree` and `sklearn.ensemble`
- **What to Learn**:
  - Overfitting and how Random Forest reduces it
  - Visualizing trees with `plot_tree()`
- ✅ **Mini Project**: Predict if someone survived the Titanic based on age, gender, class, etc. (Kaggle Titanic dataset)

---

## 4. 👥 K-Nearest Neighbors (KNN) – *Lazy Learning*

**Use case**: Find similar examples to make decisions

- **Concept**: Look at the 'K' closest neighbors to classify a new point
- **Idea**: If your 5 closest neighbors like cricket, maybe you do too!
- **Tools**:
  - `KNeighborsClassifier` from `sklearn.neighbors`
- **What to Learn**:
  - Distance metrics (Euclidean), how K affects results
  - Visualization of decision boundaries
- ✅ **Mini Project**: Classify types of flowers (Iris dataset)

---

## 🛠️ Learning Approach

- Use **Jupyter notebooks** or **Google Colab** for interactive practice
- Use **visuals and storytelling**: imagine you’re teaching a child how a model works
- Use small datasets like:
  - `sklearn.datasets.load_iris()`
  - `load_digits()`
  - Kaggle’s Titanic or House Price datasets
