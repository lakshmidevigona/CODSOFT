from tkinter import *
expression = ""
def press(num):
	global expression
	expression = expression + str(num)
	equation.set(expression)
def equalpress():
    global expression
    total = str(eval(expression))
    equation.set(total)
    expression=""
def clear():
	global expression
	expression = ""
	equation.set("")
if __name__ == "__main__":
	root= Tk()
	root.configure(background="#eee8dd")
	root.title("Simple Calculator")
	root.geometry("400x300+500+200")
	root.resizable(False,False)
	equation = StringVar()
	expression_field = Entry(root, textvariable=equation,font=("arial",13,"bold"))
	expression_field.grid(columnspan=4,ipadx=100,ipady=10)
	button1 = Button(root, text=' 1 ', fg='#fff', bg='#2a2d36',
					command=lambda: press(1), height=1, width=7,font=("arial",10,"bold"))
	button1.grid(row=2,column=0,pady=5)

	button2 = Button(root, text=' 2 ',  fg='#fff', bg='#2a2d36',
					command=lambda: press(2), height=1, width=7,font=("arial",10,"bold"))
	button2.grid(row=2, column=1,pady=5)

	button3 = Button(root, text=' 3 ',  fg='#fff', bg='#2a2d36',
					command=lambda: press(3), height=1, width=7,font=("arial",10,"bold"))
	button3.grid(row=2, column=2,pady=5)

	button4 = Button(root, text=' 4 ',  fg='#fff', bg='#2a2d36',
					command=lambda: press(4), height=1, width=7,font=("arial",10,"bold"))
	button4.grid(row=3, column=0,pady=5)

	button5 = Button(root, text=' 5 ',  fg='#fff', bg='#2a2d36',
					command=lambda: press(5), height=1, width=7,font=("arial",10,"bold"))
	button5.grid(row=3, column=1,pady=5)

	button6 = Button(root, text=' 6 ',  fg='#fff', bg='#2a2d36',
					command=lambda: press(6), height=1, width=7,font=("arial",10,"bold"))
	button6.grid(row=3, column=2,pady=5)

	button7 = Button(root, text=' 7 ',  fg='#fff', bg='#2a2d36',
					command=lambda: press(7), height=1, width=7,font=("arial",10,"bold"))
	button7.grid(row=4, column=0,pady=5)

	button8 = Button(root, text=' 8 ',  fg='#fff', bg='#2a2d36',
					command=lambda: press(8), height=1, width=7,font=("arial",10,"bold"))
	button8.grid(row=4, column=1,pady=5)

	button9 = Button(root, text=' 9 ',  fg='#fff', bg='#2a2d36',
					command=lambda: press(9), height=1, width=7,font=("arial",10,"bold"))
	button9.grid(row=4, column=2,pady=5)

	button0 = Button(root, text=' 0 ',  fg='#fff', bg='#2a2d36',
					command=lambda: press(0), height=1, width=7,font=("arial",10,"bold"))
	button0.grid(row=5, column=0,pady=5)

	plus = Button(root, text=' + ',  fg='#fff', bg='#2a2d36',
				command=lambda: press("+"), height=1, width=7,font=("arial",10,"bold"))
	plus.grid(row=2, column=3,pady=5)

	minus = Button(root, text=' -- ',  fg='#fff', bg='#2a2d36',
				command=lambda: press("-"), height=1, width=7,font=("arial",10,"bold"))
	minus.grid(row=3, column=3,pady=5)

	multiply = Button(root, text=' x ',  fg='#fff', bg='#2a2d36',
					command=lambda: press("*"), height=1, width=7,font=("arial",10,"bold"))
	multiply.grid(row=4, column=3,pady=5)

	divide = Button(root, text=' / ',  fg='#fff', bg='#2a2d36',
					command=lambda: press("/"), height=1, width=7,font=("arial",10,"bold"))
	divide.grid(row=5, column=3,pady=5)

	equal = Button(root, text=' = ', fg='#fff', bg='#2a2d36',
				command=equalpress, height=1, width=7,font=("arial",10,"bold"))
	equal.grid(row=5, column=2,pady=5)

	clear = Button(root, text='Clear',  fg='#fff', bg='#2a2d36',
				command=clear, height=1, width=7,font=("arial",10,"bold"))
	clear.grid(row=5, column='1',pady=5)

	Decimal= Button(root, text='.',  fg='#fff', bg='#2a2d36',
					command=lambda: press('.'), height=1, width=7,font=("arial",10,"bold"))
	Decimal.grid(row=6, column=0,pady=5)
	root.mainloop()
