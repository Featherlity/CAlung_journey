# วางแผนการเป็นมะเร็งระยะท้าย

เว็บหน้าเดียว ไม่มี backend ไม่มีการเก็บข้อมูลผู้เล่น

```
index.html        ตัวเกมทั้งหมด (HTML + CSS + JavaScript)
music/            เพลงประกอบ 4 ไฟล์
```

## วางบน Vercel

วิธีที่ 1 (ผ่าน GitHub): สร้าง repo ใหม่ อัปโหลดทั้งโฟลเดอร์นี้ แล้วใน Vercel กด Add New → Project → เลือก repo
ตั้ง Framework Preset เป็น Other ไม่ต้องตั้ง Build Command

วิธีที่ 2 (ผ่าน command line): เปิด terminal ในโฟลเดอร์นี้ แล้วพิมพ์ `npx vercel` ตามด้วย `npx vercel --prod`

## ทดสอบในเครื่องก่อน

เปิด terminal ในโฟลเดอร์นี้ แล้วพิมพ์ `npx serve` จากนั้นเปิด http://localhost:3000
(ดับเบิลคลิกเปิด index.html ตรงๆ ก็เล่นได้ แต่บางเบราว์เซอร์จะไม่เล่นเพลง)
