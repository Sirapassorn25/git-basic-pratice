About Me
Hello, everyone!
My name is Sirapassorn Thongtim, but please call me Bell. I'm 24 years old and you can reach me at Sirapassorn.tb@gmail.com. Nice to meet you all.

Git คือ Version control ที่เก็บประวัติการทำงาน จัดการ Version ต่างๆ ของ Software แก้ไขข้อผิดพลาดได้ง่ายเพราะสามารถย้อนกลับไป Version ก่อนๆ ได้
แนวคิดแบ่งเป็น 3 ส่วนดังนี้
Working Directory (พื้นที่แก้ไขไฟล์ หรือ Code) ---> Staging Area (พื้นที่เตรียมพร้อมก่อนการ Commit) ---> Repository (พื้นที่เก็บประวัติการเปลี่ยนแปลง)

Git Commands
1. git init --> เป็นการเริ่มต้นใช้ git
2. git clone (url) --> คัดลอกโปรเจคมาลงไว้ยังเครื่ืองตัวเอง (Local)
3. git status --> ตรวจสอยสถานะ มี 3 สถานะ
    untracked files = ไฟล์ใหม่ที่ยังไม่ track
    changes not staged = ไฟล์ที่แก้แล้วแต่ยังไม่ Add
    changes to be committed = ไฟล์พร้อม commit
4. git add --> เลือกไฟล์เข้า staging (เหมือนเอาของใส่กล่อง)
5. git commit -m "(commit msg)" --> นำไฟล์ที่อยู่บน staging ไปเตรียมพร้อมสำหรับ push (เหมือนแปะป้ายหน้ากล่อง)
ุ6. git push --> ส่ง commit จากเครื่องเราไป remote
7. git pull --> ดึงข้อมูลล่าสุดจาก remote มาเครื่องเรา
8. git fetch --> ดึงข้อมูลจาก remote โดยยังไม่ merge

Terminal Commands
pwd = ดู path ปัจจุบันที่อยู่
ls = ดูรายการไฟล์ โฟลเดอร์
cd folder-name = เข้าไปยัง folder-name
cd .. = ย้อน 1 ระดับ
cd ../.. = ย้อน 2 ระดับ
mkdir (name) = สร้างโฟลเดอร์
open = เปิดโฟลเดอร์
clear / control + k = ล้างจอ terminal

Additional commands
git diff --> ดูความแตกต่างของไฟล์ที่แก้ไข
git diff --staged --> ดูความต่างของไฟล์ที่ add แล้ว
git help --> ดูคำสั่งและวิธีใช้ git
git log --> ดูประวัติ commit แบบเต็ม
git log --oneline --> ดูประวัติแบบสั้น
git add . --> เพิ่มทุกไฟล์เข้า staging
