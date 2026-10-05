# AR Retro Adventure – Hiro Marker

โปรเจกต์ AR สำหรับทดลองบนมือถือ โดยใช้ A-Frame + AR.js

## วิธีใช้งาน

1. Upload ไฟล์ทั้งหมดในโฟลเดอร์นี้ขึ้น GitHub Repository
2. เปิด GitHub Pages
3. เปิดเว็บไซต์ด้วยมือถือ
4. อนุญาตการใช้กล้อง
5. ส่องกล้องไปที่ `hiro-marker.png`
6. เมื่อพบ Hiro Marker จะเห็นเกม AR
7. กด `กระโดด / โหม่งเห็ด` เพื่อรับ 1 เหรียญและ 100 คะแนน
8. กด `ยก 2 นิ้ว` เพื่อรับโบนัส 2 เหรียญและ 50 คะแนน
9. กด `Reset` เพื่อเริ่มเกมใหม่

## GitHub Pages

Settings → Pages → Deploy from a branch → Branch: `main` → Folder: `/ (root)`

URL จะมีรูปแบบ:

`https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/`

## หมายเหตุ

- ต้องใช้งานผ่าน HTTPS สำหรับกล้องบนมือถือ
- โมเดลตัวละครในตัวอย่างสร้างจาก A-Frame primitives ไม่ได้ใช้ไฟล์ตัวละคร Mario ที่มีลิขสิทธิ์
- ไลบรารี A-Frame และ AR.js ถูกโหลดจาก CDN ใน `index.html`
