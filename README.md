# Ishavasyopanishad-backend

## Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/Samskriti-Foundation/upanishads-backend
   ```

2. **Navigate to the project directory:**

   ```bash
   cd upanishads-backend
   ```

   
3. **Install dependencies using a Virtual Environment:**

   a. Create a virtual environment:

   ```bash
   python -m venv venv
   ```

   b. Activate the virtual environment:

   - **Linux/macOS:**
     ```bash
     source venv/bin/activate
     ```
   - **Windows:**
     ```bash
      venv\Scripts\activate
     ```

   c. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```
1. Start the server using FastAPI CLI:

      ```bash
      uvicorn app.main:app --reload  
      ```
      or
      
      ```bash
      fastapi dev
      ```

## Run tests

1. Run tests with Pytest:

```bash
pytest -v
```
