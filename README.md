# TASK--8
# K-Means Clustering - Customer Segmentation

##  Objective
To apply **K-Means clustering** for unsupervised learning on a customer segmentation dataset (Mall Customers) and identify natural groupings in customer behavior.

---

##  Tools & Libraries
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
---

##  Dataset
- **Mall Customers Dataset**  
---

## Steps Performed
1. **Load and preprocess the data**
   - Selected relevant features: `Annual Income` and `Spending Score`.
   - Standardized the dataset.
2. **Elbow Method**
   - Used to determine the optimal number of clusters `K`.
3. **K-Means Clustering**
   - Applied clustering algorithm with optimal `K`.
   - Assigned cluster labels.
4. **Visualization**
   - Scatter plot to show customer segments.
5. **Evaluation**
   - Computed **Silhouette Score** to evaluate clustering performance.

---

## Output
- Elbow plot to identify the best `K`
- Clustered scatter plot of customer segments
- Silhouette Score for cluster quality
