# Windows WIFI Hotspot
- - -
แชร์ไวไฟอย่าง่าย

### การตั้งค่า
- - -
เปิดไฟล์ชื่อว่า **config_hotspot.bat** (เปิดโดยใช้ notepad)
> netsh wlan set hostednetwork **ssid**=My_WIFI **key**=password mode=allow 

สามารถแก้ไขชื่อไวไฟได้จาก
>ssid=**My_WIFI**(เปลี่ยนเป็นชื่อที่คุณต้องการ)

สามารถแก้ไขรหัสผ่านได้จาก
>key=**password**(เปลี่ยนเป็นรหัสที่คุณต้องการ)

### เปิดใช้งาน
- - -
ดับเบิ้ลคลิก **start_hotspot.bat** 

![alt tag](https://www.img.in.th/images/9e81227d0e4bc65cd8156c5547d07e58.png)

### ปิดใช้งาน
- - -
ดับเบิ้ลคลิก **stop_hotspot.bat**

