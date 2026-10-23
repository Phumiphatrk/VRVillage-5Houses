# VRVillage-5Houses

บ้าน 5 หลังของ 67011643 สำหรับโปรเจกต์ VR Village (Unity 6000.3.19f1, URP, XR Interaction Toolkit 3.5.1)

ดาวน์โหลดไฟล์ `67011643_5Houses.unitypackage` แล้วทำตามวิธีด้านล่าง

```
5 บ้านของ 67011643 - วิธีใส่ลงหมู่บ้าน
==========================================

ไฟล์: 67011643_5Houses.unitypackage

1) นำเข้า
   Unity > Assets > Import Package > Custom Package... > เลือกไฟล์นี้ > Import ทั้งหมด
   ทุกอย่างอยู่ในโฟลเดอร์ Assets/RamenVR
   ต้องมีในโปรเจกต์: URP, XR Interaction Toolkit 3.x, XR Origin rig จาก Starter Assets (มีระบบ teleport)

2) วางบ้าน
   ลาก prefab จาก Assets/RamenVR/Prefabs ลงฉากหมู่บ้าน:
     1_RiceShowerRamen     ร้านราเมน
     2_KaiPlaNaJa          ร้านปลา
     3_RaiKaiTod           ฟาร์มไก่
     4_DokTong             ร้านดอกไม้
     5_SuanTonMaiKongPoa   สวนสาธารณะ
   ย้ายตำแหน่งและหมุนได้ตามใจ (ระบบจะหมุนตามบ้านเอง) แต่อย่าเปลี่ยน scale (ปล่อยเป็น 1)
   บ้านแต่ละหลังมีของครบในตัว: เกม 10 ขั้น, ป้ายเช็กลิสต์, เสียง และ UI
   ไม่ต้องตั้งค่าอะไรเพิ่ม และไม่ต้องลาก script ใส่เอง
   ถ้าลบ child ของ prefab ทิ้ง บางขั้นอาจกดไม่ผ่าน

3) ปุ่มหยิบของ
   ในโปรเจกต์ของเรา trigger (ปุ่มนิ้วชี้) ใช้หยิบของได้ด้วย เพราะเพิ่ม binding trigger -> Select
   ไว้ใน XRI Default Input Actions (Starter Assets)
   ถ้าโปรเจกต์นายไม่มี binding นี้ ให้ใช้ปุ่ม grip (ปุ่มข้าง) หยิบแทน ใช้ได้เหมือนกัน

4) อย่ากดเมนู "Ramen VR" ในแถบบนของ Unity
   เป็นเครื่องมือตอนสร้างบ้าน ถ้ากดอาจสร้างบ้านใหม่ทับ

5) ก่อน export APK (ตามที่อาจารย์บอก)
   - ลบหรือปิด object "XR Interaction Simulator"
   - Company Name = "Group #"  /  Product Name = ชื่อหมู่บ้านแบบ TitleCase
   - Platform = Android
```
