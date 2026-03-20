# 🔐 Password Strength Checker (Python)

A simple Python program that evaluates the strength of a password based on common security criteria and provides suggestions to improve it.

---

## 📌 Features

- Checks password strength based on:
  - Minimum length (8 characters)
  - Uppercase letters (A–Z)
  - Lowercase letters (a–z)
  - Numbers (0–9)
  - Special characters (!@#$%^&* etc.)
- Provides:
  - Strength rating: **Weak ❌ / Medium ⚠️ / Strong ✅**
  - Suggestions to improve weak passwords

---

## 🛠️ Technologies Used

- Python 🐍
- `re` (Regular Expressions module)

---

## 🚀 How It Works

The program assigns a score based on 5 criteria:

| Criteria              | Score |
|----------------------|------|
| Length ≥ 8           | +1   |
| Uppercase letter     | +1   |
| Lowercase letter     | +1   |
| Digit                | +1   |
| Special character    | +1   |

### 🔎 Strength Levels

- **0–2 → Weak ❌**
- **3–4 → Medium ⚠️**
- **5 → Strong ✅**

---

## ▶️ How to Run

1. Make sure Python is installed on your system  
2. Save the file as `password_checker.py`  
3. Open terminal or command prompt  
4. Run the program:

```bash
python password_checker.py

Enter your password when prompted

💡 Example
Enter your password: hello123

Password Strength: Medium ⚠️
Suggestions to improve:
- Add uppercase letters
- Add special characters
📈 Possible Improvements

Add GUI using Tkinter or PyQt

Add real-time password checking

Integrate with web apps (Flask/Django)

Add password entropy calculation

Check against common password lists

🤝 Contributing

Feel free to fork this project and improve it! Contributions are always welcome.

📄 License

This project is open-source and free to use.
