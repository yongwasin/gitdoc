# Lottery

ในส่วนนี้เราจะมากล่าวถึง Lottery กัน โดยที่เราจะกล่าวถึงนี้เป็นเรื่องของ address กันครับ address ที่เรากล่าวถึงนั้นจะอยู่ใน path ต่อไปนี้ src/config/constants/contracts.ts โดยจะมี code ที่เป็น address ดังนี้

```text
lotteryV2: {
    97: '0x5790c3534F30437641541a0FA04C992799602998',
    56: '0x5aF6D33DE2ccEC94efb1bDF8f92Bd58085432d2c',
  }
```

สิ่งที่เราต้องทำการดำเนินการแก้ไข หรือเพิ่มเติมลงไปนั่นก็คือ chain id และ address ที่มีการ deployed ในส่วนนี้ ต่อมาเราจะมาพูดถึงรูปแบบของ code ที่เราจะต้องทำการเพิ่มเติมลงไปกันครับโดย code ที่เราจะทำการเพิ่มลงไปนั้นจะมีรูปแบบดังต่อไปนี้

```text
chain id : 'address',
```

เมื่อเรารู้รูปแบบของ code ที่เราจะต้องทำการเพิ่มลงไปนะครับ โดยเมื่อเราได้ทำการเพิ่มเติมหรือแก้ไขเสร็จสิ้นแล้ว code ทั้งหมดในส่วนนี้จะมีลักษณะนี้ครับ

```text
lotteryV2: {
    97: '0x5790c3534F30437641541a0FA04C992799602998',
    56: '0x5aF6D33DE2ccEC94efb1bDF8f92Bd58085432d2c',
    25925: '0x73feaa1eE314F8c655E354234017bE2193C9E24E'
  }
```

เพียงเท่านี้ การดำเนินการแก้ไขการเปลี่ยน address ในส่วนของ Lottery ก็จะเสร็จสิ้นแล้วครับ
