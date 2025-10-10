# Agent Wallboard System

**Agent Wallboard System** เป็นระบบสำหรับแสดงสถานะและข้อมูลแบบเรียลไทม์ของตัวแทน (agents) ผ่านหน้าจอ wallboard — เหมาะกับการใช้งานในศูนย์บริการลูกค้า (call center) เพื่อให้ผู้จัดการหรือทีมงานเห็นภาพรวมของการทำงานได้ทันที

---

## 📂 โครงสร้างโปรเจกต์

โปรเจกต์นี้แบ่งออกเป็นหลายส่วนสำคัญ:

- **agent-desktop** — ส่วน frontend สำหรับ agent ใช้งาน
- **backend-server** — API / Logic หลักของระบบ
- **database** — Schema และไฟล์ที่เกี่ยวกับฐานข้อมูล
- **supervisor-dashboard** — หน้าจอแดชบอร์ดสำหรับผู้จัดการ / Supervisor
- **README.md** — ไฟล์ README หลัก (ไฟล์นี้)

---

## 🚀 เริ่มต้นใช้งาน (Installation & Setup)

### 1. โคลนโปรเจกต์

```
bash
git clone https://github.com/Peerapong67/agent-wallboard-system.git
cd agent-wallboard-system
```
### 2. ตั้งค่าฐานข้อมูล
* เขียนโครงสร้างฐานข้อมูล (schema) หรือรัน migration ที่อยู่ในโฟลเดอร์ database
* แก้ไขไฟล์คอนฟิกฐานข้อมูล (เช่น host, port, username, password) ให้ตรงกับสภาพแวดล้อมของคุณ

### 3. ติดตั้ง dependencies และรัน backend
เข้าไปที่โฟลเดอร์ backend-server:
```
bash

cd backend-server
# สมมติใช้ Node.js
npm install
npm run start   # หรือคำสั่งที่ตั้งไว้
```

### 4. ติดตั้ง / รัน frontends (Agent / Supervisor)
```
bash

cd agent-desktop
npm install
npm run dev     # หรือคำสั่ง run ที่ตั้งไว้

cd ../supervisor-dashboard
npm install
npm run dev
```
