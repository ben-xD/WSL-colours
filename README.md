# WSL-colours
**When you update the Ubuntu App on Windows, which runs the Windows Subsystem for Linux, the settings get reset almost all the time. You'd lose all the colour settings you creatively came up with! Here's how mine looks.**

**How it looks on Bash.**
![BASH view](https://i.imgur.com/cc1Blke.png)

**How it looks on VIM. (the text editor)**
![VIM view](https://i.imgur.com/g6uBJlZ.png)

**How to set it up.**
Change all the colour slots to these RGB values in properties (Right click the title bar > Properties) to:  
Each colour slot corresponds to a certain type of text in Bash. For example, slot 11 are files with executable permission by user.  
**Slot 1:** 50 50 55  
**Slot 2:** 255 255 0  
**Slot 3:** 66 210 255  
**Slot 4:** 6 152 154  
**Slot 5:** 244 158 200  
**Slot 6:** 0 255 204  
**Slot 7:** 255 255 255  
**Slot 8:** 211 215 207  
**Slot 9:** 85 87 83  
**Slot 10:** 255 255 0  
**Slot 11:** 102 255 153  
**Slot 12:** 100 255 100 
**Slot 13:** 239 41 41  
**Slot 14:** 220 127 168  
**Slot 15:** 255 102 255  
**Slot 16:** 0 210 255  

**That should end up looking like this:**
![Properties window](https://i.imgur.com/2TDGZo9.png)

**Then set:**  
Screen Text to Slot 16.  
Screen Background to Slot 1.  
Popup Text to Slot 1.  
Popup Background to Slot 16.  

I'm also using the Ubuntu font. 
https://design.ubuntu.com/font/
Download, install and go into Properties > Font to change it.
