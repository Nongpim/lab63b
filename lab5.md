# การทดลองที่ ๕ เรื่อง การเขียนโปรแกรมเชื่อมต่อไวไฟและเว็บเซอร์เวอร์

## วัตถุประสงค์
1. เพื่อศึกษาการเขียนโปรแกรมเชื่อมต่อไวไฟและเว็บเซอร์เวอร์

## อุปกรณ์ที่ใช้
1. ไมโครคอนโทรเลอร์
2. อุปกรณ์ USB to Serial
3. CPU
4. ตัวโปรแกรมเชื่อมต่อไวไฟและเว็บบราวเซอร์(05_Wifi-Web-Server)

## ศึกษาข้อมูลเบื้องต้น
1. 05 run wifi : https://youtu.be/VX-QNQcO-b4
2. src code ของโปรแกรมเชื่อมต่อไวไฟและเว็บบราวเซอร์(05_Wifi-Web-Server) : https://github.com/choompol-boonmee/lab63b/blob/master/examples/05_Wifi-Web-Server/src/main.cpp
## วิธีการทำการทดลอง
1. นำไมโครคอนโทรเลอร์ไปต่ออุปกรณ์ USB to Serial แล้วเปิด command prompt เพื่อเขียนโปรแกรมเข้าไปในไมโครคอนโทรเลอร์
![image](https://github.com/Nongpim/picture/blob/main/1%E0%B9%83%E0%B8%AB%E0%B8%A1%E0%B9%88.jpg) 
![image](https://github.com/Nongpim/picture/blob/main/2%E0%B9%83%E0%B8%AB%E0%B8%A1%E0%B9%88.jpg)
2. ดูตัวอย่างโปรแกรมที่จะเขียนในโฟลเดอร์ pattani
    * 2.1 พิมพ์คำสั่ง cd pattani เพื่อที่จะเข้าไปยังโฟลเดอร์
      * 2.1.1 ซึ่งในการทดลองนี้จะให้ใช้โปรแกรมตัวอย่างที่ 2 พิมพ์คำสั่ง cd 05_Wifi-Web-Server
      * 2.1.2 พิมพ์คำสั่ง vi src/main.cpp จะแสดงโค้ดของโปรแกรม ซึ่งประกอบไปด้วย 2 ส่วน
        ![image](https://github.com/Nongpim/picture/blob/main/2.1%E0%B9%83%E0%B8%AB%E0%B8%A1%E0%B9%88.jpg)
3. อัปโหลดโปรแกรม 05_Wifi-Web-Server โดยพิมพ์คำสั่ง pio run -t upload
    * 3.1 ในขณะที่รันเพื่อให้ไมโครคอนโทรเลอร์รับโปรแกรมใหม่เข้าไป เราจะต้องกดปุ่มให้โหลด(ปุ่มสีดำ) แล้วกดปุ่มreset(ปุ่มสีแดง) เมื่อโปรแกรมโหลดเข้าไปในคอมพิวเตอร์ตัวจิ๋วนี้แล้ว
4. เมื่อโปรแกรมโหลดเสร็จแล้วจะขึ้นคำว่า SUCCESS ซึ่งต่อไปเราจะใช้คำสั่ง (pio device monitor) แล้วดูผลลัพธ์ที่แสดงผลใน monitor ซึ่งโปรแกรมจะเข้าไปทำงานโดยการค้นหาไวไฟรอบๆตัว

![image](https://github.com/Nongpim/picture/blob/main/2.2%20%E0%B9%83%E0%B8%AB%E0%B8%A1%E0%B9%88.jpg)       ![image](https://github.com/Nongpim/picture/blob/main/2.3%E0%B9%83%E0%B8%AB%E0%B8%A1%E0%B9%88.jpg)
## การบันทึกผลการทดลอง

## อภิปรายผลการทดลอง

## คำถามหลังการทดลอง
