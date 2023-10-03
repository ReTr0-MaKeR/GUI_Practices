import tkinter as tk
#from tkinter import ttk
import ttkbootstrap as ttk


def convert():
    mile_input = entry_int.get()
    km_output = mile_input * 1.61
    answer = str(km_output)
    output = answer + " km"
    output_string.set(output)

#Window
Window = ttk.Window()
Window.geometry('500x200')

#title
title_label = ttk.Label(master = Window, text='Miles to Km Convert', font='calibri 20 bold')
title_label.pack()

#Input Frame
input_frame = ttk.Frame(master = Window)
entry_int = tk.IntVar()
entry = ttk.Entry(master = input_frame, textvariable = entry_int)
button = ttk.Button(master = input_frame, text = 'Convert', command = convert)
entry.pack(side = 'left', padx = 10)
button.pack(side = 'left')
input_frame.pack(pady = 10)

#Output Frame
output_string = tk.StringVar()

output_label = ttk.Label(master = Window, text = 'Output', font = 'calibri 24', textvariable = output_string)
output_label.pack(pady = 5)
#root
Window.mainloop()
