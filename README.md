# 🗄️ LEAF | Legal Editorial Automation Framework

A notification service for [LEAF](https://github.com/anildani36/sentinel.git) eco-system. This service sends notification via Email 
and Team notification in channel.

---

## ✨ Services

- **[CORE](https://github.com/anildani36/core.git)**
  - Framwork for automated collection, extraction and XML transformation of data

- **[LENS](https://github.com/anildani36/lens.git)**
  - Central portal for job submission, monitoring and history tracking

- **[SENTINEL](https://github.com/anildani36/sentinel.git)**
  - Notification service for alerts and job status notifications

- **[TIVA](https://github.com/anildani36/tiva.git)**
  - Service to convert the HTML based tables to image attachments in data

---

## 🛠 Tech Stack

**Backend**
- Python 3.13
- FastAPI

---

## 📂 Project Structure

```

leaf/             
├── images/                
├── services/                 
│   ├── core/
│   ├── lens/
│   ├── sentinel/
│   └── tiva/
└── README.md 

````

---

## 🚀 Getting Started

### Prerequisites
- Python **3.13+**
- **uv** (Fast Python package manager)

---

### Installation

1️⃣ **Clone the repository**
```bash
git clone https://github.com/anildani36/sentinel.git
cd sentinel
````

2️⃣ **Install dependencies**

```bash
uv sync
```

3️⃣ **Run the application**

```bash
uv run main.py
```

4️⃣ **Open in browser**

```
http://127.0.0.1:5000
```
or
```
http://localhost:5000
```

---

## Architecture

To be added

---

## 💡 How It Works

1. **Select Length**

   * Use the slider to choose password length (8–25 characters)

2. **Customize Characters**

   * Toggle:

     * Uppercase
     * Lowercase
     * Numbers
     * Symbols

3. **Instant Feedback**

   * Password updates immediately via Fetch API calls

4. **Security First**

   * Passwords generated using `secrets.choice()`
   * Resistant to brute-force predictability

---

## 🔒 Security Notes

* No passwords are stored or logged
* All generation occurs server-side using secure entropy
* No external APIs involved

---

## 👨‍💻 Author

**[Anil Dani](htttps://www.linkedin.com/in/anildani)**

---

## 📜 License

This project is licensed under the **[GNU GPL V3 License](LICENSE)** — feel free to use, modify, and distribute.

---

⭐ If you find this project useful, consider starring the repository!
