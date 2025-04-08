# 📦 QR Code REST API – FastAPI Assignment

This project is a REST API built with **FastAPI** for creating, retrieving, and deleting QR codes. It is based on the instructor's original repository, but this version includes **fixes for all intentionally added bugs**.

✅ All tests pass via **GitHub Actions** CI/CD  
🐳 Fully **Dockerized** application  
📚 Auto-generated **Swagger/OpenAPI** documentation


## ✨ Features

- 🧾 Create QR codes and store them locally
- 🔍 Retrieve saved QR codes
- 🗑️ Delete QR codes
- 📄 Auto-generated OpenAPI docs (`/docs`)
- 🔐 Basic authentication (`admin` / `secret`)

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/fastapi-qr-api.git
cd fastapi-qr-api
```

### 2. Set Up Virtual Environment

```bash
python3 -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

### 3. Install Requirements

```bash
pip install -r requirements.txt
```

### 4. Create Directory for QR Codes

```bash
mkdir qr_codes
```

**Note**: Ensure this folder has write permissions. Without it, Docker won't be able to save files.

## 🧪 Run Tests

```bash
pytest
```

## 🐳 Run with Docker
Make sure Docker is running:

```bash
docker compose up --build
```

Then open your browser at: 👉 http://localhost/docs

## 🔐 Authentication
On the Swagger UI (`/docs`), click **Authorize** and use:
* **Username**: `admin`
* **Password**: `secret`


