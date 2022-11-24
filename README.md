# sstv_matlab
sstv with app designer in matlab 
 
Graphical User Interface ของ Program
GitHub ของโปรแกรม : https://github.com/nawatc/sstv_matlab



# การใช้งานโปรแกรม หลังจาก Run Program ด้วย MATLAB

1.	กดปุ่ม Import Image file เพื่อเลือกไฟล์ที่จะแปลงเป็นสัญญาณเสียง
(โดยไฟล์ที่เลือกจะต้องเป็น PNG file และมีขนาด pixel มากกว่า 
line * column ของ mode (มากกว่า pixel แนวนอน * pixel แนวตั้ง) )
เช่น mode Martin M1 ไฟล์ต้องมีขนาดใหญ่กว่า 320*256 (V_pixel * H_pixel)
 
2.	กดปุ่ม Generate

3.	สามารถ กดปุ่ม Play Audio เพื่อฟังเสียง และกด Stop Audio เพื่อหยุดเสียง

4.	สามารถ Save file ได้โดยการกดปุ่ม Export sound as wav file เพื่อ save file


# การทำงานของโปรแกรม
	โปรแกรม MATLAB ที่เขียนเป็นโปรแกรม Graphical Interface เพื่อใช้งานโปรแกรมอื่นๆ เพื่อให้ง่ายต่อการใช้งานแทน Command Line Interface
	โดยโปรแกรมที่ถูกเรียกใช้มีชื่อว่า pysstv เป็นโปรแกรมเพื่อแปลงไฟล์ภาพ .PNG ไปเป็นสัญญาณเสียง SSTV ที่เป็นไฟล์ .WAV โดยโปรแกรม pysstv เป็น library หนึ่งของ Python Link [https://pypi.org/project/PySSTV/] ที่ถูกทำให้เป็นไฟล์ exe และสามารถถูกเรียกใช้ผ่าน Command line ได้โดยใช้โปรแกรม py2exe เพื่อแปลงไฟล์เป็น exe
