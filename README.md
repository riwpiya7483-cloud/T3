# Tutor Mate (เว็บแอป)

## ก่อน deploy
1. วางโค้ด Tutor Mate เดิม "ทั้งไฟล์" ทับ `App.jsx` (ไม่ต้องแก้โค้ด)
   - ถ้าบรรทัดแรกเป็น ```react และบรรทัดสุดท้ายเป็น ``` ให้ลบสองบรรทัดนั้นออก

## Deploy (Netlify หรือ Vercel ผ่าน GitHub)
1. สร้าง repo ใหม่บน GitHub แล้วอัปโหลดไฟล์ทั้งหมดในโฟลเดอร์นี้ (ทุกไฟล์อยู่ระดับเดียวกัน ไม่มีโฟลเดอร์ย่อย)
2. Netlify: Add new site > Import an existing project > เลือก repo
   - Build command: `npm run build`
   - Publish directory: `dist`
   (ปกติระบบตรวจเจอ Vite แล้วเติมให้เอง) แล้วกด Deploy
   Vercel: Add New > Project > เลือก repo > Framework เป็น Vite > Deploy

## ทดสอบในเครื่อง (ถ้ามี Node.js)
`npm install` แล้ว `npm run dev`

## เช็กลิสต์หลัง deploy
ตาราง > จัดการวัน (ลงเวลา/นำเข้าคลาส) > รายงานทั้ง 4 โหมด > ชำระเงิน/บิลรวม > ข้อความแจ้งยอด
> คะแนน > ลิงก์ (กดค้างลากสลับ) > กราฟ > Backup / Restore
