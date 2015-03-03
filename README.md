# oscommerce
การเชื่อมต่อกับ software oscommerce 

Payment Module ในการติดต่อ ThaiEPay

       การเชื่อมต่อกับ software oscommerce ปกติแล้วมีให้ download ทั่วไปจาก 
http://www.oscommerce.com ซึ่งมี module ให้ใช้งานมากมาย
      module ของ thaiepay นั้นได้มาจากการนำ module payment secpay มาทำการปรับปรุ่งแก้ไข โดยมีรายละเอียด
ประกอบด้วย 2 แฟ้มข้อมูล
      - thaiepay.php
      - thaiepay.php

     การติดตั้งนั้นทางบริษัทได้ทำการวางโครงสร้างของแฟ้มข้อมูลให้แล้วตามแฟ้มข้อมูลที่ได้ ดังนี้ 

     แฟ้ม thaiepay.php เก็บอยู่ใน diretory /includes/modules/payment/ ซึ่งเป็นแฟ้มที่ใช้ประมวลผลตลอดจนส่งรายละเอียดต่าง ๆ ให้กับระบบ ThaiEPay 
     แฟ้ม thaiepay.php เก็บอยู่ใน diretory /includes/languages/english/modules/payment/

*หมายเหตุ

- ในที่นี้ ทำการยกตัวอย่างในกรณีที่ oscommerce มีการ install ด้วยภาษาอังกฤษภาษาเดียว กรณีที่มีหลายภาษาต้องทำการนำแฟ้มนี้ไปวางไว้ทุก ๆ ภาษาด้วย เช่น
ภาษาไทย thaiepay.php เก็บอยู่ใน diretory /includes/languages/thai/modules/payment/ เป็นต้น

- /includes/modules/payment/thaiepay.php เป็นแฟ้มข้อมูลที่กำหนดค่าต่าง ๆ ในการส่งค่าต่าง ๆให้กับ ThaiEPay  ท่านสามารถกำหนดสกุลเงิน ได้จากแฟ้มนี้ โดยค่าที่ทำการกำหนดต้องเป็นไปตามการข้อกำหนด ซึ่งกำหนดผ่าน oscommerce configuration
  
 

