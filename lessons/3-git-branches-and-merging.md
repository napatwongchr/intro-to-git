## Git Branches And Merging 

### Git Branches

Git สามารถที่จะทำการแตก Branch ออกมาจาก Branch เดิมได้ เพื่อที่ทำให้เราพัฒนา software ในทีมได้ง่ายมากยิ่งขึ้น และเพิ่มความคล่องตัวในการทำงานของตัวเราเอง

ยกตัวอย่างเช่น เรามี requirement เกี่ยวกับ feature login ที่ต้องทำ เราก็แตก branch ออกมาจาก branch หลักเพื่อทำ feature นี้ สมมติว่ามีสถานการที่ต้องรีบเอา feature อื่น ๆ ขึ้นไปให้ users ใช้งานก่อนเราก็แค่สลับไป branch อื่นที่เราสร้างไว้ แล้วค่อยกลับมาทำให้เสร็จ

![Git branches](./images/git-branches.png)


### Git Merging

เมื่อเราทำ feature เสร็จเรียบร้อยแล้ว เราต้องการที่จะรวม code กลับเข้าไปที่ branch หลัก ให้เราทำการ merge

การ merge นั้นสามารถทำให้เกิด **"Merge conflicts"** กันเนื่องจากเราอาจจะบังเอิญไปแก้โค้ดบางส่วนของไฟล์เดียวกันกับของเพื่อนในทีม Git จะมองเห็น Merge conflicts ตรงนี้แล้วให้เราเป็นคนแก้ไขโค้ดส่วนที่ conflicts กันว่าเราจะเอาโค้ดส่วนไหนของใคร

![Git merging](./images/git-merging.png)

[ไปเนื้อหาต่อไป](https://github.com/napatwongchr/intro-to-git/blob/main/lessons/4-remote-repository.md)

[ย้อนกลับไป](https://github.com/napatwongchr/intro-to-git/blob/main/lessons/2-how-git-works.md)
