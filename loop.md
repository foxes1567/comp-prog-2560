คุณได้รับการว่าจ้างให้ไปติดตั้งโปรแกรมที่ตู้เกมarcade แห่งหนึ่ง
โดยเจ้าของต้องการให้รูปแบบเกมเป็น คนต่อสู้กับบอส โดยที่มีระดับความยากอยู่ด้วยกัน
3 ระดับ 1.boss easy ในกรณีนี้ boss จะมีเลือดอยู่ที่ 250 hp 2.boss normal ในกรณีนี้
boss จะมีเลือดอยู่ที่ 500 hp 3.boss hard ในกรณีนี้boss จะมีเลือดอยู่ที่ 1000 hp แต่ถ้าเลือกระดับ
ความยากนอกเหนือจากนี้ระบบจะขึ้นว่า 'Error' โดยเจ้าของยังต้องการอีกว่าให้โอกาสผู้เล่นในการกำจัดboss ตัวนี้
แค่10ครั้งถ้าเกินจากนี้จะมีคำสั่งขึ้นมาว่า "Ah! unfortunate you were killed by big boss"
พร้อมกับบอกเลือดที่บอสเหลืออยู่ โดยในกรณีที่สามารถกำจัดบอสได้ก่อน	10 ครั้งจะขึ้นว่า "Congratulation u win
againts big boss" โดยในแต่ละครั้งที่โจมตีจะขึ้นสถานะเลือดและความเสียหายที่เราสร้างตลอดรวมถึงโอกาสที่เหลืออยู่




Test case 1

boss easy -250hp ,Boss normal - 500hp , Boss hard -1000hp
Select boss skills (1-easy 2-normal 3-hard) : 1

You got 10 chance to finish this boss
Attack damage : 200
You hit 200 so boss have 50 left and u got 9 more chance
Attack damage : 50
Congratulation u win againts big boss

Test case 2

boss easy -250hp ,Boss normal - 500hp , Boss hard -1000hp
Select boss skills (1-easy 2-normal 3-hard) : 7

Error

Test case 3
boss easy -250hp ,Boss normal - 500hp , Boss hard -1000hp
Select boss skills (1-easy 2-normal 3-hard) : 3

You got 10 chance to finish this boss
Attack damage : 4
You hit 4 so boss have 996 left and u got 9 more chance
Attack damage : 200	
You hit 200 so boss have 796 left and u got 8more chance
Attack damage : 1
You hit 1 so boss have 795 left and u got 7 more chance
Attack damage : 1		
You hit 1 so boss have 794 left and u got 6 more chance
Attack damage : 1
You hit 1 so boss have 793 left and u got 5 more chance
Attack damage : 1
You hit 1 so boss have 792 left and u got 4 more chance
Attack damage : 1
You hit 1 so boss have 791 left and u got 3 more chance
Attack damage : 1
You hit 1 so boss have 790 left and u got 2 more chance
Attack damage : 1
You hit 1 so boss have 789 left and u got 1 more chance
Attack damage : 1
Ah! unfortunate you were killed by big boss(boss have 788 hp left)

