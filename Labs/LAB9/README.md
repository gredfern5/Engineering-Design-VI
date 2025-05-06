# Lab 9 | YANG
## George Redfern
### Lab Instructions:
 - Go to the GitHub repository Lesson 9
 - Install pyang and PlantUML
 - copy ~/iot/lesson9/intrusiondetection.yang to ~/demo
 - Run pyang to generate intrusiondetection.yin and intrusiondetection.uml
 - Run PlantUML to generate intrusiondetection.png

## Part 1: Installing pyang and PlantUML

I executed the following commands in my Windows PowerShell:
```
cd ~/iot/lesson9
pip install -U lxml pyang
pip install -U plantuml
```
## Part 2: Copying and generating PYang

After the installations, I executed the following commands in my Windows PowerShell:

```
cp ~/iot/lesson9/intrusiondetection.yang ~/demo
cd ~/demo
```

![image](https://github.com/user-attachments/assets/c11c729a-4403-4914-9c16-6f7897aeb526)

I then ran the following commands to generate the intrusiondetection.yin and intrusiondetection.uml files, displaying the intrusiondetection data in .yang, .yin, and .uml formats.

```
cat intrusiondetection.yang
pyang -f yin -o intrusiondetection.yin intrusiondetection.yang
cat intrusiondetection.yin
pyang -f uml -o intrusiondetection.uml intrusiondetection.yang --uml-no=stereotypes,annotation,typedef
cat intrusiondetection.uml
```

Pictured below are the contents of the intrusiondetection file in each format.
</br>

### .yang:
![image](https://github.com/user-attachments/assets/365b2d67-a8a1-4cce-886e-9df13f468d81)
</br>

### .yin:
![image](https://github.com/user-attachments/assets/ea3dec37-67ee-4d8f-aa96-dc68ca455288)
</br>

### .uml: 
![image](https://github.com/user-attachments/assets/91d26bb9-5f58-4cf1-b590-826d567348c2)
</br>

## Part 3: Creating IMG
I used the command python -m plantuml intrusiondetection.uml to generate a PNG sequence diagram. Afterward, I installed and launched GIMP and Pinta to view the image. The following commands were used to accomplish this:

```
pip install six
python -m plantuml intrusiondetection.uml
start intrusiondetection.png
```
![intrusiondetection](https://github.com/user-attachments/assets/4c1c59e4-0108-49da-8cae-d60c44533062)

## Summary
In this lab, I examined the structure and representation of a YANG model by converting it into .yin, .uml, and .png formats. The pyang tool proved useful for translating the original .yang file into both YIN and UML formats, while PlantUML effectively generated a visual diagram from the UML file. This process helped me better understand how network models can be visualized and transformed using standard tools.

I pledge my honor that I have abided by the Stevens Honor System- George Redfern
