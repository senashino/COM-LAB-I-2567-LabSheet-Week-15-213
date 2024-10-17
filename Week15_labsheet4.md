# การทดลอง
## การรัน unit test บน console application โดยใช้ Visual Studio Code (ตอนที่ 2)

- ใบงานนี้จะทำการ รัน unit test บน  .NET console application โดยใช้ Visual Studio Code
- เพื่อให้โปรแกรมสามารถ reuse ได้ เราจะทดลองสร้างเป็น class library ซึงสามารถเรียกใช้ได้จากทั้งโปรแกรมแบบ console application, mobile application หรือ web application


## การเตรียมการเบื้องต้น
- เตรียม classlibrary project ที่ผ่านการทดลองใช้บน console application มาแล้ว 

## การสร้าง unit test project
1. สร้าง project ใหม่โดยเลือกชนิดเป็นดังรูป

![alt text](./Pictures/image-35.png)

2. ตั้งชื่อ project
   
![alt text](./Pictures/image-36.png)

3. เลือกที่ตั้ง project

![alt text](./Pictures/image-37.png)

4. สร้าง test project จนเสร็จ เปิดไฟล์ CalcLibTest.csproj ควรพบข้อความ  `<TargetFramework>net8.0</TargetFramework>`
  
5. เพิ่ม reference project ให้กับ CalcLibTest โดยเลือก CalculatorLibrary

![alt text](./Pictures/image-38.png)

6. แก้ code ใน UnitTest1.cs เป็นดังต่อไปนี้

![alt text](./Pictures/image-39.png)


7. เลือกหน้าต่าง Test

![alt text](./Pictures/image-40.png)


8. Run Test with coverage

![alt text](./Pictures/image-41.png)

