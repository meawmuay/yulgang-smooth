# วิธีปรับ Yulgang ให้ลื่นหัวแตก ฉบับง่าย โดย แมวหมวย (NVIDIA) 
## หมายเหตุ
เนื่องจาก Yulgang เป็นเกมที่ถูกสร้างมานานมากแล้ว ทำให้ Nvidia ไม่สามารถตรวจจับได้ว่าต้องประมวลกราฟฟิก ตัวเกมจึงไปใช้งาน CPU ประมวลผลแทน ทำให้เมื่อเราเปิดเกมเล่นปกติ ตัวเกมจะใช้งาน CPU ค่อนข้างมาก

วันนี้เราจะมาสอนวิธีทำให้ ตัวเกมไปใช้งาน GPU แทน

## วิธีทำ
1. โหลด [GEFORCE EXPERIENCE คลิก](https://www.nvidia.com/en-us/geforce/geforce-experience/download/)
2. ติดตั้งให้เรียบร้อย
3. เปิดโปรแกรม\
   ![](https://i.imgur.com/Z3z5jf6.png)

4. เมื่เปิดโปรแกรมา จะเจอหน้าจอให้เข้าสู่ระบบ
5. สามารถเลือกสมัครหรือ Login in with Facebook หรือ Login in with Google
6. ถ้าเลือกสมัครให้คลิกที่นี่\
   ![](https://i.imgur.com/JbBFcz7.png)

7. กรอกข้อมูลสมัครให้เรียบร้อย
8. หลังจากสมัครแล้ว คุณจำเป็นต้องยืนยันอีเมลด้วย เข้าอีเมลที่สมัครไว้เพื่อยืนยัน
9. หลังจากนั้น เข้าสู่ระบบตามไอดีที่สมัครไว้ จะพบหน้าจอหลัก คลิกที่ DRIVERS\
    ![](https://i.imgur.com/fHdULKU.png)

10. คลิกที่ CHECK FOR UPDATES\
    ![](https://i.imgur.com/SD93YBa.png)

11. หากมีให้อัปเดต ก็กด DOWNLOAD และกด EXPESS INSTALL แล้วกดติดตั้งให้เรียบร้อย
12. มาที่หน้าจอ คลิกขวาเลือก NVIDIA Control Panel\
    ![](https://i.imgur.com/8s9p62J.png)

13. เลือกที่เมนูด้านซ้าย Manage 3D Settings
14. เลือกที่ Tab Program Settings แล้วเลือก Add\
    ![](https://i.imgur.com/PWu7nWm.png)

15. คลิกที่ Browse... แล้วเลือกไฟล์ YGOnline.exe ที่อยู่ใน Playpark\Yulgang\client\
    ![](https://i.imgur.com/3XXwylP.png)

    ![](https://i.imgur.com/q56dxIi.png)

16. คุณสามารถเลือกปรับค่าใน กรอบ 4 เหลี่ยมได้ แต่จะไม่ตั้งก็ได้โดยมันจะอ้างอิงจากค่าหลัก (อย่าตั้งตามในภาพ!)\
    ![](https://i.imgur.com/lqdMbUu.png)

17. ยินดีด้วย ตอนนี้คุณสามารเข้าเล่นเกมแบบลื่น ๆ ได้แล้ว
18. แต่เดี่ยวก่อน หากคุณเข้าเล่นแล้วไม่ลื่นแบบก่อนหน้า คุณสามารถกดปุ่ม Remove ในหน้าต่างนี้ได้เลย\
    ![](https://i.imgur.com/juEdH7H.png)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
