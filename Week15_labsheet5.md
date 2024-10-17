# การทดลอง
## Actions บน github

- ใบงานนี้จะทำการ test บน github โดยใช้ action 


## การเตรียมการเบื้องต้น
- เตรียม classlibrary project ที่ผ่านการทดลองใช้บน console application และผ่านการทำ test มาแล้ว 

## การสร้าง unit test project
1. Push โปรเจคทั้งหมดขึ้นบน github

![alt text](./Pictures/image-42.png)

2. คลิกที่ Actions

![alt text](./Pictures/image-43.png)

3. คลิกที่ Configure

![alt text](./Pictures/image-44.png)

4. จะได้หน้าจอแบบนี้

![alt text](./Pictures/image-45.png)

5. คลิก `Commit Changes...` และ commit จนเสร็จ

6. คลิก Action อีกครั้ง จะเห็นว่า github กำลัง test โปรเจคที่เพิ่มเข้าไป ให้รอจนทดสอบเสร็จ

7. จะพบว่ามี error เนื่องจากยังไม่ได้แก้ไข template ให้ตรงกับชื่อโปรเจค ให้แก้ไขให้ถูกต้องและทดสอบจนผ่าน


**ตัวอย่าง Actions**
https://github.com/koson/demo_classlib/actions


**ตัวอย่างไฟล์ workflow `dotnet-desktop.yml`**
https://github.com/koson/demo_classlib/actions/runs/11393214123/workflow

