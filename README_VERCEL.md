# Bronto LIFF Frontend - Vercel Ready

ชุดนี้เป็น frontend-only สำหรับอัปขึ้น Vercel

## วิธีตั้งค่า Vercel

Framework Preset: Other
Root Directory: เว้นว่าง
Build Command: ว่าง หรือ `echo no build`
Output Directory: ว่าง หรือ `.`
Install Command: ว่าง

## ไฟล์สำคัญ

- index.html
- config.js
- vercel.json

## config.js

ตั้ง backend แล้วเป็น:

```js
API_BASE_URL: 'https://lineoa1-0s4i.onrender.com/api/v1'
```

เหลือใส่ LIFF_ID ให้ถูกต้อง
