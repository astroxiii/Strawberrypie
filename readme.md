# strawberrypie

## Usage :


> Install :
```

pip install Strawberrypie

```


> example 
```
from tkinter import *
from strawberrypie import Pie ,Center_root,Btn ,Tfield,color_ch

root = Tk()

pie = Pie(root, root ,bg = "#000")

#if set to false it will show mini/max btns
sat =pie.statbar(True)

#center the window
Center_root(root)

btn1 = Btn(text = "Button 01 ")
btn1.place(relx =0.1 , rely =0.1 )
btn2 = Btn(text = "Button 02 ")
btn2.place(relx =0.1 , rely =0.3 )
ent1 = Tfield()
ent1.place(relx =0.1 , rely =0.5 , relheight= 0.06 )
#change hover/click colors 
colors = {"enter":"lightgray" , "leave" :"#fff" , "actbg" : "red" ,"actfg" :"#000"}
color_ch(colors , btn2)

root.mainloop()
```
