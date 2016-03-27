นี่เป็น Starter Template สำหรับใช้ทำ Workshop ในการเรียนออนไลน์ [สร้าง Cross Platform Mobile App ใน 24 ชม. จากเริ่มต้นจนถึงโปร](https://goo.gl/Cp93BH).

## วิธีใช้เทมเพลตนี้

### สร้างด้วย Ionic CLI:


```bash
$ sudo npm install -g ionic cordova
$ ionic start MyVat7 blank
```

เปิดโปรแกรม Terminal หรือ Command Prompt ขึ้นมาจากโฟลเดอร์ `MyVat7` และรันคำสั่งต่อไปนี้:

```bash
$ ionic platform add ios
$ ionic build ios
$ ionic emulate ios
```

การรันคำสั่งดังกล่าวต้องมีการติดตั้งระบบ iOS SDK และโปรแกรมอื่นๆ ตามที่บอกไว้ใน[คอร์สออนไลน์](https://goo.gl/Cp93BH) ซึ่งเป็นเช่นเดียวกันกับระบบ Android

## ปัญหาที่อาจพบ
หากพบปัญหาทางเทคนิคใดๆ ที่เกี่ยวข้องกับ หรือเกิดจากเทมเพลตนี้ สามารถแจ้งได้ที่ Issue 
