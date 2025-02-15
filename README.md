
### Anti-Money Laundering Using Anomaly Detection

Anti-money laundering (AML) involves identifying and preventing the concealment of illegally obtained funds. In this project, we’ll use a historical transaction dataset to train anomaly detection models that identify outliers, which could indicate suspicious activity.

While the dataset includes a column (`SAR`) that flags actual frauds, we’ll intentionally ignore this information. This approach reflects real-world scenarios where money laundering often goes undetected, making anomaly detection a critical tool for uncovering such activities.

Finally, we’ll evaluate the effectiveness of our anomaly detection models using a small subset of labeled data.

---

### Problem Type
Anomaly Detection – Outlier Detection

### Unsupervised Learning with DataRobot

DataRobot is highly effective at identifying patterns in datasets where a target feature is unavailable. This is known as **unsupervised modeling** in machine learning. DataRobot offers two primary modes for unsupervised learning:

1. **Outlier Detection**: Identifies unusual data points that deviate significantly from the majority of the dataset.
2. **Time Series Anomaly Detection**: Detects anomalies in time-ordered data, such as unexpected spikes or drops.

The choice between these modes depends on the specific use case and the nature of the data. Both approaches are powerful tools for uncovering hidden insights in the absence of labeled outcomes.
