# How to create dialog using Python3 on a macOS system.

 
 


 

 
 <br/>
 
Project Summary
-------

* The purpose of this project is to demostrate the process of talking between two or more voices and/or phrases using the 'say' command with Python3 code.
  
  * This project is designed for creative writers/coders to experiment with different conversations, stories, text, and/or code.

  * Project files can be downloaded from.<br/>
  [https://github.com/Git-Grobe/How-to-create-dialog-using-Python3-on-a-macOS-system.](https://github.com/Git-Grobe/How-to-create-dialog-using-Python3-on-a-macOS-system.)
  
  * A project demonstration video can be found on YouTube.<br/>
  [https://youtu.be/m5qfFgB5N0c](https://youtu.be/m5qfFgB5N0c)
  

<br/>
<br/>

Prerequisites
---------------
*Compatible on all macOS systems using the 'say' command with Python3 installed*

<br/>
<br/>

Author & Contributor List
------------


*Scott M. Grobe*


Report bugs/fixes to gitgrobe@gmail.com

<br/>
<br/>



File List
---------

```
README.md

helloworld.py

```

<br/>
<br/>
<br/>
<br/>


   
---
---

How to run file
------------

Once you have cloned the directory to your local machine, follow the directions below:

 1. open `How-to-create-dialog-using-Python3-on-a-macOS-system.` master folder
 
 2. copy `helloworld.py` onto your computer's desktop
 
 3. open `Terminal`
 
 4. type `cd desktop`  then hit the enter key
 
 5. type `Python3 helloworld.py`  then hit the enter key


---
---


<br/>
<br/>
<br/>
<br/>


### Coding thought-process explained
----------

1. `import os`

   *This allows the ability to interface with programs on the operating system (macOS in this example)* 

---

2. `os.system("clear")`

   *This will start the sequence on a blank screen for a clean look & to eliminate any distractions*
  
---
  
3. `os.system("say -v samantha -r 150 --interactive=red Hello Stephen. Hello World!" )`

   *This converts text `Hello Stephen. Hello World!` to audible speech and visual text using the 'say' comand. Modifiers listed below are being used*

   *`-v` is used to change the voice*
    
    
   *`-r` is used for the rate of speech, in words per minute*
    
    
   *`--interactive=red` The system will print the text line by line during speech synthesis, highlighting words exactly as they are spoken. In this case its using the color red.*
   
   * (for more information on 'say' command modifiers, type `info say` into the terminal window)
   
   ---
   
    
 4. `os.system("say -v fred -r 150  --interactive=red Hello Siri. Hello World!!" )`
 
 
    *This repeating function allows the 'say' command to keep running between different voices and phrases without interuption.*
    
    
    *The voices of Samantha and Fred are used in this example. They address each other as Siri and Stephen Hawkins. This is done in tribute because both have had an enormous impact and influence on modern technology, specifically computerized speech synthesis!*
    
---
