# Restaurant Management

โปรเจกต์ระบบจัดการร้านอาหารแบบ Console ด้วย Python Standard Library

## ไฟล์
- `main.py` - โปรแกรมหลัก
- `menu.py` - จัดการเมนูอาหาร
- `table.py` - จัดการโต๊ะ
- `order.py` - รับออเดอร์
- `billing.py` - คำนวณบิล
- `report.py` - รายงานยอดขาย
- `file_manager.py` - อ่าน/เขียน JSON และจัดการ error log
- `utils.py` - รับข้อมูลและตรวจสอบ input
- `restaurant_data.json` - จะถูกสร้างอัตโนมัติหลังบันทึกข้อมูล
- `error.log` - จะถูกสร้างเมื่อเกิดข้อผิดพลาด

## วิธีรัน
เปิด Terminal ในโฟลเดอร์นี้ แล้วใช้

```bash
python main.py
```

## ความสามารถตามโจทย์
- ตัวแปร `int`, `float`, `str`, `bool`
- `if / elif / else`
- `for` และ `while`
- ฟังก์ชันมากกว่า 6 ฟังก์ชัน พร้อม parameter และ return
- ใช้ `list` และ `dict`
- แยกโปรแกรมเป็นหลาย module
- บันทึกข้อมูลลง JSON
- `try / except` และ traceback ลง `error.log`
- เพิ่ม/แก้ไข/ลบ/ค้นหาเมนู
- จัดการโต๊ะ
- รับออเดอร์
- เช็กบิล ส่วนลด ภาษี และค่าบริการ
- รายงานยอดขายและเมนูขายดี
