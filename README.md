# CIG Internal Hub

ศูนย์สื่อสาร **IT ↔ MKT** สำหรับเว็บ `cigblu.com` — เว็บภายในที่ **มิเรอร์โครงหน้าเว็บจริง**
เพื่อบอกในที่เดียวว่าแต่ละหน้า *ต้องแก้อะไร · โหลด resource อะไร · สถานะแค่ไหน*

## เปิดใช้งาน
- หน้าเว็บ (GitHub Pages): เปิด `index.html` = Dashboard รวมทุกหน้า
- แต่ละหน้ามิเรอร์ URL จริง เช่น เว็บจริง `/products/refrigeration` → hub `products/refrigeration/`

## หลักการ
- hub เป็น **ชั้น index** ไม่เก็บไฟล์เนื้อหาซ้ำ (กันข้อมูลล้า) — ปุ่มโหลดชี้ไฟล์จริงใน repo เว็บ
- **โครง** มาจาก target tree (migration-map + nav-structure) · **สถานะ** มาจากเว็บที่ IT ขึ้นจริง

## แต่ละหน้ามี 4 บล็อก
1. Change notes — สิ่งที่ต้องแก้ 2. Resource downloads — ไฟล์ให้ IT โหลด
3. สถานะงาน 4. ลิงก์อ้างอิง (Figma / live / repo)

## ยังไม่ทำในรอบ scaffold นี้
- Model pages ~27 หน้า + Refrigeration L3 → จะแตกทีหลังต่อ family
- Global shell (nav/footer) → IT ขึ้นเสร็จแล้ว ยังไม่จำเป็น

> สถานะเป็นเว็บภายใน — ตั้ง `noindex` ทุกหน้า ไม่ให้ search engine เก็บ
