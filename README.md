# Backend of DTM Project

This is the Flask backend for the DTM Project. It provides RESTful APIs to support the frontend application, handling data processing, business logic, and communication with the database.

---

## 🚀 Features

- Fast and lightweight backend using Flask
- REST API endpoints for frontend integration
- Handles requests and responses for DTM project features
- Easy to extend and maintain

---

## 🛠️ Technologies Used

- Python 3.x
- Flask (web framework)
- Flask-CORS (for cross-origin requests)
- Other dependencies as required (see `requirements.txt`)

---


---

## 📦 Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/pythonserver.git
   cd pythonserver
   ```

2. **Create a virtual environment (recommended):**
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Flask server:**
   ```bash
   python app.py
   ```
   The server will start on `http://localhost:5000` by default.

---

## 🔗 API Endpoints

- `GET /api/health` — Health check endpoint
- `POST /api/dtm` — Main DTM processing endpoint
- Other endpoints as defined in `routes/dtm_routes.py`

---

## ⚠️ Notes

- Make sure to configure CORS if you are connecting from a different frontend origin.
- Update `requirements.txt` as you add new dependencies.

---

## 👨‍💻 Developed By

Your Name –MODUGURI KARTHIK