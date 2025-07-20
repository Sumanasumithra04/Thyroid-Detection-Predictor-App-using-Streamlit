# Thyroid-Disease-classifier

This project introduces a machine learning-powered web app to assist in detecting thyroid disorders like hypothyroidism and hyperthyroidism. Built with Streamlit, the app allows users to input patient health metrics and receive instant, reliable predictions based on trained clinical data—empowering smarter, faster healthcare decisions.

It leverages a robust model trained on real-world patient records and features an intuitive UI for ease of use by medical professionals and researchers alike.

##✨ Features
⚡ Instant prediction of thyroid conditions

🤖 Machine learning model trained on real patient data

🧪 Input options for hormones & medical history

📊 User-friendly interface with visual feedback

🌐 Easily deployable as a web application

🛠️ Technologies Used
📘 Python

🔮 Scikit-learn (ML model)

📊 Pandas, NumPy (data preprocessing)

🌐 Streamlit (frontend UI)

🧪 Jupyter Notebook for model training





## Images
![Image 1](https://github.com/Sumanasumithra04/Thyroid-Disease-classifier/blob/8f1f97592babce72123e473e89f8ffe56571db5e/image/image%201%20.png)


![Image 2](https://github.com/Sumanasumithra04/Thyroid-Disease-classifier/blob/b7a000e74974dc780058905deb68c499f1d05eee/image/image%202.png)

## Key Features

- **Efficiency:** Instant diagnosis predictions save time and facilitate faster patient care.
- **Accuracy:** Our machine learning model is trained on high-quality data and evaluated for accuracy and reliability.
- **Accessibility:** Accessible via a user-friendly web interface built with Streamlit, our application can be used anytime, anywhere, with internet connectivity.

## Project Structure

```
.
├── Streamlit_app.py         # Streamlit application code
├── model.pkl                # Serialized machine learning model
├── model_code.ipynb         # Jupyter notebook containing model training code
├── README.md                # Project documentation
├── requirements.txt         # List of dependencies
├── train_data.csv           # Dataset used for training the model
├── test_data.csv            # Dataset used for testing the model
└── thyroidDF.csv            # Original dataset
```

## Process to Run

1. **Train and Pickle Model:**
   - Open `model_code.ipynb` in Jupyter Notebook or any compatible environment.
   - Execute the code cells to train the machine learning model using `train_data.csv`.
   - Serialize the trained model and save it as `model.pkl`.

2. **Run Streamlit Application:**
   - Open your terminal.
   - Navigate to the project directory.
   - Install dependencies by running:
     ```
     pip install -r requirements.txt
     ```
   - Execute the following command to run the Streamlit application:
     ```
     streamlit run Streamlit_app.py
     ```

## Attributes Information

- **Age:** Age of the patient (numeric)
- **Sex:** Sex of the patient (categorical: 'M' for male, 'F' for female)
- **On Thyroxine:** Whether the patient is on thyroxine medication (binary: 'Yes' or 'No')
- **Query on Thyroxine:** Whether the patient is querying about thyroxine medication (binary: 'Yes' or 'No')
- **On Antithyroid Meds:** Whether the patient is on antithyroid medication (binary: 'Yes' or 'No')
- **Sick:** Whether the patient is sick (binary: 'Yes' or 'No')
- **Pregnant:** Whether the patient is pregnant (binary: 'Yes' or 'No')
- **Thyroid Surgery:** Whether the patient has undergone thyroid surgery (binary: 'Yes' or 'No')
- **I131 Treatment:** Whether the patient is undergoing I131 treatment (binary: 'Yes' or 'No')
- **Query Hypothyroid:** Whether the patient believes they have hypothyroidism (binary: 'Yes' or 'No')
- **Query Hyperthyroid:** Whether the patient believes they have hyperthyroidism (binary: 'Yes' or 'No')
- **Lithium:** Whether the patient is taking lithium medication (binary: 'Yes' or 'No')
- **Goitre:** Whether the patient has goitre (binary: 'Yes' or 'No')
- **Tumor:** Whether the patient has a tumor (binary: 'Yes' or 'No')
- **Hypopituitary:** Whether the patient has hypopituitarism (binary: 'Yes' or 'No')
- **Psych:** Whether the patient has psychiatric issues (binary: 'Yes' or 'No')
- **TSH:** Thyroid-stimulating hormone level in blood (numeric)
- **T3:** Triiodothyronine level in blood (numeric)
- **TT4:** Total thyroxine level in blood (numeric)
- **T4U:** Thyroxine utilization rate in blood (numeric)
- **FTI:** Free thyroxine index in blood (numeric)

## Note

The Thyroid Detection App using Streamlit is intended for educational and informational purposes only and should not replace professional medical advice, diagnosis, or treatment. Always consult with a qualified healthcare provider for any medical concerns or questions.

---

This version includes a table of contents to provide easy navigation and access to different sections of the README. If you have any further questions or need additional information, feel free to ask!
