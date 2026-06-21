# NEXMIND Trading Trainer

เว็บฝึกคำนวณเทรด XAUUSD แบบสุ่มโจทย์ไม่จำกัด ครอบคลุม Position Sizing, Expectancy และ Drawdown
ทำงานได้ทุก device (มือถือ/แท็บเล็ต/คอม) เก็บสถิติในเครื่องด้วย localStorage ไม่ต้องมี backend

## วิธี deploy ขึ้น GitHub Pages

1. สร้าง repo ใหม่บน GitHub (เช่น `nexmind-trainer`)
2. อัปโหลดไฟล์ `index.html` เข้า repo (วางที่ root ของ repo เลย)
3. ไปที่ **Settings → Pages**
4. ใต้ "Build and deployment" → Source เลือก **Deploy from a branch**
5. เลือก branch `main` และโฟลเดอร์ `/ (root)` แล้วกด **Save**
6. รอ 1-2 นาที เว็บจะออนไลน์ที่ `https://<username>.github.io/<repo-name>/`

## หมายเหตุ
- เป็นไฟล์ HTML เดียวจบ (CSS + JS + ฟอนต์อยู่ในตัว ดึงฟอนต์จาก Google Fonts)
- ต้องชื่อ `index.html` เพื่อให้ GitHub Pages เปิดเป็นหน้าแรกอัตโนมัติ
- สถิติเก็บแยกแต่ละเบราว์เซอร์/เครื่อง (localStorage)

## นิยามที่ใช้
- 1 pip = ราคาขยับ 0.1
- pip value = $1 ต่อ 1.00 lot
