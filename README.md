# assignment
# FastAPI Excel Processor

A FastAPI application that processes Excel files and exposes useful endpoints to access table and row data.

##  Input Excel
- File: `Data/capbudg.xls`
- Format: Multi-sheet Excel file
- Assumption: First column of each sheet represents row names

##  How to Run

```bash
pip install -r requirements.txt
uvicorn main:app --reload --port 9090
