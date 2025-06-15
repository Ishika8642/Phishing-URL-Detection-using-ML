Phishing URL Detector
A machine learning-based project to detect phishing websites using URL features.
This model is trained using a Random Forest Classifier on a labeled dataset of phishing and legitimate URLs.


Project struture
phishing-url-detector/
├── data/               # Dataset files in .parquet format
├── notebook/           # Jupyter notebooks for analysis and modeling
├── images/             # Visualizations and plots
├── .gitignore          # Ignored files and folders
├── README.md           # Project documentation
└── requirements.txt    # List of required Python packages

⚙️ Workflow

1. Load and preprocess the dataset
2. Extract meaningful URL-based features
3. Train a RandomForestClassifier
4. Evaluate the model using:
    i.Accuracy
   ii.Confusion matrix
  iii.ROC-AUC score
5. Visualize feature importance and ROC curve


