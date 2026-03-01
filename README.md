# **Hospital / Patient Management System**
(ฐานข้อมูลสำหรับจัดการข้อมูลผู้ป่วยในโรงพยาบาลหรือคลินิก)
# **1)ผู้จัดทำ     :**
  1.1)นายบุญยศักดิ์ รัตนดิลก ณ ภูเก็ต 67102010165

  1.2)อนันฌานนทน์ แป้นสุวรรณ 67102010176

  1.3)นายสิทธิโชติ เกรียงชัยพฤกษ์ 67102010224
  
# **2)รายละเอียด  : **
เป็นระบบฐานข้อมูลสำหรับจัดการข้อมูลผู้ป่วยในโรงพยาบาลหรือคลินิก ตั้งแต่การลงทะเบียนผู้ป่วย 
การนัดหมายแพทย์ การเข้ารับบริการจริง และการออกใบแจ้งหนี้
ระบบถูกออกแบบตามหลัก Database Normalization ถึงระดับ 3NF
และพัฒนา/ทดสอบด้วย PostgreSQL

# **3)โครงสร้างข้อมูล**
-PATIENT
-DOCTOR
-APPOINTMENTS
-VISITS
-INVOICES

# **4) วิธีรันโปรเจกต์**
   1) เปิด PostgreSQL
   2) สร้าง Database ใหม่
        CREATE DATABASE hospital_db;
   3) เข้าใช้งาน Database
        \c hospital_db;
   4) รันไฟล์ SQL Implementation
        นำไฟล์ clinic_database.sql ไป execute
        หรือ คัดลอกคำสั่ง CREATE TABLE และ INSERT แล้วรันใน pgAdmin / psql
   5) ทดลอง Query (BASIC AND JOIN QUERY)
