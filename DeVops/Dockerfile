# Imagen base
FROM python:3.10-slim

# Directorio de trabajo
WORKDIR /app

# Copiar archivos
COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt

COPY . .

# Exponer puerto
EXPOSE 5000

# Ejecutar la app
CMD ["python", "app.py"]
