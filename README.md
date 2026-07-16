# 🍔 JS Functions: Food Truck Exercises

![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)

ยินดีต้อนรับสู่ Repository สำหรับฝึกฝนและทบทวนความรู้เกี่ยวกับ **JavaScript Functions** และ **Array Methods** ผ่านธีมจำลองระบบจัดการร้านอาหาร Food Truck! 🚚🌮

---

## 🎯 วัตถุประสงค์ของการเรียนรู้

Repository นี้ถูกจัดทำขึ้นเพื่อฝึกฝนการเขียน JavaScript ในหัวข้อต่อไปนี้โดยเฉพาะ:
- การอ่านและเข้าถึงข้อมูลใน **Objects**
- การใช้งาน **Arrays** เบื้องต้นและการอ้างอิงตำแหน่ง (Index)
- การค้นหาข้อมูลแบบเจาะจงด้วย **`Array.prototype.find()`**
- การคัดกรองข้อมูลเป็นกลุ่มด้วย **`Array.prototype.filter()`**

## 📂 โครงสร้างของโปรเจกต์ (Project Structure)

แบบฝึกหัดถูกแบ่งออกเป็นระดับ (Stages) เพื่อให้สามารถเรียนรู้และทำความเข้าใจได้อย่างเป็นลำดับขั้นตอน:

```text
📦 JS_FUNCTIONS
 ┣ 📂 exercises                 # โฟลเดอร์รวมแบบฝึกหัด
 ┃ ┣ 📜 stage-1-exercise.js   # Stage 1: อ่านค่าจาก Object properties
 ┃ ┣ 📜 stage-2-exercise.js   # Stage 2: ใช้งาน Array index และ length
 ┃ ┣ 📜 stage-3-exercise.js   # Stage 3: ค้นหาข้อมูล 1 รายการด้วย .find()
 ┃ ┗ 📜 stage-4-exercise.js   # Stage 4: คัดกรองข้อมูลหลายรายการด้วย .filter()
 ┣ 📂 fakeData                  # โฟลเดอร์เก็บข้อมูลจำลอง
 ┃ ┗ 📜 foodTruckDB.js        # ฐานข้อมูลจำลองร้าน Food Truck (Mock Data)
 ┣ 📜 package.json
 ┗ 📜 README.md
```

## 🚀 วิธีการรันโค้ด (How to Run)

แบบฝึกหัดนี้รันบน **Node.js** สามารถทดสอบผลลัพธ์ของแต่ละแบบฝึกหัดได้ง่ายๆ ผ่าน Terminal:

1. เปิด Terminal และนำทางไปยังโฟลเดอร์ของโปรเจกต์นี้
   ```bash
   cd JS_FUNCTIONS
   ```
2. รันไฟล์ของแต่ละสเตจด้วยคำสั่ง `node`:
   ```bash
   node exercises/stage-1-exercise.js
   node exercises/stage-2-exercise.js
   node exercises/stage-3-exercise.js
   node exercises/stage-4-exercise.js
   ```
3. เทียบผลลัพธ์ใน Terminal กับคอมเมนต์ `// Expected output` ในไฟล์เพื่อให้แน่ใจว่าฟังก์ชันทำงานถูกต้อง

## 📝 รายละเอียดของแต่ละ Stage

### 🥇 Stage 1: Object Properties
ทำความเข้าใจพื้นฐานการทำงานกับ Object การเข้าถึงค่า (Value) ด้วย Key (Properties) เช่น การดึงชื่อรถ Food Truck หรือตรวจสอบสถานะเปิด-ปิดร้าน

### 🥈 Stage 2: Arrays & Indexes
เรียนรู้การทำงานของ Array การอ้างอิงสมาชิกตัวแรก ตัวสุดท้าย ด้วย Index และการประยุกต์ใช้ property `length`

### 🥉 Stage 3: `find()` Method
ฝึกการเขียน Callback Function ทำงานร่วมกับ `.find()` เพื่อดึงข้อมูล "ชิ้นเดียว" ที่ตรงกับเงื่อนไข เช่น หาข้อมูลเมนูอาหารด้วย ID

### 🏅 Stage 4: `filter()` Method
ก้าวไปอีกขั้นด้วยการใช้ `.filter()` สำหรับกรองข้อมูล "หลายชิ้น" ออกมาเป็น Array ใหม่ เช่น หาเมนูที่ราคาไม่เกินงบประมาณ หรือสินค้าที่กำลังจะหมดสต๊อก

---

**Happy Coding! ✨** 
หวังว่าแบบฝึกหัดชุดนี้จะช่วยพัฒนาทักษะและความเข้าใจเรื่อง JavaScript Functions และ Array Methods ได้ดียิ่งขึ้นครับ!
