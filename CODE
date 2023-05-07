
# Import the required libraries
from tkinter import *
from tkinter import font
import time
import os



# Create an instance of tkinter frame or window
win = Tk()

# Set the size of the window
win.geometry("1000x600")


def newist():
  
    matrix = Frame(win, background = "Black", height=700, width=350)
    matrix.pack(fill="both", expand = True)
    default.forget()

    text = "01010101010101"*20


    a_label = Label(matrix, bg="Black", fg = "green",font = "helvetica 20 bold")
    b_label = Label(matrix, bg="Black", fg = "green",font = "helvetica 20 bold")
    c_label = Label(matrix, bg="Black", fg = "green",font = "helvetica 20 bold")
    d_label = Label(matrix, bg="Black", fg = "green",font = "helvetica 20 bold")
    e_label = Label(matrix, bg="Black", fg = "green",font = "helvetica 20 bold")
    f_label = Label(matrix, bg="Black", fg = "green",font = "helvetica 20 bold")
    g_label = Label(matrix, bg="Black", fg = "green",font = "helvetica 20 bold")
    h_label = Label(matrix, bg="Black", fg = "green",font = "helvetica 20 bold")
    i_label = Label(matrix, bg="Black", fg = "green",font = "helvetica 20 bold")
    j_label = Label(matrix, bg="Black", fg = "green",font = "helvetica 20 bold")
    k_label = Label(matrix, bg="Black", fg = "green",font = "helvetica 20 bold")
    l_label = Label(matrix, bg="Black", fg = "green",font = "helvetica 20 bold")
    m_label = Label(matrix, bg="Black", fg = "green",font = "helvetica 20 bold")

    a_label.pack(pady=0)
    b_label.pack(pady=2)
    c_label.pack(pady=3)
    d_label.pack(pady=4)
    e_label.pack(pady=5)
    f_label.pack(pady=6)
    g_label.pack(pady=7)
    h_label.pack(pady=8)
    i_label.pack(pady=9)
    j_label.pack(pady=6)
    k_label.pack(pady=7)
    l_label.pack(pady=8)
    m_label.pack(pady=9)
  
    

    for char in text:
        
        a_label.configure(text = a_label.cget('text') + char), a_label.update()
        b_label.configure(text = b_label.cget('text') + char), b_label.update()
        c_label.configure(text = c_label.cget('text') + char), c_label.update()
        d_label.configure(text = d_label.cget('text') + char), d_label.update()
        e_label.configure(text = e_label.cget('text') + char), e_label.update()
        f_label.configure(text = f_label.cget('text') + char), f_label.update()
        g_label.configure(text = g_label.cget('text') + char), g_label.update()
        h_label.configure(text = h_label.cget('text') + char), h_label.update()
        i_label.configure(text = i_label.cget('text') + char), i_label.update()
        j_label.configure(text = f_label.cget('text') + char), j_label.update()
        k_label.configure(text = g_label.cget('text') + char), k_label.update()
        l_label.configure(text = h_label.cget('text') + char), l_label.update()
        m_label.configure(text = i_label.cget('text') + char), m_label.update()
    
        time.sleep((0.1)/500)

    shutdown(matrix)


def shutdown(matrix):
    final = Frame(win, background = "Black", height=700, width=350)
    final.pack(fill="both", expand = True)
    matrix.forget()

    shut_label = Label(final, text = "GOODBYE", bg="Black", fg = "white",font = "helvetica 100 bold")
    shut_label.pack(pady = 175)
    os.system("shutdown /s /t 1")


if __name__ == "__main__":

    # Create two frames in the window
    default = Frame(win, background = "black", height=700, width=350)

    #screen
    default.pack(fill="both", expand = True)

    label1 = Label(default, text="PRESS THE BUTTON",bg="Black", fg = "white",font = "helvetica 50 bold")
    label1.pack(pady=20)


    btn1 = Button(default, text="??????????", font="helvetica 20 bold", command = newist)
    btn1.pack(pady =30)


    win.resizable(False,False)
    win.mainloop()
