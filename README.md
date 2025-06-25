# phishing-url-detector
# 🛡️ Phishing Website Detection Tool

## 📌 Project Title
Phishing Website Detection Tool using Python (Rule-Based + GUI)

## 📌 Short Description
A lightweight Python-based phishing URL detector that uses rule-based logic to identify suspicious URLs. It includes a command-line interface and a simple GUI built with Tkinter for real-time URL analysis.

## 🚀 Features
- Detects phishing URLs based on:
  - IP address presence
  - Lack of HTTPS
  - Suspicious keywords (e.g., login, verify, account)
- Command-line script to scan a dataset of URLs
- GUI for interactive URL checking with popup alerts

## 🛠️ Technologies Used
- Python 3
- Pandas
- Regex (re module)
- Tkinter (GUI)
- Kali Linux (testing platform)

## ▶️ How to Run

### Step 1: Install Dependencies
```bash
sudo apt install python3 python3-pip -y
pip3 install pandas scikit-learn tk
```

### Step 2: Run CLI Script
```bash
python3 rule_based_detector.py
```

### Step 3: Run GUI Interface
```bash
python3 phishing_gui.py
```

## 📸 Screenshots
### ✅ CLI Output
```
      url                         prediction
0  https://google.com           Legitimate
```

### 💻 GUI in Action
| GUI Window | Phishing Result |
|------------|------------------|
| ![](Screenshot_2025-06-23_11_42_44.png) | ![](Screenshot_2025-06-23_11_42_51.png) |



---

✅ Built by **Kalpesh Dhamanse** —  [GitHub](https://github.com/Kalpeshdhamanse/phishing-url-detector)
