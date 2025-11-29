# 📬 Email & SMS Spam Classifier

A machine learning web application that classifies whether a given email or SMS message is **Spam** or **Not Spam**.  
Built with **Python**, **Scikit-learn**, **NLTK**, and **Streamlit**.

---

## 📸 Screenshots

### 🔴 Spam Detected  
<img width="1035" height="500" alt="Image" src="https://github.com/user-attachments/assets/ce1b752d-5943-47d2-9bfb-f29227b6ddf3" />


### 🟢 Not Spam  
<img width="1063" height="532" alt="Image" src="https://github.com/user-attachments/assets/7bbcc2ba-780f-4330-9acd-fd4361c816c7" />

---

## 🚦 Features

- Real-time classification of emails/SMS messages  
- Custom text preprocessing pipeline  
- TF-IDF vectorization  
- Machine learning model for spam detection  
- Interactive Streamlit UI  

---

## 🧠 Tech Stack

- Python 3.x  
- Scikit-learn  
- NLTK  
- Streamlit  
- Pickle  

---

## 📁 Project Structure
```
├── app.py
├── Vectorizer.pkl
├── model.pkl
├── Sms-spam_Detection.ipynb
├── requirements.txt
└── README.md
```


---

## 🚀 Getting Started
```
1️⃣ Clone the Repository
git clone https://github.com/<your-username>/email-sms-classifier.git
cd email-sms-classifier

2️⃣ Create a Virtual Environment
python -m venv venv

Activate:

Windows
venv\Scripts\activate

Mac/Linux
source venv/bin/activate

3️⃣ Install Dependencies
pip install -r requirements.txt

4️⃣ Run the Application

streamlit run app.py

```
## 🧪 How It Works
- User enters email/SMS text

- Text is preprocessed (lowercasing, tokenization, stopword removal, stemming)

- Vectorized using TF-IDF

- ML model predicts Spam or Not Spam

- Result displayed in the UI

## 📓 Jupyter Notebook
Model training and preprocessing workflow:
Sms-spam_Detection.ipynb

## 🚧 Future Improvements
- Add confidence score

- Better UI design

- Deploy online

- Include dataset summary