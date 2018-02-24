บริษัทรับจัดหาโรงแรมได้ว่าจ้างคุณที่เป็นโปรแกรมเมอร์ให้พัฒนาแอปค้นหาโรงแรม 
โดยที่เขาต้องการให้ตอนแรกขึ้นบรรทัดว่า Welcome to hotel searching app 
และต้องการให้มีโรงแรม 5 ระดับ ตั้งแต่ 1ดาวถึง-5ดาว โดยใช้ราคาเป็นตัวกำหนดว่าผู้ใช้จะได้โรงแรมกี่ดาวในจำนวนเงินเท่านั้น 
โดยกำหนดให้จำนวนเงินตั้งแต่ 700 บาทลงมา จะไม่สามารถหาห้องได้โดยจะแจ้งว่า 
‘You can’t get any hotel room in this price’ 
และอีกบรรทัดนึงจะขึ้นว่า’If you add more (money) baht,you can get hotel (star) room’ 
คือระบบจะคำนวณเงินที่เหลือถ้าคุณเพิ่มจะได้ห้องระดับดาวต่อไปเท่าไหร่ และกรณีที่เงิน อยู่ในช่วง 700-2000 จะได้ห้องระดับ 1 ดาว , 
เงินในช่วง 2000-3500 จะได้ ห้องระดับ 2 ดาว, เงินในช่วง 3500-5000 จะได้ห้องระดับ 3 ดาว, เงินในช่วง 5000-9000 จะได้ห้องระดับ 4 ดาว,
 และสุดท้ายจำนวนเงินที่มากกว่า 9000 จะได้ห้องระดับ 5 ดาวซึ่งมากสุด และระบบจะขึ้นอีกบรรทัดว่า 
นี้คือระดับโรงแรมที่ดีที่สุดที่เราสามารถหาให้คุณได้แล้ว ‘This is the best thing we can find for you’

Test case 1
Welcome to hotel searching app
---------------------------------------------
Looking for hotel price (baht) : 500
You can’t get any hotel room in this price
If you add more 200 baht,you can get hotel 1 star room
Press ‘0’ to end this program 0
Thank you for using this app	

Test case 2

Welcome to hotel searching app
---------------------------------------------
Looking for hotel price (baht) :  -231
ERROR

Test case 3

Welcome to hotel searching app
---------------------------------------------
Looking for hotel price (baht) :  5788
You can get 4 star hotel
If you add more 3212 baht,you can get hotel 5 star room
Press '0' to end this program2
Welcome to hotel searching app
---------------------------------------------
Looking for hotel price (baht) :  9200
You can get 5 star hotel
This is the best thing we can find for you
Press '0' to end this program 0
Thank you for using this app