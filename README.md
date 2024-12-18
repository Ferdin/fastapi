# Setting Up FastAPI and Uvicorn on Windows

Follow these steps to install **FastAPI** and **Uvicorn** on a Windows machine.

---

## Prerequisites

- Ensure that Python is installed on your system. You can download it from [python.org](https://www.python.org/).
- Add Python to your system's PATH during installation.

---

## Steps to Install

1. **Create a Virtual Environment**  
   Open a terminal (PowerShell or Command Prompt) and navigate to your project directory. Then, create a virtual environment:
   ```bash
   python -m venv fastapi
   ```
2. **Activate the Virtual Environment**

   - For PowerShell:

   ```bash
   .\fastapi\Scripts\activate
   ```

   - For Command Prompt:

   ```bash
   fastapi\Scripts\activate.bat
   ```

3. **Install FastAPI**

   Run the following command to install FASTAPI

   ```bash
   pip install fastapi
   ```

4. **Install Uvicorn**

   Use the following command to install Uvicorn with the standard dependencies:

   ```bash
   pip install "uvicorn[standard]"
   ```

## How to run this project

Use the following command to run the server. (Usually it's on the port 127.0.0.1:8000)

```bash
uvicorn books:app --reload
```

Replace "books" with the python file that you would like to serve.
