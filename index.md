## **Welcome to my SOC Project repo**
Welcome to my repository to display my SOC (System on chip) project. This project will expand on a template given for a simple colour stripe VGA output and will be altered to create flags.
The flag I have chosen to use is the Norway national flag.

## **Template VGA Design**

### **Project Set-Up**
Summarise the project set-up and design flow. Include a screenshot of your own set-up, for example see the image of my Project Summary window below. Guideline 1 short paragraph.

<img width="1061" height="650" alt="image" src="https://github.com/user-attachments/assets/6022b240-aceb-40a5-8717-9e464e269f2e" />

### **Template Code**
Outline the structure and design of the Verilog code templates you were given. What do they do? Include reference to how a VGA interface works. Guideline: 2/3 short paragraphs, consider including screenshot(s).
### **Simulation**
Explain the simulation process. Reference any important details, include a well-selected screenshot of the simulation. Guideline: 1/2 short paragraphs.
### **Synthesis**
Describe the synthesis and implementation processes. Consider including 1/2 useful screenshot(s). Guideline: 1/2 short paragraphs.
### **Demonstration**
Perhaps add a picture of your demo. Guideline: 1/2 sentences.

## **My VGA Design Idea**
### **Project output on screen**
<img width="1920" height="1920" alt="image" src="https://github.com/user-attachments/assets/7fc633bd-4145-4607-a05e-531bcde6151d" />

Introduce your own design idea. Consider how complex/achievable this might be or otherwise. Reference any research you do online (use hyperlinks).

What my VGA design is going to be is the Norway national flag. The reason I chose this is because national flags seemed to be a popular choice among previous/current students.
I feel as this is an achievable goal that will display knowledge into how the VGA works under the hood consisting of colour representation, screen layout knowledge and loop syntax needed to display this flag on the screen.
### **Code Adaptation**
**Briefly show how you changed the template code to display a different image. Demonstrate your understanding. Guideline: 1-2 short paragraphs.**

## **Progress timeline**

**Week1** - In week one the agenda was to get the demo working on my screen which was colour stripes. We ran through the steps involved to see the template code stripe output on the screen. I did not record an image of this but I found a similar photo from the internet of what this looked like.
<img width="889" height="580" alt="image" src="https://github.com/user-attachments/assets/604062e0-e540-4fbc-968e-2eb736e2093b" />

**Week2** - I altered the stripe template from a vertical RGB style to display a horizontal blue and white stripe style. This was achieved by altering the original code to check the rows instead of the columns. Within this code I re-wrote 0 or 1s to align with the colours I wanted to display. For example all ones written to red blue and green would create the white colour and all ones written to blue and zeros written to red and green would create only the blue colour.

**Week3** - Absent

**Week4** - In week three I decided to create and finish the display of the Norway flag. How this was done was by coding the display to create the primary colour red for the entire screen and then add white and blue horizontal and vertical lines.

**Week5** - Final review of Github page, code explanation and adding of screenshots. No new features will be added in this session it will solely be used to fill in the report.

### **Code explanation**
<img width="566" height="543" alt="image" src="https://github.com/user-attachments/assets/bea9cf93-882d-4ec0-b0fb-78af3ae507f5" />
<img width="400" height="543" alt="image" src="https://github.com/user-attachments/assets/07ea8675-240c-4710-bacf-d3c673ceadd1" />

### **Simulation**
Show how you simulated your own design. Are there any things to note? Demonstrate your understanding. Add a screenshot. Guideline: 1-2 short paragraphs.

<img width="1042" height="595" alt="image" src="https://github.com/user-attachments/assets/0514dda3-2eba-4623-a37c-33add3989c7f" />

### **RTL Analysis**

**Elaborated Design - Schematic**
<img width="1218" height="597" alt="image" src="https://github.com/user-attachments/assets/a8d6d3fd-af61-4c76-87df-27e465197e04" />

###**Synthesis**
Describe the synthesis & implementation outputs for your design, are there any differences to that of the original design? Guideline 1-2 short paragraphs.
<img width="337" height="492" alt="image" src="https://github.com/user-attachments/assets/271cb133-a10f-46f7-ba63-17e6f5424a03" />

**Implementation**
Describe the synthesis & implementation outputs for your design, are there any differences to that of the original design? Guideline 1-2 short paragraphs.
<img width="859" height="382" alt="image" src="https://github.com/user-attachments/assets/9d17753e-8242-411c-af2d-f348e29b9822" />

**Schematic**
<img width="942" height="515" alt="image" src="https://github.com/user-attachments/assets/f9cbf99c-065d-4cc1-afd1-ee25a0de1721" />

### **Demonstration**
If you get your own design working on the Basys3 board, take a picture! Guideline: 1-2 sentences.

## **More Markdown Basics**
This is a paragraph. Add an empty line to start a new paragraph.

Font can be *Italic* or **Bold**.

Highlighting code using `backticks`.

Hyperlinks -> : [GitHub Help](https://help.github.com/).

A bullet list can be rendered as follows:
- vectors

Images can be added by uploading them to the repository in a /docs/assets/images folder, and then rendering using HTML via githubusercontent.com as shown in the example below.

<img src="https://raw.githubusercontent.com/melgineer/fpga-vga-verilog/main/docs/assets/images/VGAPrjSrcs.png">
