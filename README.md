# code
- git clone https://github.com/66160015/66160015-hw1.git
- cd 66160015-hw1
- git add .
- git commit -m "hw1 project" 
- git checkout -b development 
- git checkout -b feature/home   
- git add .
- git commit -m "ทำหน้าต่างของ home เบื้องต้น"
- git add .
- git commit -m "เพิ่มรูปภาพและข้อมูล highlight"
- git add .
- git commit -m "ใส่ ลิงค์ข้อมูลที่นำมาประกอบ"
-git add .
- git commit -m "ใส่ copyright ของหน้า home" 
- git add .
- git commit -m "จัดเรียงหน้า detail แบบพื้นฐาน"
- git add .
- git commit -m "เพิ่มหัวเรื่องของ detail"
- git add .
- git commit -m "เพิ่มสถานที่ท่องเที่ยวที่ 1"
- git add .
- git commit -m "เพิ่มสถานที่ท่องเที่ยวที่ 2"
- git add .
- git commit -m "เพิ่มสถานที่ท่องเที่ยวที่ 23"
-git add .
- git commit -m "เพิ่มสถานที่ท่องเที่ยวที่ 4"
-git add .
- git commit -m "เพิ่มสถานที่ท่องเที่ยวที่ 5"
- git add .
- git commit -m "เพิ่มบทความที่เกี่ยวข้อง"
- git add .
- git commit -m "ใส่ copyright ของหน้า detail"
- git checkout -b feature/contact
- git add .
- git commit -m "เพิ่มโครงสร้างพื้นฐานของ contact"
- git add .
- git commit -m "เพิ่ม header หน้า contact" 
- git add .
- git commit -m "เพิ่มช่องใส่form และช่องทางติดต่อในหน้า contact"
- git add .
- git commit -m "เพิ่มแบบ form ในหน้า contact"
- git add .
-git commit -m "เพิ่ม input validation"
- git add .
- git commit -m "เพิ่ม ตัวอย่างการใส่ข้อความ"
- git checkout -b feature/css
- git add .
- git commit -m "สร้างตัว css"
- git add .
- git commit -m "ใส่ link เชื่อม css"
- git checkout feature/contact
- git add .
- git commit -m "เพิ่ม copyright ใน contact"
- git checkout development
- git merge feature/home
- git merge feature/contact
- git merge feature/css
- git push origin development