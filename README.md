# โปรเจกต์ Django E-commerce

นี่คือแอปพลิเคชันอีคอมเมิร์ซที่สร้างขึ้นด้วย Django 4 ซึ่งมีฟังก์ชันพื้นฐานสำหรับการจัดการสินค้า การยืนยันตัวตนของผู้ใช้ และฟีเจอร์ตะกร้าสินค้า

## คุณสมบัติ

- การยืนยันตัวตนของผู้ใช้ (ลงทะเบียน, เข้าสู่ระบบ, ออกจากระบบ)
- หน้ารายการสินค้าและหน้ารายละเอียดสินค้า
- ฟีเจอร์ตะกร้าสินค้า
- การจัดการคำสั่งซื้อ
- แผงควบคุมสำหรับผู้ดูแลระบบเพื่อจัดการสินค้าและคำสั่งซื้อ

## การติดตั้ง

1. โคลนโปรเจกต์นี้:

   ```bash
   git clone https://github.com/your-username/django-ecommerce.git
   cd django-ecommerce
   ```

2. สร้างและเปิดใช้งาน virtual environment:

   ```bash
   python -m venv env
   env\Scripts\activate  # บน Windows
   ```

3. ติดตั้ง dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. ใช้คำสั่ง migrations:

   ```bash
   python manage.py migrate
   ```

5. สร้าง superuser:

   ```bash
   python manage.py createsuperuser
   ```

6. รันเซิร์ฟเวอร์สำหรับการพัฒนา:

   ```bash
   python manage.py runserver
   ```

7. เปิดเบราว์เซอร์และไปที่ `http://127.0.0.1:8000`

## โครงสร้างโปรเจกต์

```
django-ecommerce/
├── shopping/          # แอปหลักสำหรับฟังก์ชันอีคอมเมิร์ซ
├── templates/         # ไฟล์ HTML templates
├── static/            # ไฟล์ Static (CSS, JS, รูปภาพ)
├── db.sqlite3         # ฐานข้อมูล SQLite
├── manage.py          # สคริปต์จัดการ Django
└── requirements.txt   # Dependencies ของ Python
```

## ข้อกำหนด

- Python 3.8+
- Django 4.x
- SQLite (ฐานข้อมูลเริ่มต้น)


