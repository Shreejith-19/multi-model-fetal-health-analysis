# multi-model-fetal-health-analysis
## Features
<p><li>Data cleaning and duplicate removal

<li>Outlier detection using IQR

<li>Feature scaling with StandardScaler (Z-score normalization)

<li>70-15-15 dataset split (train-validation-test)

<li>Model training with GridSearchCV hyperparameter tuning

<li>Evaluation using accuracy, classification report, and ROC-AUC
<br></br>
<b>Models compared:</b>

<li>Random Forest

<li>Gradient Boosting

<li>K-Nearest Neighbors

<li>Logistic Regression

<li>Artificial Neural Network (MLP)

<li>Support Vector Machine</p>

## Folder Structure
<pre>project-root/
│
├── data/
│   └── raw/
│       └── fetal_health.csv          # Dataset file
│
├── models/                           # (Optional) saved trained models
│
├── notebooks/
│   └── index.ipynb                      # Main notebook
│
├── requirements.txt                  # Project dependencies
└── README.md                         # Project documentation
</pre>

## Requirements
Ensure you have Python ≥ 3.8 and Jupyter Notebook installed, then install the dependencies:
<pre>
pip install -r requirements.txt
</pre>
## How to Run
<b> 1. Clone the repository</b>
<pre>git clone https://github.com/Shreejith-19/multi-model-fetal-health-analysis.git
</pre>
<b> 2. cd into the project directory</b>
<pre>cd multi-model-fetal-health-analysis
</pre>
<b>3. Open index.ipynb and run all cells</b>

## Output
<ul>
<li>Class distribution visualization</li>
<li>Outlier detection summary</li>
<li>Model performance reports</li>
<li>ROC-AUC scores for all models</li>
</ul>



