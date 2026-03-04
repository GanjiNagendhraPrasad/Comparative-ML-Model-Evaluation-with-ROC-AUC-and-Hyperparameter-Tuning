<h1>Comparative ML Model Evaluation with ROC-AUC and Hyperparameter Tuning</h1>

<p>
This project focuses on building, comparing, and evaluating multiple machine learning
classification models using key performance metrics such as <b>Accuracy</b>,
<b>Confusion Matrix</b>, <b>ROC Curve</b>, and <b>AUC (Area Under the Curve)</b>.
The goal is to identify the most effective classification model for predicting
breast cancer diagnosis.
</p>

<hr>

<h2>🚀 Live Deployment</h2>
<p>
The project is deployed as a web application and can be accessed here:
</p>
<p>
<a href="https://comparative-ml-model-evaluation-with-roc-8s61.onrender.com/" target="_blank">
https://comparative-ml-model-evaluation-with-roc-8s61.onrender.com/
</a>
</p>

<hr>

<h2>📌 Project Objectives</h2>
<ul>
  <li>Train and evaluate multiple machine learning classification models</li>
  <li>Compare model performance using ROC curves and AUC scores</li>
  <li>Understand strengths and weaknesses of different ML algorithms</li>
  <li>Demonstrate best practices in model evaluation and comparison</li>
  <li>Deploy the trained model using a web-based interface</li>
</ul>

<hr>

<h2>📊 Dataset Description</h2>
<p>
The project uses the <b>Breast Cancer Dataset</b>, which contains medical measurements
of cell nuclei derived from breast cancer biopsies.
</p>

<ul>
  <li><b>Target Variable:</b> Diagnosis (Malignant or Benign)</li>
  <li><b>Label Encoding:</b>
    <ul>
      <li>Malignant (M) → 0</li>
      <li>Benign (B) → 1</li>
    </ul>
  </li>
</ul>

<p>
Unnecessary columns such as ID values are removed, and the dataset is prepared for
machine learning classification tasks.
</p>

<hr>

<h2>🧠 Machine Learning Models Used</h2>
<p>
The following classification models are implemented and evaluated:
</p>

<ul>
  <li>K-Nearest Neighbors (KNN)</li>
  <li>Naive Bayes (GaussianNB)</li>
  <li>Logistic Regression</li>
  <li>Decision Tree Classifier</li>
  <li>Random Forest Classifier</li>
  <li>AdaBoost Classifier</li>
  <li>Gradient Boosting Classifier</li>
  <li>XGBoost Classifier</li>
  <li>Support Vector Machine (SVM)</li>
</ul>

<p>
Each model is trained using the same train-test split to ensure fair comparison.
</p>

<hr>

<h2>📈 Model Evaluation Metrics</h2>

<h3>1. Confusion Matrix</h3>
<p>
Displays the number of true positives, true negatives, false positives,
and false negatives, helping to understand classification errors.
</p>

<h3>2. Accuracy Score</h3>
<p>
Measures the proportion of correct predictions made by the model.
</p>

<h3>3. Classification Report</h3>
<p>
Provides detailed metrics including precision, recall, F1-score,
and support for each class.
</p>

<h3>4. ROC Curve</h3>
<p>
The Receiver Operating Characteristic (ROC) curve plots the True Positive Rate
against the False Positive Rate at various threshold values.
</p>

<h3>5. AUC (Area Under the Curve)</h3>
<p>
AUC summarizes the ROC curve into a single value.
Higher AUC indicates better model performance in distinguishing between classes.
</p>

<hr>

<h2>🔍 Hyperparameter Tuning</h2>
<p>
Although default parameters are initially used, the project structure allows
easy integration of hyperparameter tuning techniques such as:
</p>

<ul>
  <li>GridSearchCV</li>
  <li>RandomizedSearchCV</li>
</ul>

<p>
Hyperparameter tuning helps improve model accuracy and robustness by
optimizing learning parameters.
</p>

<hr>

<h2>🌐 Web Application Deployment</h2>
<p>
The trained model is deployed using a Flask-based web application
and hosted on the Render platform.
</p>

<p>
The web app allows users to interact with the model through a browser,
making predictions without needing technical knowledge.
</p>

<hr>

<h2>📌 Key Learnings from This Project</h2>
<ul>
  <li>How to compare multiple ML models effectively</li>
  <li>Importance of ROC-AUC over accuracy in binary classification</li>
  <li>Understanding ensemble learning methods</li>
  <li>Deploying ML models as web applications</li>
  <li>End-to-end machine learning workflow</li>
</ul>

<hr>

<h2>✅ Conclusion</h2>
<p>
This project demonstrates a complete machine learning pipeline, from
data preprocessing and model training to evaluation and deployment.
It highlights the importance of comparative analysis in selecting the
best-performing model for real-world classification problems.
</p>

<p>
The inclusion of ROC curves and AUC metrics provides a deeper and more reliable
understanding of model performance, making this project a strong example of
practical machine learning implementation.
</p>
