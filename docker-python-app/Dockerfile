# 1️⃣ نختارو image ديال Python
FROM python:3.11-slim

# 2️⃣ نخدمو داخل هاد الفولدر
WORKDIR /app

# 3️⃣ ننسخو الملفات
COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt

COPY app.py .

# 4️⃣ نفتحوا port
EXPOSE 5000

# 5️⃣ نشغلو التطبيق
CMD ["python", "app.py"]
