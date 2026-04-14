# Customer-Chat-bot

# 🤖 Real-Time Gen AI Customer Support Bot

This is the repository for **Task 1** of the NullClass Internship:  
A fully functional **Real-Time Gen AI Customer Support Bot** built using **Python, Streamlit, FAISS, and OpenAI**, deployed using **ngrok**.

The bot can:
- 🧠 Understand user queries in real-time
- 💬 Respond intelligently using a fine-tuned response database
- 🧾 Provide FAQs & support suggestions
- 🌐 Run on a Streamlit-based web app with ngrok public URL

---

## 🔧 Folder Structure
```
📁 real-time-genai-customer-support-bot/
├── app.py
├── train_model.ipynb
├── requirements.txt
├── responses.json
├── vectorizer.pkl
├── .gitignore
└── README.md
```

---

## 🚀 Getting Started

### 1️⃣ Clone the Repo
```bash
git clone https://github.com/yourusername/real-time-genai-customer-support-bot.git
cd real-time-genai-customer-support-bot
```
### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```
### 3️⃣ Set Up Ngrok
•Sign up at ngrok.com
•Copy your auth token
•Then authenticate:
```bash
ngrok config add-authtoken YOUR_NGROK_AUTH_TOKEN
```

---

### 🧠 Training (Optional)
To train or fine-tune the chatbot:
Open train_model.ipynb
Add your own responses to responses.json
Run all cells to generate vectorizer.pkl
💡 Don't forget to replace your auth token in the notebook for personal runs
(Use auth_token = "YOUR_NGROK_AUTH_TOKEN")

---

### 🌐 Running the Streamlit App
```bash
streamlit run app.py
```
Then copy the ngrok public URL printed in the terminal (e.g., https://1234-56-78-90.ngrok.io) to access the bot.

---

### 📁 Files Explained
| File                | Description                            |
| ------------------- | -------------------------------------- |
| `app.py`            | Streamlit app for chatbot frontend     |
| `train_model.ipynb` | Model training + vectorizer generation |
| `responses.json`    | Set of FAQs and pre-defined answers    |
| `vectorizer.pkl`    | TF-IDF vectorizer for text matching    |
| `requirements.txt`  | Python dependencies                    |
| `README.md`         | Project overview & setup instructions  |

---

### ✅ Task Requirements Checklist
✔️ Real-time intelligent responses using GenAI
✔️ User input + chatbot output via GUI
✔️ Organized file structure
✔️ Trainable with JSON data
✔️ .ipynb file for training
✔️ Deployable using ngrok
✔️ GitHub-ready with all files

---

### 🧑‍💻 Author
* Name: Sakshi Jadhav
* Internship Role: Data Science Intern
* Organization: NullClass

---

### 📜 License
This project is for academic and internship use only.
