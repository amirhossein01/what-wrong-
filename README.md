# what-wrong-
# tkinter

## i can share my changes in my terminal but i can`t share my changes in my window i use tkinter library ##
from tkinter import *

counter = 0
def now():
    global counter
    counter+=1
    print(counter)
    
    hello_cnt.config(text="count: ()".format(counter))  

window = Tk()
window.title("Amirhossein_app")

window.resizable(width = False , height = False)

Button(window,text = "Clieck me",bd=10,fg = "black",bg = "red",command = now).pack()
#Label(window,text = "HELLO_WORLD",fg = "red",bg = "black",font = ("Tahoma",20)).pack()

hello_cnt = Label(window,text = "count:",font = ("Tahoma",10))
window.geometry("400x400")
hello_cnt.pack()
window.mainloop()

