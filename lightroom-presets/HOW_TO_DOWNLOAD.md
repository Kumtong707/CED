# วิธีการดาวน์โหลดพรีเซ็ต Lightroom

มีหลายวิธีในการดาวน์โหลดไฟล์พรีเซ็ต เลือกวิธีที่สะดวกที่สุดสำหรับคุณ

## 📱 วิธีที่ 1: ดาวน์โหลดจาก GitHub (แนะนำ - ง่ายที่สุด)

### สำหรับมือถือ (iOS/Android):

1. **เปิดลิงก์ branch นี้บนมือถือ:**
   ```
   https://github.com/Kumtong707/CED/tree/cursor/lightroom-ricoh-presets-332c/lightroom-presets
   ```

2. **เลือกไฟล์ที่ต้องการดาวน์โหลด:**
   - เข้าไปในโฟลเดอร์ `japanese-styles/` หรือ `ricoh-gr-iv/`
   - คลิกที่ไฟล์ .xmp ที่ต้องการ (เช่น `Japanese-Soft-Film.xmp`)

3. **กดปุ่ม "Raw" หรือ "Download":**
   - iOS: Long press → "Download Linked File"
   - Android: กดดาวน์โหลด → เลือก "Download"

4. **บันทึกไฟล์:**
   - iOS: บันทึกใน Files app หรือ iCloud Drive
   - Android: บันทึกใน Downloads folder

### สำหรับคอมพิวเตอร์:

1. **เปิดลิงก์นี้:**
   ```
   https://github.com/Kumtong707/CED/tree/cursor/lightroom-ricoh-presets-332c/lightroom-presets
   ```

2. **ดาวน์โหลดแต่ละไฟล์:**
   - คลิกเข้าไปในโฟลเดอร์ `japanese-styles/` หรือ `ricoh-gr-iv/`
   - คลิกที่ไฟล์ .xmp
   - กดปุ่ม **"Download raw file"** (ไอคอนลูกศรลง)
   - หรือ คลิกขวา → "Save as..."

---

## 💻 วิธีที่ 2: ดาวน์โหลดทั้ง Folder (ใช้คอมพิวเตอร์)

### ดาวน์โหลดทั้ง Repository:

1. **ไปที่หน้า branch:**
   ```
   https://github.com/Kumtong707/CED/tree/cursor/lightroom-ricoh-presets-332c
   ```

2. **กดปุ่ม "Code" สีเขียว**

3. **เลือก "Download ZIP"**

4. **แตกไฟล์ ZIP** และเข้าไปในโฟลเดอร์ `lightroom-presets/`

---

## 🔗 วิธีที่ 3: ดาวน์โหลดจาก Pull Request

1. **เปิด PR:**
   ```
   https://github.com/Kumtong707/CED/pull/1
   ```

2. **ไปที่แท็บ "Files changed"**

3. **คลิกที่ไฟล์แต่ละไฟล์:**
   - กดปุ่ม "⋮" (สามจุด) ที่มุมบน
   - เลือก "View file"
   - กด "Download raw file"

---

## 🖥️ วิธีที่ 4: ใช้ Git Clone (สำหรับคนที่ใช้ Git)

```bash
# Clone repository
git clone https://github.com/Kumtong707/CED.git

# เข้าไปใน branch
cd CED
git checkout cursor/lightroom-ricoh-presets-332c

# ไฟล์พรีเซ็ตจะอยู่ใน
cd lightroom-presets/
```

---

## 📦 ลิงก์ดาวน์โหลดแบบตรง (Direct Download)

### Japanese Styles:
```
https://raw.githubusercontent.com/Kumtong707/CED/cursor/lightroom-ricoh-presets-332c/lightroom-presets/japanese-styles/Japanese-Soft-Film.xmp

https://raw.githubusercontent.com/Kumtong707/CED/cursor/lightroom-ricoh-presets-332c/lightroom-presets/japanese-styles/Tokyo-Street.xmp

https://raw.githubusercontent.com/Kumtong707/CED/cursor/lightroom-ricoh-presets-332c/lightroom-presets/japanese-styles/Kyoto-Moody.xmp
```

### Ricoh GR IV:
```
https://raw.githubusercontent.com/Kumtong707/CED/cursor/lightroom-ricoh-presets-332c/lightroom-presets/ricoh-gr-iv/Ricoh-GR-Positive-Film.xmp

https://raw.githubusercontent.com/Kumtong707/CED/cursor/lightroom-ricoh-presets-332c/lightroom-presets/ricoh-gr-iv/Ricoh-GR-Negative-Film.xmp

https://raw.githubusercontent.com/Kumtong707/CED/cursor/lightroom-ricoh-presets-332c/lightroom-presets/ricoh-gr-iv/Ricoh-GR-Snap.xmp
```

**วิธีใช้ลิงก์ตรง:**
- คลิกขวาที่ลิงก์ → "Save Link As..." (บนคอมพิวเตอร์)
- Long press → "Download Linked File" (บนมือถือ)

---

## 📱 ขั้นตอนหลังดาวน์โหลด

### สำหรับ Lightroom Mobile:

**iOS:**
1. เปิด **Files** app
2. หาไฟล์ .xmp ที่ดาวน์โหลดมา (ใน Downloads หรือ iCloud Drive)
3. เปิด **Lightroom Mobile**
4. ไปที่ Presets → กดไอคอน **⋮** (สามจุด)
5. เลือก **"Import Presets"**
6. เลือกไฟล์ .xmp ที่ดาวน์โหลด
7. เสร็จแล้ว! พรีเซ็ตจะอยู่ใน **User Presets**

**Android:**
1. ดาวน์โหลดไฟล์จะอยู่ใน **Downloads** folder
2. เปิด **Lightroom Mobile**
3. ไปที่ Presets → กดไอคอน **⋮** (สามจุด)
4. เลือก **"Import Presets"**
5. เลือกไฟล์จาก Downloads
6. เสร็จแล้ว!

### สำหรับ Lightroom Desktop:

1. เปิด **Lightroom Classic**
2. ไปที่ **Develop Module** (กด D)
3. มองหา **Presets Panel** ทางซ้าย
4. คลิกขวาที่ Presets → เลือก **"Import Presets"**
5. เลือกไฟล์ .xmp ทั้งหมดที่ดาวน์โหลด
6. กด **Import**
7. พรีเซ็ตจะปรากฏใน **User Presets**

---

## ⚠️ สิ่งที่ควรตรวจสอบ

- ✅ ไฟล์ต้องมีนามสกุล **.xmp**
- ✅ ไฟล์ไม่ควรเปลี่ยนชื่อ (ใช้ชื่อเดิม)
- ✅ อย่าเปิดไฟล์ด้วย Text Editor (จะทำให้เสีย)
- ✅ ถ้าดาวน์โหลดแล้วเป็นไฟล์ .txt ให้เปลี่ยนเป็น .xmp

---

## 🎯 แนะนำ

**ดาวน์โหลดแบบไหนดี?**
- 📱 **มือถือ:** ใช้วิธีที่ 1 (ง่ายที่สุด) หรือ ลิงก์ตรง
- 💻 **คอมพิวเตอร์:** ใช้วิธีที่ 2 (Download ZIP) เพื่อได้ทั้งหมดพร้อมกัน
- 🤓 **มีความรู้ Git:** ใช้วิธีที่ 4 (Git Clone)

---

## ❓ แก้ปัญหา

### ไฟล์ดาวน์โหลดเป็น .txt แทน .xmp:
1. เปลี่ยนนามสกุลไฟล์จาก `.txt` เป็น `.xmp`
2. หรือดาวน์โหลดโดยใช้ "Raw" button แทน

### Lightroom ไม่เจอไฟล์:
1. ตรวจสอบว่าไฟล์อยู่ใน folder ที่เข้าถึงได้
2. iOS: ต้องให้ Lightroom เข้าถึง Files app ก่อน
3. Android: ตรวจสอบ permissions

### พรีเซ็ตไม่ทำงาน:
1. ตรวจสอบว่าเป็นไฟล์ .xmp ที่ไม่ได้แก้ไข
2. ลองดาวน์โหลดใหม่อีกครั้ง
3. อาจต้อง restart Lightroom

---

## 💬 ต้องการความช่วยเหลือ?

ถ้ายังมีปัญหา สามารถ:
- เปิด Issue ใน GitHub repository นี้
- หรือติดต่อผ่านทาง Pull Request

---

**สนุกกับการถ่ายภาพ!** 📸✨

อัปเดตล่าสุด: July 2026
