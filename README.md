# Travel Tide: Customer Segmentation

## Project Overview
This project focuses on customer segmentation for **Travel Tide**, aiming to analyze customer behavior using data-driven methods and derive targeted marketing and incentive strategies. Through **Exploratory Data Analysis (EDA)**, **Feature Engineering**, **PCA**, and **K-Means Clustering**, distinct customer segments are identified to support improved customer engagement and retention.

---

## Objectives
- Analyze user behavior and booking patterns  
- Clean and preprocess raw CSV data  
- Identify relevant customer features  
- Reduce dimensionality using Principal Component Analysis (PCA)  
- Determine the optimal number of clusters using the Silhouette Score  
- Segment customers with K-Means clustering  
- Interpret customer segments and derive business recommendations (e.g., bonuses and discount perks)

---

## Data Sources
The project is based on multiple CSV files containing information such as:
- **User data** (demographics, activity)
- **Session data** (platform usage behavior)
- **Trip and booking data** (travel history, cancellations, hotel nights)

### Data Preparation Steps
- Conversion of date formats  
- Cleaning of implausible values (e.g., negative hotel nights)  
- Outlier handling and value clipping  
- Identification and separate handling of canceled trips  

---

## Methodology & Workflow
The Jupyter Notebook follows a clear, modular structure:

### 1. EDA & Preprocessing
- Initial data exploration  
- Data cleaning and outlier handling  
- Export of cleaned datasets  

### 2. Canceled Trip Detection
- Separation of canceled and completed trips  
- Export of relevant subsets  

### 3. Feature Engineering
- Creation of new features from session, trip, and user data  
- Aggregations and transformation-based features  

### 4. PCA (Principal Component Analysis)
- Handling of non-numeric and missing values  
- Feature scaling  
- Dimensionality reduction  

### 5. Silhouette Score Analysis
- Determination of the optimal number of clusters  
- Evaluation of cluster quality  

### 6. K-Means Clustering
- Training of the clustering model  
- Assignment of customers to segments  

### 7. Cluster Analysis & Interpretation
- Merging of all relevant features  
- Exploratory analysis of final customer segments  
- Manual interpretation and business insights  

---

## Technology Stack
- **Python 3**
- **Jupyter Notebook**
- **Pandas & NumPy** – data processing  
- **Matplotlib & Seaborn** – data visualization  
- **Scikit-learn** – PCA, K-Means, Silhouette Score  

---

## Results
- Identification of clearly distinguishable customer segments  
- Transparent cluster structure visualized via PCA  
- Solid foundation for personalized marketing initiatives  
- Export of a final customer segmentation dataset  

---

## How to Run the Project
1. Clone the repository or download the notebook  
2. Install required dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
