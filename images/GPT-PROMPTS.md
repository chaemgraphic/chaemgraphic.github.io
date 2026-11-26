# งานรูปสำหรับ GPT — เว็บ "ติดตามงานออกแบบ" (กราฟฟิกชะเอม)

ผู้ทำ: GPT (สร้างรูป) · ผู้ใส่รูปเข้าเว็บ: ชะเอม (โหมดเจ้าของร้าน → "ตกแต่งหน้าเว็บ") หรือส่งไฟล์ให้ Claude อัปโหลด
บันทึกไฟล์ที่ได้ไว้ในโฟลเดอร์นี้: `E:\AI-Workspace\Customer-Tracking\design-tracker\images\`

โทนเว็บเดิม (ต้องเข้ากัน): พื้นขาวอมเทาอ่อน #f7f7f8 / ตัวอักษรดำ #111113 / สีทองแชมเปญ #b08d57 (โหมดมืด พื้น #0c0c0e ทอง #c9a96e)
เว็บจะวางม่านสีพื้นทับรูปพื้นหลังประมาณ 85% อยู่แล้ว ดังนั้นรูปไม่ต้องจาง แต่ห้ามมีจุดเด่นตรงกลางที่แย่งข้อความ

---

## 1) รูปพื้นหลัง — `bg-light.jpg`
- ขนาด 2400×1600 px (แนวนอน 3:2) JPG
- ห้ามมีตัวอักษร โลโก้ ตัวเลข หรือคน

Prompt (วางใน ChatGPT ได้เลย):
```
Wide 3:2 abstract background for a sportswear graphic-design studio website.
Close-up macro of white athletic jersey mesh fabric with a soft diagonal fold,
subtle champagne-gold (#b08d57) thread stitching curving across the top-right corner,
very light off-white palette (#f7f7f8), soft diffused studio light, shallow depth of field,
calm empty area in the center and left for text, minimal, elegant, high-end.
No text, no logos, no numbers, no people. 2400x1600.
```

## 2) รูปพื้นหลังโหมดมืด (ถ้าต้องการ) — `bg-dark.jpg`
```
Same composition as before but dark: charcoal black athletic jersey mesh fabric (#0c0c0e),
fine champagne-gold (#c9a96e) stitching in the top-right corner, low-key lighting,
calm empty center, no text, no logos, no people. 2400x1600.
```
หมายเหตุ: ตอนนี้เว็บรับรูปพื้นหลังได้ 1 รูป ใช้กับทั้งสองโหมด ถ้าอยากแยกสว่าง/มืด แจ้งลิสเพิ่มช่องให้

## 3) โลโก้ / ไอคอน — `logo.png`
- 1024×1024 px PNG พื้นโปร่งใส สี่เหลี่ยมจัตุรัส
- ต้องอ่านออกเมื่อย่อเหลือ 32 px (ใช้เป็นไอคอนแท็บด้วย)

```
Minimal flat vector logo mark for "Graphic Chaem", a sports jersey design studio.
A simple jersey (t-shirt) silhouette combined with a pen nib or diamond shape,
two colors only: ink black #111113 and champagne gold #b08d57,
bold clean geometry, no gradients, no text, centered on a transparent background,
readable at 32px favicon size. 1024x1024 PNG.
```

---

## ตรวจก่อนส่ง
- [ ] ไม่มีตัวอักษร/ลายน้ำ/โลโก้แบรนด์อื่นติดมา
- [ ] พื้นหลังโทนอ่อน ตรงกลางโล่ง
- [ ] โลโก้พื้นโปร่งใสจริง (ไม่ใช่ลายตารางหมากรุก)
- [ ] ตั้งชื่อไฟล์ตามด้านบน
