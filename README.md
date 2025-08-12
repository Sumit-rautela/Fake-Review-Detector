Fake Review Detector 🕵️‍♂️💬

A web application that detects whether a product review is Original (OR) or Computer-Generated (CG) using a BERT-based deep learning model.
Built with Python, Hugging Face Transformers, and Streamlit, and deployed locally via LocalTunnel.

📌 Features
🧠 BERT-powered NLP model for accurate fake review classification.

🌐 Streamlit UI for an interactive, user-friendly experience.

⚡ Real-time prediction — instantly see if a review is fake or genuine.

📊 Confidence score for each prediction.

💾 Works locally and can be shared temporarily using LocalTunnel.

🛠 Tech Stack
Language: Python 3.9+

Libraries:

transformers (BERT model)

torch (PyTorch backend)

pandas & numpy (data handling)

scikit-learn (preprocessing & evaluation)

streamlit (web interface)

Deployment: LocalTunnel

📂 Dataset
This project uses the Fake Reviews Dataset from Kaggle:
📌 Fake Reviews Dataset by Maxwell
Credit: Maxwell — thank you for providing the dataset for research purposes. 🙏

⚙️ Installation
1️⃣ Clone the repository
bash
Copy
Edit
git clone https://github.com//Sumit-rautela/Fake-Review-Detector.git
cd fake-review-detector
2️⃣ Create and activate a virtual environment
bash
Copy
Edit
python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows
3️⃣ Install dependencies
bash
Copy
Edit
pip install -r requirements.txt
🚀 Usage
1️⃣ Run the Streamlit app
bash
Copy
Edit
streamlit run app.py
2️⃣ (Optional) Share via LocalTunnel
bash
Copy
Edit
npx localtunnel --port 8501
You’ll get a public URL to share the app temporarily.

📊 Model Training
Dataset: Labeled with OR (Original) and CG (Computer-Generated).

Preprocessing: Tokenization with BERT tokenizer.

Model: Fine-tuned bert-base-uncased with classification head.

Evaluation: Accuracy, Precision, Recall, and F1-score.

(Training script: train_model.py)

📜 License
This project is licensed under the MIT License.
