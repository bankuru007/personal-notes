# Personal Notes Flask App 📝

A simple web application built using Python Flask that allows you to:
✅ Add Notes  
✅ View Notes  
✅ Delete Notes  

Notes are stored in an SQLite database.

---

## 🚀 Features
- Add personal notes
- Display all saved notes
- Delete notes
- Lightweight and beginner-friendly
- Ready to deploy on Render

---

## 📂 Project Structure
```
personal_notes_app/
│
├── app.py                # Main Flask application
├── requirements.txt      # Python dependencies
├── render.yaml           # Render deployment configuration
├── templates/            # HTML templates
│     ├── home.html
│     └── add_note.html
└── notes.db              # SQLite database (auto-generated after running)
```

---

## 🛠 Installation and Run Locally

### 1. Clone the repository
```
git clone https://github.com/YOUR_USERNAME/personal_notes_app.git
cd personal_notes_app
```

### 2. Install dependencies
```
pip install -r requirements.txt
```

### 3. Run the Flask app
```
python app.py
```

### 4. Visit in Browser
```
http://127.0.0.1:5000/
```

---

## 🌐 Deployment (Optional)
- Ready to deploy on **Render**
- Contains `render.yaml` for easy configuration

---

## ✅ Requirements
- Python 3.x
- Flask
- SQLite (comes pre-installed with Python)

---

## 🤝 Contribution
Pull requests are welcome! If you'd like to improve this project, feel free to fork and raise a PR.

---

## 📃 License
This project is open-source and free to use.

---