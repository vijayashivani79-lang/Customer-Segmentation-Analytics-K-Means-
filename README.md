# Customer Segmentation Analytics using K-Means Clustering

## 📌 Overview

Customer Segmentation Analytics is an unsupervised machine learning project that groups customers based on their **demographic characteristics and purchasing behaviour**.

The project uses **K-Means Clustering** to identify distinct customer segments and uncover patterns that can support data-driven marketing strategies, customer targeting, and business decision-making.

---

## 🎯 Objectives

* Segment customers based on purchasing behaviour and demographics.
* Explore customer spending patterns using Exploratory Data Analysis (EDA).
* Identify meaningful customer groups using unsupervised machine learning.
* Determine the optimal number of clusters using the **Elbow Method**.
* Visualise and interpret customer segments.
* Identify high-value, low-spending, and behaviourally distinct customer groups.

---

## 🛠️ Technologies Used

| Technology           | Purpose                                  |
| -------------------- | ---------------------------------------- |
| **Python**           | Programming and data analysis            |
| **Pandas**           | Data manipulation and preprocessing      |
| **NumPy**            | Numerical operations                     |
| **Scikit-learn**     | K-Means clustering and ML implementation |
| **Matplotlib**       | Data visualisation                       |
| **Seaborn**          | Statistical visualisation                |
| **Jupyter Notebook** | Development and analysis environment     |

---

## 📂 Project Structure

```text
Customer-Segmentation-Analytics/
│
├── Customer_Segmentation.ipynb
├── Mall_Customers.csv
├── README.md
└── requirements.txt
```

> Update the filenames above if your actual repository uses different names.

---

## 📊 Dataset

The project uses a customer dataset containing information related to:

* Customer ID
* Gender
* Age
* Annual Income
* Spending Score

These attributes are explored to understand customer demographics and purchasing behaviour.

---

## 🔍 Project Workflow

### 1. Data Collection

The customer dataset is loaded into Python using Pandas.

### 2. Data Cleaning & Preprocessing

The dataset is inspected for:

* Missing values
* Duplicate records
* Incorrect data types
* Inconsistent values

Relevant features are selected for the clustering process.

### 3. Exploratory Data Analysis

EDA is performed to understand relationships and distributions within the dataset.

Visualisations are created to analyse:

* Age distribution
* Income distribution
* Spending behaviour
* Gender distribution
* Income vs. Spending Score

### 4. Feature Selection

Relevant numerical features are selected for customer segmentation.

The primary clustering features include:

* Annual Income
* Spending Score

Additional demographic attributes are analysed to interpret the resulting clusters.

### 5. K-Means Clustering

K-Means clustering is implemented using **Scikit-learn**.

The algorithm groups customers into clusters based on similarity in their purchasing characteristics.

### 6. Selecting the Optimal Number of Clusters

The **Elbow Method** is used to determine an appropriate number of clusters.

The Within-Cluster Sum of Squares (WCSS) is calculated for different values of `K`, and the point where the reduction in WCSS begins to slow down is used to identify a suitable cluster count.

### 7. Visualisation

Matplotlib and Seaborn are used to visualise the customer segments and make the results easier to interpret.

### 8. Cluster Interpretation

Each cluster is analysed based on its characteristics to understand the type of customers it represents.

---

## 📈 Key Customer Segments

The clustering analysis can reveal groups such as:

| Customer Segment                    | Characteristics                                     |
| ----------------------------------- | --------------------------------------------------- |
| 💎 High-Value Customers             | Higher income and higher spending                   |
| 🛍️ Potential Customers             | Higher income with relatively lower spending        |
| 💰 Moderate Customers               | Medium income and spending behaviour                |
| 📉 Low-Spending Customers           | Lower spending behaviour                            |
| 🎯 Behaviourally Distinct Customers | Unique combinations of income and spending patterns |

> The exact characteristics of each segment depend on the clustering results obtained from the dataset.

---

## 📊 Visualisations

The project includes visualisations such as:

* Customer demographic distributions
* Annual Income distribution
* Spending Score distribution
* Income vs. Spending Score
* Elbow Method plot
* Customer clusters
* Cluster-wise behavioural analysis

---

## 💡 Business Insights

Customer segmentation can help businesses:

* Identify high-value customer groups.
* Develop targeted marketing campaigns.
* Personalise promotions and offers.
* Identify customers with growth potential.
* Understand differences in purchasing behaviour.
* Improve customer retention strategies.
* Support data-driven marketing decisions.

---

## 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/your-username/customer-segmentation-analytics.git
```

### 2. Navigate to the project directory

```bash
cd customer-segmentation-analytics
```

### 3. Install the required libraries

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 5. Open the notebook

Open:

```text
Customer_Segmentation.ipynb
```

and run the cells sequentially.

---

## 📦 Requirements

Create a `requirements.txt` file containing:

```text
pandas
numpy
scikit-learn
matplotlib
seaborn
jupyter
```

---

## 🧠 Machine Learning Approach

### K-Means Clustering

K-Means is an **unsupervised learning algorithm** that divides data into `K` clusters by assigning each data point to the nearest cluster centroid.

The objective is to minimise the within-cluster variation:

```text
WCSS = Σ ||xᵢ - μⱼ||²
```

where:

* `xᵢ` = data point
* `μⱼ` = centroid of the assigned cluster
* `WCSS` = Within-Cluster Sum of Squares

The **Elbow Method** is used to help determine a suitable value of `K`.

---

## 📌 Results

The final clustering model successfully groups customers into behaviourally distinct segments based on their income and spending patterns.

The resulting clusters provide an interpretable view of customer behaviour and demonstrate how **unsupervised machine learning can be applied to customer analytics and marketing segmentation**.

---

## 🔮 Future Enhancements

* Compare K-Means with **K-Medoids and Hierarchical Clustering**.
* Apply feature scaling and evaluate its effect on clustering.
* Use **Silhouette Score** and other clustering evaluation metrics.
* Build an interactive **Power BI or Streamlit dashboard**.
* Add customer lifetime value analysis.
* Develop a recommendation system for personalised offers.
* Automate customer segmentation for new customer data.

---

## 👩‍💻 Author

**B. Vijaya Shivani**

Computer Science & Engineering — AI & ML

### Skills Demonstrated

`Python` `Data Analytics` `Machine Learning` `Pandas` `NumPy` `Scikit-learn` `Matplotlib` `Seaborn` `EDA` `K-Means Clustering`

---

## ⭐ Project Highlights

> **An end-to-end customer analytics project demonstrating data preprocessing, exploratory data analysis, unsupervised machine learning, visualisation, and business-oriented interpretation of customer segments.**
