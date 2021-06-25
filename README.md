# Calculator
# My FIRST calculator in python 
# [instagream id](https://www.instagram.com/therealhardikpatel/)
#use to tkinter
'''
    from tkinter import *

me=Tk()
me.geometry("354460")
me.title("CALCULATOR")
melabel = Label(me,text="CALCULATOR",bg="white",font=("Times",30,'bold'))
melabel.pack(side=TOP)
me.config(background="Dark gray")

texin=StringVar()
operator=""

def clickbut(number):
    global operator
    operator=operator+str(number)

def equlbut():
    global operator
    add=str(eval(operator))
    texin.set(add)
    operator=''
def equlbut():
    global operator
    sub=str(eval(operator))
    texin.set(sub)
    operator=''

def equlbut():
    global operator
    mul=str(eval(operator))
    texin.set(mul)
    operator=''

def equlbut():
    global operator
    div=str(eval(operator))
    texin.set(div)
    operator=''


def clebut():
    texin.set('')


metext=Entry(me,font=("Courier New",12,'bold'),textvar=texin,width=25,bd=5,bg=('powder blue'))
metext.pack()

but1=Button(me,padx=14,pady=14,bd=4,hg='white',command=lambda:clickbut(1),text="1",font=("Courier New",16,'bold'))
but1.place(x=10,y=100)

but2=Button(me,padx=14,pady=14,bd=4,hg='white',command=lambda:clickbut(2),text="2",font=("Courier New",16,'bold'))
but2.place(x=10,y=170)

but3=Button(me,padx=14,pady=14,bd=4,hg='white',command=lambda:clickbut(3),text="3",font=("Courier New",16,'bold'))
but3.place(x=10,y=240)

but4=Button(me,padx=14,pady=14,bd=4,hg='white',command=lambda:clickbut(4),text="4",font=("Courier New",16,'bold'))
but4.place(x=75,y=100)

but5=Button(me,padx=14,pady=14,bd=4,hg='white',command=lambda :clickbut(5),text="5",font=("Courier New",16,'bold'))
but5.place(x=75,y=170)

but6=Button(me,padx=14,pady=14,bd=4,hg='white',command=lambda:clickbut(6),text="6",font=("Courier New",16,'bold'))
but6.place(x=75,y=240)

but7=Button(me,padx=14,pady=14,bd=4,hg='white',command=lambda:clickbut(7),text="7",font=("Courier New",16,'bold'))
but7.place(x=140,y=100)

but8=Button(me,padx=14,pady=14,bd=4,hg='white',command=lambda:clickbut(8),text="8",font=("Courier New",16,'bold'))
but8.place(x=140,y=170)

but9=Button(me,padx=14,pady=14,bd=4,hg='white',command=lambda:clickbut(9),text="9",font=("Courier New",16,'bold'))
but9.place(x=140,y=240)

but0=Button(me,padx=14,pady=14,bd=4,hg='white',command=lambda:clickbut(0),text="0",font=("Courier New",16,'bold'))
but0.place(x=140,y=240)

butdot=Button(me,padx=47,pady=14,bd=4,bg='white',command=lambda:clickbut("."),text=".",font=("Courier New",16,'bold'))
butdot.place(x=140,y=240)

butPl=Button(me,padx=14,pady=14,bg='white',text="+",command=lambda:clickbut("+"),font=("Courier New",16,'bold'))
butPl.place(x=205,y=100)

butSub=Button(me,padx=14,pady=14,bg='white',text="-",command=lambda :clickbut("-"),font=("Courier New",16,'bold'))
butSub.place(x=205,y=170)

butMl=Button(me,padx=14,pady=14,bg='white',text="*",command=lambda :clickbut("*"),font=("Courier New",16,'bold'))
butMl.place(x=205,y=240)

butDiv=Button(me,padx=14,pady=14,bg='white',text="/",command=lambda:clickbut("/"),font=("Courier New",16,'bold'))
butDiv.place(x=240,y=100)


butClear=Button(me,padx=14,pady=119,bd=4,bg='white',text="CE",command=clebut,font=("Courier New",16,'bold'))
butClear.place(x=270,y=100)

butequal=Button(me,padx=14,pady=119,bd=4,bg='white',text="=",command=clebut,font=("Courier New",16,'bold'))
butequal.place(x=10,y=300)
me.mainloop()

'''
