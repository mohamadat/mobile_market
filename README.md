

# 🛒 مشروع متجر إلكتروني بسيط – Webshop

مشروع ويب بسيط يعرض المنتجات ويتيح إضافة، تعديل، وحذف المنتجات باستخدام واجهة أمامية بـ HTML + Bootstrap وواجهة خلفية باستخدام FastAPI مع قاعدة بيانات MySQL.

---

## 🚀 تشغيل التطبيق

ادخل إلى مجلد `backend` ثم شغّل السيرفر باستخدام:

```bash
uvicorn main:app --host 0.0.0.0 --port 8000 --reload

To run the application (inside backend folder):
uvicorn main:app --host 0.0.0.0 --port 8000 --reload

Remember to start XAMPP for the database and create the tables and the dadtabase
Database name: webshop.., change it later inside main.py
CREATE TABLE products (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(255),
    price FLOAT,
    image_url VARCHAR(255)
);

To install sql connector
pip install mysql-connector-python


