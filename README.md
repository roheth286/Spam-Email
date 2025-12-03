# 📩 Spam Email Detection (AI/ML Task)

## 🎯 Project Goal  
This project builds a spam email detection model using a **Decision Tree Classifier** to classify emails as **spam** or **not spam** based on their textual content. The full pipeline is implemented in a single Jupyter notebook, from importing the dataset to text preprocessing, TF‑IDF vectorization, model training, and evaluation.

---

## 🔬 Project Overview  

The notebook is structured into three main stages:

1. **Import the Database**
   - Load the dataset containing email texts and their corresponding spam/ham labels.
   - Shuffle the dataset to ensure randomness and reduce ordering bias.

2. **Data Cleaning**
   - Convert all email text to lowercase for consistency.
   - Tokenize the email content into words.
   - Apply **TF‑IDF Vectorization** to convert text into numerical form.
   - Split the data into **training (80%)** and **testing (20%)** sets.

3. **Model Definition, Training, and Testing**
   - Define a **Decision Tree Classifier**.
   - Train the model using the TF‑IDF‑transformed training data.
   - Make predictions on the test set.
   - Evaluate the model using appropriate metrics (e.g., accuracy and other classification metrics provided in the notebook).

---

## 📊 Dataset  

- The notebook includes a **dataset link** in the **“Database of Spam mails”** section.  
- You must download this dataset **locally** (for example, as a CSV file) using that link.  

> After downloading, run the **“Import Database”** cell in the notebook. When it prompts you to upload a file, select the downloaded dataset so the notebook can load it correctly.

---

## 📁 Project Structure  

- `README.md` → Project description and usage instructions (this file).  
- `spam_email_decision_tree.ipynb` (or similar) → Main notebook containing:
  - Dataset import logic  
  - Text cleaning and TF‑IDF vectorization  
  - Decision Tree model training and evaluation  

---

## 🚀 How to Run (Google Colab Recommended)  

1. **Open the notebook in Colab**
   - Upload the `.ipynb` file to Google Drive and open it with **Google Colaboratory**, or  
   - Open it directly from GitHub using an “Open in Colab” link if available.

2. **Download and import the dataset**
   - In the notebook, locate the **“Database of Spam mails”** section where the dataset link is provided.  
   - Click the link, download the dataset **to your local machine**.  
   - Run the **“Import Database”** cell:
     - When prompted, upload the dataset file you just downloaded.  
   - Once uploaded, the notebook will load the data and proceed with shuffling and preprocessing.

3. **Run the notebook cells in order**
   - Run the **Data Cleaning** section to:
     - Lowercase and tokenize text.  
     - Apply TF‑IDF vectorization.  
     - Split into train and test sets.  
   - Run the **Model Definition, Training, and Testing** section to:
     - Define and train the Decision Tree model.  
     - Generate predictions and evaluate model performance.

---

## 📄 Notes  

- All core steps (import, cleaning, TF‑IDF, model training, evaluation) are handled inside the notebook.  
- Any extra libraries (such as `pandas`, `scikit‑learn`, `numpy`) are installed within the notebook if required.  
- Always ensure you upload the correct dataset file when the **Import Database** cell asks for it.
