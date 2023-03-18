# Online-Article1
assigment 240-311 web Online-Article(Front-end , Back-end)

สมาชิกในกลุ่ม
นาย ชาคริต ภูวมุกดา รหัส 6310110107 รับผิดชอบ Back end, Data base
นาย อัฟฎ็อล หีมเห็ม รหัส 6310110576 รับผิดชอบ Front end


อธิบายการทำงาน
สร้างเว็บไซต์สำหรับโพสต์บทความออนไลน์ได้(ก่อน login จะสามารถเห็นบทความที่ผู้อื่นโพสต์ได้แต่ไม่สามารถโพสต์บทความของตัวเองได้)
![h](https://user-images.githubusercontent.com/128234855/226118787-beed49f2-781a-4b6a-b867-3f373c0eee4b.png)

หากต้องการโพสต์บทความของตนเอง ต้องทำการ login เข้าสู่ระบบก่อน(ซึ่งต้องสมัครบัญชีผู้ใช้)
![re](https://user-images.githubusercontent.com/128234855/226119284-b41f63f0-21f4-4c60-b8ea-846f4b0c3ccb.png)
![lo](https://user-images.githubusercontent.com/128234855/226119242-e629d5e3-1d98-4b9c-b221-d016120eef6e.png)

เมื่อ login แล้วจึงสามารถโพสต์ แก้ไข และลบบทความของตนเองได้
![l](https://user-images.githubusercontent.com/128234855/226118821-7099203b-fc34-459c-ac70-345052361067.png)
![c](https://user-images.githubusercontent.com/128234855/226118869-4efb2597-983a-4387-a6ff-429feaa83637.png)


ใช้ฐานข้อมูล MongoDB ในการจัดทำโดยแบ่งออกเป็น 2 ส่วน ได้แก่
1.ใช้สำหรับจัดเก็บข้อมูล username,password ที่ผู้ใช้ใหม่ทำการสมัครเข้ามา(เพื่อนำไปตรวจสอบในการ login)

2.ใช้สำหรับจักเก็บข้อมูลที่ผู้ป้อนเข้ามา (หัวข้อบทความ, รายละเอียดบทความ , รูปภาพ)
![m](https://user-images.githubusercontent.com/128234855/226119167-e3bf3b9a-efcf-4b44-9490-29bbec37011f.png)

