# digipin-fastapi - FastAPI server using Digipin

Follow these steps to get your FastAPI project up and running:

### 1. 📦 Install Dependencies

Create a virtual environment and install the required packages:

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

Install dependencies using Poetry

```bash
poetry install
```

## 2. 🏃 Run the FastAPI App

Assuming your main app file is named main.py and includes a FastAPI instance:

```bash
uvicorn app.main:app --reload
```

## 3. 🌐 Access the API
Once running, your FastAPI app is available at:

📘 Swagger UI: http://127.0.0.1:8000/docs

📜 ReDoc: http://127.0.0.1:8000/redoc