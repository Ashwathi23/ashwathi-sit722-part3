
FROM python:3.9-slim

WORKDIR /app/

COPY inventory_management/requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt


COPY inventory_management/ .

CMD ["uvicorn", "main:app","--host","0.0.0.0","port","8000"]

Your Solution