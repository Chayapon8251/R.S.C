# R.S.C
Physical Computing Project 2024 - IT KMITL Project
Project นี้เป็นส่วนหนึ่งในรายวิชา PHYSICAL COMPUTING 06016409 ภาคเรียนที่ 1 ปีการศึกษา 2566 ของคณะเทคโนโลยีสารสนเทศ สาขาเทคโนโลยีสารสนเทศ สถาบันเทคโนโลยีพระจอมเกล้าเจ้าคุณทหารลาดกระบัง

## บทคัดย่อ
Project นี้เป็นการบูรณาการในการใช้งาน Microcontroller ในรายวิชา PHYSICAL COMPUTING โดยเป็นการทำเป็น Hardware สำหรับระบบตรวจจับความสว่างของแสง โดยหากปริมาณแสงสว่างที่ตัวเซ็นเซอร์ตรวจพบมีความสว่างมากเกินกว่าค่าที่กำหนดจะส่งผลให้สัญญาณแจ้งเตือนปริมาณแสงเกินกำหนดดังขึ้น และสามารถหยุดการทำงานของสัญญาณแจ้งเตือนได้โดยการใส่รหัสผ่านที่ถูกต้องลงบนอุปกรณ์ Keypad โดยจะมีอุปกรณ์ที่ใช้งานใน Project ดังกล่าวทั้งหมดดังนี้

## อุปกรณ์ที่ใช้งาน
* #### Arduino UNO
> ![Arduino Uno Screenshot](https://github.com/pprwf/PhyCom-Project__LightIntensityAlarm__/blob/main/Picture/Arduino%20Uno.png "Arduino Uno")

* #### Breadboard
> ![Breadboardd Screenshot](https://github.com/pprwf/PhyCom-Project__LightIntensityAlarm__/blob/main/Picture/Breadboard.png "Breadboard")

* #### Buzzer       
> ![Buzzer Screenshot](https://github.com/pprwf/PhyCom-Project__LightIntensityAlarm__/blob/main/Picture/Buzzer.png "Buzzer")

* #### Push Button
> ![Push Button Screenshot](https://github.com/pprwf/PhyCom-Project__LightIntensityAlarm__/blob/main/Picture/Red%20Push%20Button.png "Button")

* #### Light Sensor
> ![(Seeed Studio) Grove - Light Sensor Screenshot](https://github.com/pprwf/PhyCom-Project__LightIntensityAlarm__/blob/main/Picture/Grove%20-%20Light%20Sensor.png "Light Sensor")

* #### Laser Transmitter
> ![(ky-008) Laser Transmitter Screenshot](https://github.com/pprwf/PhyCom-Project__LightIntensityAlarm__/blob/main/Picture/Laser%20Transmitter.png "Laser")


## VDO สาธิตการใช้งานโปรเจค
<video width="630" height="300" src="https://github.com/pprwf/PhyCom-Project__LightIntensityAlarm__/assets/109953609/03a49f24-4509-4754-8728-e520c8ac2526"></video>
[YouTube](https://youtu.be/GNzjRTAWlpY "Project Video Demo")

## POSTER 
![Poster Show](https://github.com/pprwf/PhyCom-Project__LightIntensityAlarm__/blob/main/Poster/LightAlarm_Pic.png "Post Pic")
[Poster](https://github.com/pprwf/PhyCom-Project__LightIntensityAlarm__/blob/main/Poster/LightAlarm_Print.pdf "Poster")

## Library ที่ใช้งาน
```c++

```

## การตั้งค่าตัวแปรและ Pin
```c++

```

## ฟังก์ชันที่สำคัญ
* ฟังก์ชันการเปิดปิด Laser ด้วย Push Button
```c++

  ```
* ฟังก์ชันการเปิดใช้งาน Keypad
```c++

```
* ฟังก์ชันการรับรหัสผ่านจาก Keypad
  * ในที่นี้ รหัสผ่านที่ใช้ในการปิดเสียง Buzzer คือ "A68#"
```c++

```

## สมาชิกผู้จัดทำ
| ชื่อ - นามสกุล | รหัสนักศึกษา |
| -------- | ------- |
| นายธนาวัลย์ แช่มเสถียร | 65070099 |
| นายปรเมษฐ์ เชื้อทอง | 65070130 |
| นายพีรวิชญ์ พิชญธาดาพงศ์ | 65070162 |
| นายภาคิน จันทร์จำลอง | 65070174 |
