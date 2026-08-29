# 💗 1st Anniversary — โมเมทน์ & แทนคุณ

ไฟล์ชุดนี้พร้อมอัปขึ้น GitHub Pages แล้ว

## วิธีที่ง่ายที่สุดบนมือถือ
1. สร้าง Repository ใหม่ใน GitHub ชื่อ เช่น `our-1st-anniversary`
2. ตั้ง Repository เป็น Public
3. อัปโหลดไฟล์ทั้งหมดในโฟลเดอร์นี้ โดยให้ `index.html` อยู่ที่ระดับบนสุด
4. ไปที่ **Settings → Pages**
5. ที่ **Build and deployment → Source** เลือก **GitHub Actions**
6. รอให้ workflow Deploy GitHub Pages ทำงานสำเร็จ
7. กลับมาที่ **Settings → Pages → Visit site** เพื่อรับลิงก์เว็บไซต์

เว็บไซต์จะมี URL ประมาณ:
`https://ชื่อผู้ใช้.github.io/our-1st-anniversary/`

## ไฟล์สำคัญ
- `index.html` เว็บไซต์หลัก
- `images/` รูปความทรงจำ
- `.github/workflows/deploy.yml` ระบบเผยแพร่เว็บไซต์อัตโนมัติ
- `.nojekyll` ป้องกัน GitHub Pages ประมวลผลแบบ Jekyll

## หมายเหตุ
ทุกครั้งที่แก้ไขไฟล์และอัปโหลดขึ้น branch `main` เว็บไซต์จะ deploy ใหม่อัตโนมัติ
