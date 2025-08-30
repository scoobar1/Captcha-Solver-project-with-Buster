# 🧠 Advanced Captcha Solver with Buster Integration

## 📌 Overview
This project is an **AI-powered Python-based Captcha Solver** combined with the **Buster Captcha Solver** browser extension.  
It is designed for **web automation, scraping, and system integration** where bypassing CAPTCHAs is required.

Key highlights:
- 🚀 Automatically detects and solves a wide range of CAPTCHA types.
- 🧩 Learns continuously from failed attempts, improving accuracy over time.
- 🔌 Can be embedded into any automation system or used as a standalone tool.
- 🌍 Cross-platform and flexible (Windows, Linux, macOS).

Author: **mrdev (Mahmoud Essam)**

---

## ✨ Features
- ✅ **Automation Ready** – Integrates seamlessly with Selenium, Playwright, or desktop automation tools.
- ✅ **AI Self-Training** – Improves performance with every failed CAPTCHA attempt.
- ✅ **Buster Extension Support** – Uses the Buster browser extension to handle reCAPTCHA challenges.
- ✅ **Plug-and-Play** – Works out of the box, can be attached to any Python project.
- ✅ **Scalable** – Can be extended to work with large-scale scraping or bot systems.

---

## ⚙️ Requirements
- **Python**: Version 3.8 or later  
- **Browser**: Google Chrome or Mozilla Firefox  
- **Extension**: Buster Captcha Solver  

### 📦 Python Dependencies
Install all required Python libraries with:
```bash
pip install -r requirements.txt
```

---

## 🔧 Installing Buster Captcha Solver Extension
1. Open your preferred browser:
   - [Chrome Web Store](https://chrome.google.com/webstore/detail/buster-captcha-solver-for/mpbjkejclgfgadiemmefgebjfooflfhl)  
   - [Firefox Add-ons](https://addons.mozilla.org/en-US/firefox/addon/buster-captcha-solver/)
2. Click **Add to Chrome / Firefox**.
3. Ensure the extension is enabled in your browser.

---

## 🚀 Usage
1. **Clone the repository:**
   ```bash
   git clone https://github.com/YOUR_USERNAME/captcha-solver.git
   cd captcha-solver
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the solver:**
   ```bash
   python captcha_solver.py
   ```

The solver will automatically detect CAPTCHAs and attempt to solve them using both its AI-based approach and the Buster extension.

---

## 🎓 Training the Solver
This project includes a **learning mode** that allows the solver to improve continuously.

- ❌ Failed CAPTCHA attempts are logged and saved.  
- 📊 The model is retrained with each failure, boosting accuracy.  
- 📂 You can add your own dataset of CAPTCHA images to improve results.

To train manually:
```bash
python train.py
```

---

## 🔌 Integration into Other Systems
The solver can be embedded into:
- **Selenium / Playwright scripts**
- **Headless browser automation**
- **Desktop automation (PyAutoGUI, etc.)**
- **Custom scraping frameworks**

Example:
```python
from captcha_solver import CaptchaSolver

solver = CaptchaSolver()
if solver.solve():
    print("✅ Captcha solved successfully!")
else:
    print("❌ Failed to solve captcha.")
```

---

## 📁 Project Structure
```
captcha-solver/
│
├── captcha_solver.py       # Main solver script
├── train.py                # Training script for improving recognition
├── requirements.txt        # Python dependencies
├── README.md               # Documentation
└── data/                   # Captcha datasets (training & failed attempts)
```

---

## 👤 Author
- **Name:** Mahmoud Essam  
- **Alias:** mrdev  
- **GitHub:** [https://github.com/YOUR_USERNAME](https://github.com/YOUR_USERNAME)  

---

## ⚠️ Disclaimer
This project is for **educational and research purposes only**.  
The author is not responsible for any misuse of this tool.  
