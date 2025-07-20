# Thyroid-Disease-classifier

This project introduces a machine learning-powered web app to assist in detecting thyroid disorders like hypothyroidism and hyperthyroidism. Built with Streamlit, the app allows users to input patient health metrics and receive instant, reliable predictions based on trained clinical data—empowering smarter, faster healthcare decisions.

It leverages a robust model trained on real-world patient records and features an intuitive UI for ease of use by medical professionals and researchers alike.

## Features

⚡ Instant prediction of thyroid conditions

🤖 Machine learning model trained on real patient data

🧪 Input options for hormones & medical history

📊 User-friendly interface with visual feedback

🌐 Easily deployable as a web application

## Technologies Used

📘 Python

🔮 Scikit-learn (ML model)

📊 Pandas, NumPy (data preprocessing)

🌐 Streamlit (frontend UI)

🧪 Jupyter Notebook for model training


##  Folder Structure

```
📁 Thyroid-Disease-classifier
├── Streamlit_app.py         # Main Streamlit app
├── model_code.ipynb         # Model training notebook
├── model.pkl                # Trained model file
├── requirements.txt         # Dependency list
├── train_data.csv           # Training dataset
├── test_data.csv            # Testing dataset
└── thyroidDF.csv            # Original dataset
```

## Input Attributes

| Feature                             | Description                         |
| ----------------------------------- | ----------------------------------- |
| Age                                 | Patient’s age                       |
| Sex                                 | Gender (`M` or `F`)                 |
| TSH, T3, TT4, T4U, FTI              | Hormone levels (numeric)            |
| On Thyroxine, Pregnant, Tumor, etc. | Yes/No flags for medical conditions |


## APP Preview
![Image 1](https://github.com/Sumanasumithra04/Thyroid-Disease-classifier/blob/8f1f97592babce72123e473e89f8ffe56571db5e/image/image%201%20.png)


![Image 2](https://github.com/Sumanasumithra04/Thyroid-Disease-classifier/blob/b7a000e74974dc780058905deb68c499f1d05eee/image/image%202.png)

## Note

The Thyroid Detection App using Streamlit is intended for educational and informational purposes only and should not replace professional medical advice, diagnosis, or treatment. Always consult with a qualified healthcare provider for any medical concerns or questions.

---

This version includes a table of contents to provide easy navigation and access to different sections of the README. If you have any further questions or need additional information, feel free to ask!
