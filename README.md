# Agent Wallboard System

**Agent Wallboard System** เป็นระบบสำหรับแสดงสถานะและข้อมูลแบบเรียลไทม์ของตัวแทน (agents) ผ่านหน้าจอ wallboard — เหมาะกับการใช้งานในศูนย์บริการลูกค้า (call center) เพื่อให้ผู้จัดการหรือทีมงานเห็นภาพรวมของการทำงานได้ทันที

---

## 🧩 โครงสร้างโปรเจกต์

โปรเจกต์นี้แบ่งออกเป็นหลายส่วนสำคัญ:

- **agent-desktop** — ส่วน frontend สำหรับ agent ใช้งาน
- **backend-server** — API / Logic หลักของระบบ
- **database** — Schema และไฟล์ที่เกี่ยวกับฐานข้อมูล
- **supervisor-dashboard** — หน้าจอแดชบอร์ดสำหรับผู้จัดการ / Supervisor
- **README.md** — ไฟล์ README หลัก (ไฟล์นี้)

---

## 🚀 เริ่มต้นใช้งาน (Installation & Setup)

### 1. คลอนโปรเจกต์

```bash
git clone https://github.com/Peerapong67/agent-wallboard-system.git
cd agent-wallboard-system
```
### 2.ติดตั้ง dependencies & ตั้งค่าตัวแปรแวดล้อม

ในแต่ละโฟลเดอร์ที่เป็นบริการ (backend-server, agent-desktop, supervisor-dashboard):
```bash
git clone https://github.com/Peerapong67/agent-wallboard-system.git
cd agent-wallboard-system
```
