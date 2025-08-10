# Blender Quick Reference Guide 🎨⚡

### [ KEY ]

- `X, Y, Z` = ล็อกการขยับไปตามแกน  
- `G` = Move / Grab  
- `R` = Rotate  
- `S` = Scale  
- `F` = สร้างหน้า (Face) จาก Vertex/Edge ที่เลือก  

### [ COMBO ]

- `Shift + Alt + Click` = เลือกหลายๆ Edge Loop / Face Loop ได้พร้อมกัน!  

### [ SETTINGS ]

**Navigation**  
Edit → Preferences → Navigation → Orbit Around Selection  
- หมุนมุมกล้องรอบ object ที่เลือกอยู่ (ไม่หลุดโฟกัสเวลา zoom)  

**⚡ Performance**  
Preferences → System → Cycles Render Devices  
- เลือก GPU (เช่น RTX 4060 เปิด CUDA / OptiX ให้เต็มแม็ก)  
Undo Steps: 64+ (Preferences → System)  
- ป้องกันกด Ctrl+Z ไม่พอ  
ปิด Auto Save Timer หรือปรับให้ยาวขึ้น (File → Save & Load)  
- ถ้าเครื่องแรงอยู่แล้ว จะได้ไม่ lag ตอนเซฟ background  

**🖌️ Modeling & Shading**  
Preferences → Add-ons → Node Wrangler  
- โครต must-have! ต่อ node shader ง่ายมาก แค่ Ctrl+Shift+Click ก็ preview ได้  
Extra Objects Add-on  
- เพิ่ม primitive พวก Gears, Pipes, Diamonds ให้เลือกสร้างได้ไว  
Snap → Increment / Vertex / Face + เปิด Absolute Grid Snap  
- ถ้าทำงานแบบสถาปัตย์  

**🎥 Rendering & Output**  
Render → Color Management → View Transform → Standard  
- ถ้าทำ anime shader สีจะไม่เพี้ยน (Filmic มันจะ wash-out สี)  
ตั้ง Default Output Folder ให้เป็นโฟลเดอร์ project  
- เพื่อป้องกัน render หาย  

**🪄 Quality of Life**  
Preferences → Keymap → Spacebar Action = Search  
- เรียก command ได้ไวกว่าเมนู  
เปิด Emulate Numpad  
- ถ้าใช้ laptop ไม่มี numpad  
เปลี่ยน Theme ให้สบายตา  
- (บางคนใช้ dark flat หรือ custom pastel tone)  

---

✨ ขอให้ Blender โชคดี มีแต่โมเดลสวยๆ งานปังๆ ค่ะ! ✨  
