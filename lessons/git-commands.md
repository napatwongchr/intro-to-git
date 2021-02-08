# Git commands

1. คำสั่งสร้าง Git repository

`git init`

2. คำสั่งดู status ของการเปลี่ยนแปลง code ใน repo

`git status`

3. คำสั่ง add ไฟล์ที่เปลี่ยนแปลงไปเพื่อที่จะเตรียม commit

`git add <files>`

ตัวอย่าง

`git add .` จะทำการ add ไฟล์ที่เปลี่ยนแปลงทั้งหมด

4. คำสั่ง commit ไฟล์ที่เปลี่ยนแปลงทั้งหมดพร้อมกับ commit message เพื่ออธิบาย commit ว่าเราทำอะไรใน commit นี้บ้าง

`git commit -m “commit message”`

5. คำสั่งเลือก commit ที่จะไปอยู่

`git checkout <commit_id>`

6. คำสั่งดู log ของการเปลี่ยนแปลงไฟล์ทั้งหมดใน repo

`git log --graph --decorate --oneline --all`

7. คำสั่ง merge branch

`git merge <branch_name>`

8. คำสั่งแสดงรายชื่อ branch

`git branch`

9. คำสั่งลบ branch

`git branch -d <branch_name>`

10. คำสั่ง clone repo

`git clone <repo_url>`

11. คำสั่ง download ข้อมูลที่เกี่ยวข้องกับ repo ที่เราใช้ download จาก github

`git fetch`

12. คำสั่ง download code จาก repo ที่เราใช้ download ลงมาจาก github

`git pull`

13. คำสั่ง upload code ขึ้นไปบน github repo

`git push`

14. คำสั่ง link repo บนเครื่องเราเข้ากับ repo บน github

`git remote add origin <repo_url>`

15. คำสั่ง push branch ขึ้นไปบน repo

`git push -u origin master`
