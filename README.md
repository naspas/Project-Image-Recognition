# Project-Image-Recognition
# ชื่อกลุ่ม แอนฟิล์ดนรกทีมเยือน
## รายชื่อสมาชิก
  1.
  2.
  3.Naspas hh
  4.
  
## Project 2
### วิธี Run Code
```
python handcraft_based.py
```

ต้องเปลี่ยน directory ที่อยู่ของไฟล์ handcraft_based.py ก่อน ตามที่อยู่ที่เก็บไฟล์ไว้ <br />
หรือ ใช้วิธี “ลากและวาง” ไฟล์ handcraft_based.py ลงใน Anaconda Prompt <br />

โดยจะแบ่งเป็น <br />
  1. Train - โดยใช้ วิธี เมทริกซ์ระดับสีเทาร่วม (Grey Level Co-occurrence Matrix : GLCM) <br />
  2. Test – โดยใช้การค้นหาเพื่อนบ้านที่ใกล้ที่สุด K ตัว (K-Neaerest Neighbors) และ การวัดความคล้ายโดยอาศัยระยะทาง (Distance) โดยใช้ Euclidean ในการแบ่งกลุ่มข้อมูล <br />
<br />
เมื่อ Run เสร็จ จะแสดงผลลัพธ์จากการทำนายของแบบจำลอง โดย Answer is [ผลลัพธ์], <br />
แสดงจำนวนข้อมูลที่ทำนายถูก จากจำนวนข้อมูลที่ใช้ test 30 ตัว (เปลี่ยนจำนวนที่จะใช้ทดสอบได้) <br />
และแสดง Percent ความถูกต้องของการทำนาย <br />

### วิธีการเปลี่ยนรูป Dataset
สำหรับ Train <br />
![path_train](https://imgur.com/AsTOJpX)
