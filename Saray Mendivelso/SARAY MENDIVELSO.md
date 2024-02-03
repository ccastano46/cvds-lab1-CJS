# ⚝ BIENVENIDOS A MI MUNDO * 

Hola! 
Yo soy _Saray Alieth Mendivelso Gonzalez_ y les hablare un poco mas de mí

##### INFORMACION GENERAL

    EDAD: 18 años.
    FECHA DE NACIMIENTO: 19 de Abril de 2005.
    LUGAR DE NACIMIENTO: Tunja, Boyaca.
    CARRERA: Ingenieria de sistemas.
    UNIVERSIDAD: Escuela Colombiana De Ingenieria Julio Garavito.
    NIVEL DE INGLES: B1.
    
**HOBBIES**
- Me gusta bastante patinar
- Diseñar
- Ver series
- La fotografia
- Leer acerca de la tecnología



**Link de mi perfil de instagram**
-  [SARAY MENDIVELSO](https://www.instagram.com/gonsaray/)

![](https://scontent-ord5-1.xx.fbcdn.net/v/t1.15752-9/418996973_1289781508366284_3236229763754993440_n.jpg?_nc_cat=108&ccb=1-7&_nc_sid=510075&_nc_ohc=fvcIy7Xfkm8AX-gKNGD&_nc_ad=z-m&_nc_cid=0&_nc_ht=scontent-ord5-1.xx&oh=03_AdQ-yOfOXPI6zlU_Qyb0Qzn8o4HCCuAsgYpXvcQm4LoKig&oe=65E51A87)

_Dado que soy ingeniera de sistemas les quiero compartir un código basico hecho en python que te pinta una flor_

```
from turtle import*
import colorsys


speed (0)
bgcolor("black")
h=0

for i in range (16):
    for j in range (18):
        c=colorsys.hsv_to_rgb(h,0.9,1)
        color(c)
        h+=0.005
        rt(90)
        circle(150-j*6,90)
        lt(90)
        circle(150-j*6,90)
        rt(180)
    circle(40,24)

done()
```

