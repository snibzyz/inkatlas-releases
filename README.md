<p align="center">
  <img src="assets/banner.png" alt="INKATLAS — สตูดิโอนิยายครบวงจร" width="100%">
</p>

<h1 align="center">INKATLAS</h1>

<p align="center"><b>สตูดิโอนิยายครบวงจร — เปิดให้เฉพาะผู้ได้รับเชิญ</b></p>

<p align="center">
  <a href="https://github.com/snibzyz/inkatlas-releases/releases/latest"><img src="https://img.shields.io/github/v/release/snibzyz/inkatlas-releases?style=for-the-badge&label=release&color=7C3AED" alt="release"></a>
  <a href="https://github.com/snibzyz/inkatlas-releases/releases"><img src="https://img.shields.io/github/downloads/snibzyz/inkatlas-releases/total?style=for-the-badge&label=downloads&color=A78BFA" alt="downloads"></a>
  <img src="https://img.shields.io/badge/%E0%B8%AA%E0%B8%B4%E0%B8%97%E0%B8%98%E0%B8%B4%E0%B9%8C-%E0%B9%80%E0%B8%89%E0%B8%9E%E0%B8%B2%E0%B8%B0%E0%B8%9C%E0%B8%B9%E0%B9%89%E0%B9%84%E0%B8%94%E0%B9%89%E0%B8%A3%E0%B8%B1%E0%B8%9A%E0%B9%80%E0%B8%8A%E0%B8%B4%E0%B8%8D-1E1B4B?style=for-the-badge" alt="สิทธิ์ เฉพาะผู้ได้รับเชิญ">
</p>
<p align="center">
  <img src="https://img.shields.io/badge/Windows-10%2B-0078D4?style=for-the-badge&logo=windows&logoColor=white" alt="Windows 10+">
  <img src="https://img.shields.io/badge/macOS-Apple%20Silicon-111111?style=for-the-badge&logo=apple&logoColor=white" alt="macOS Apple Silicon">
</p>

ใช้งานได้เฉพาะคีย์ที่**ได้รับสิทธิ์ ATLAS** · ติดตั้งครั้งเดียว หลังจากนั้นแอปอัปเดตตัวเองจาก repo นี้

> repo นี้เก็บเฉพาะไฟล์ติดตั้ง — ไม่มีซอร์สโค้ด

---

## ดาวน์โหลด

โหลดรุ่นล่าสุดที่ **[หน้า Releases](https://github.com/snibzyz/inkatlas-releases/releases/latest)** แล้วเลือกไฟล์ให้ตรงกับเครื่อง

| เครื่อง | ไฟล์ | หมายเหตุ |
|---|---|---|
| Windows | `INKATLAS-Setup-x.x.x.exe` | ตัวติดตั้ง — แนะนำ (อัปเดตอัตโนมัติ) |
| Windows | `INKATLAS-Portable-x.x.x.exe` | แบบพกพา ไม่ต้องติดตั้ง |
| macOS — Apple Silicon (M1 ขึ้นไป) | `INKATLAS-x.x.x-arm64.dmg` | |

ไฟล์ `latest.yml` / `latest-mac.yml` มีไว้ให้ระบบอัปเดตอ่าน — ไม่ต้องโหลดเอง

---

## ติดตั้ง

### Windows
1. ดับเบิลคลิก `INKATLAS-Setup-x.x.x.exe` — ติดตั้งเสร็จแล้วแอปเปิดเอง
2. ถ้าตัวติดตั้งขึ้นว่า "cannot be closed" ให้ปิด INKATLAS ที่เปิดค้างใน Task Manager ก่อน

### macOS
1. เปิดไฟล์ `.dmg` แล้วลาก **INKATLAS** ไปที่ **Applications**
2. คลิกขวาที่แอป → **Open** (ครั้งแรกต้องเปิดแบบนี้)
3. ถ้าขึ้นว่าแอป "เสียหาย" ให้รันใน Terminal:
   ```
   xattr -cr "/Applications/INKATLAS.app"
   ```

---

## ความต้องการของระบบ

- **Windows** — Windows 10 ขึ้นไป (64-bit)
- **macOS** — macOS 10.15 ขึ้นไป · Apple Silicon

---

ไฟล์ติดตั้งทุกรุ่นสร้างและเผยแพร่อัตโนมัติผ่าน GitHub Actions

© INKREALM
