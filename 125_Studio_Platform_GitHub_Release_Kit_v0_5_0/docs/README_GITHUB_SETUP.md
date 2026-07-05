# 125 Studio Platform - GitHub Update Setup

## 1) สร้าง Repository
ตั้งชื่อแนะนำ: `125-studio-platform`

## 2) อัปโหลดไฟล์
อัปโหลดโฟลเดอร์นี้ขึ้น GitHub:

- `release_manifest/manifest.json`
- ไฟล์ `.rbz` แต่ละเวอร์ชันในหน้า Releases

## 3) แก้ manifest.json
เปลี่ยน `YOUR_USERNAME` เป็นชื่อ GitHub ของคุณจริง

ตัวอย่าง Manifest URL ที่นำไปใส่ใน Extension:

```text
https://raw.githubusercontent.com/YOUR_USERNAME/125-studio-platform/main/release_manifest/manifest.json
```

## 4) วิธีทดสอบใน SketchUp
1. เปิด 125 Studio Platform
2. ไปที่ Settings
3. ใส่ Manifest URL
4. กด Save Settings
5. ไปที่ Update Center
6. กด Fetch Online Manifest
7. กด Check Updates
8. กด Download/Update ที่โมดูลที่ต้องการ

## 5) การปล่อยเวอร์ชันใหม่
1. สร้างไฟล์ `.rbz` ใหม่
2. Upload ไปที่ GitHub Releases
3. Copy ลิงก์ดาวน์โหลด
4. แก้ `latest_version` และ `rbz_url` ใน `manifest.json`
5. ผู้ใช้กด Check Updates ได้ทันที
