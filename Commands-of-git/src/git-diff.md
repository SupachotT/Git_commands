# คำสั่ง diff
คำสั่ง `diff` เป็นคำสั่งที่จะแสดงความแตกต่างของไฟล์ระหว่าง Working directory กับ Staging area ที่กำลังทำงานอยู่

เราจะใช้คำสั่ง `diff` ในรูปแบบดังนี้
```
git diff
```

- ตัวอย่างการแสดงการเปลี่ยนแปลงต่อไฟล์ที่ระบุ:

    ```
    git diff file1.ts
    ```

    แทนที่ `file1.ts` ด้วยชื่อไฟล์หรือที่อยู่ของไฟล์ที่ต้องการ

- แสดงการเปลี่ยนแปลงระหว่าง branches master และ develop:

    ```
    git diff main..new_feature
    ```
    คำสั่งนี้จะเป็นการแสดงความแตกต่างระหว่าง 2 branch จากนั้นตั้วอย่างจะเป็น branch 'main' กับ 'new_feature'