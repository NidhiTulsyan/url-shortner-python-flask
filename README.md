# 🚀 URL Shortener with Flask  

This is a **simple and efficient URL shortening application** built with Flask, a lightweight web framework in Python. It works like popular services such as **bit.ly** or **TinyURL**, allowing users to shorten long URLs and redirect them easily.  

---

## 📂 **Project Structure**  
- **`main.py`** – Contains the core Flask application logic and routes.  
- **`urls.json`** – Stores the mapping between shortened URLs and original URLs.  
- **`templates/index.html`** – Frontend template with a form to submit and display shortened URLs.  

---

## 💡 **How It Works**  
1. **Generate Short URL** – When a user submits a long URL, the app generates a unique short URL using random characters (letters and digits).  
2. **Store the Mapping** – The mapping between the short and long URLs is stored in `urls.json` for future reference.  
3. **Redirection** – When the short URL is accessed, the app looks up the original URL and redirects the user.  
4. **404 Handling** – If the short URL doesn't exist, a clean 404 error page is shown.  

---

## 🚀 **Getting Started**  
### 🔹 **1. Clone the Repository**  
```bash
git clone https://github.com/your-username/url-shortener.git
cd url-shortener

### 🔹 **2. Install Dependencies**  
```bash
pip install flask

