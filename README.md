from tkinter import *
aken=Tk()
aken.title("Tunniplaan")
aken.geometry("800x500")
Ep=Label(aken,text="Esmaspäev",relief="solid",font="Arial 10").grid(row=2,column=0,rowspan=2,sticky=N+S+W+E)
Tp=Label(aken,text="Teisipäev",relief="solid",font="Arial 10").grid(row=4,column=0,rowspan=2,sticky=N+S+W+E)
Kp=Label(aken,text="Kolmapäev",relief="solid",font="Arial 10").grid(row=6,column=0,rowspan=2,sticky=N+S+W+E)
Np=Label(aken,text="Neljapäev",relief="groove",font="Arial 10").grid(row=8,column=0,rowspan=2,sticky=N+S+W+E)
Rp=Label(aken,text="Reede",relief="groove",font="Arial 10").grid(row=10,column=0,rowspan=2,sticky=N+S+W+E)

t0=Label(aken,text="0",relief="groove",font="Arial 20").grid(row=1,column=1,sticky=N+S+W+E)
t1=Label(aken,text="1",relief="groove",font="Arial 20").grid(row=1,column=2,sticky=N+S+W+E)
t2=Label(aken,text="2",relief="groove",font="Arial 20").grid(row=1,column=3,sticky=N+S+W+E)
t3=Label(aken,text="3",relief="groove",font="Arial 20").grid(row=1,column=4,sticky=N+S+W+E)
t4=Label(aken,text="4",relief="groove",font="Arial 20").grid(row=1,column=5,sticky=N+S+W+E)
t5=Label(aken,text="5",relief="groove",font="Arial 20").grid(row=1,column=6,sticky=N+S+W+E)
t6=Label(aken,text="6",relief="groove",font="Arial 20").grid(row=1,column=7,sticky=N+S+W+E)
t7=Label(aken,text="7",relief="groove",font="Arial 20").grid(row=1,column=8,sticky=N+S+W+E)
t8=Label(aken,text="8",relief="groove",font="Arial 20").grid(row=1,column=9,sticky=N+S+W+E)
t9=Label(aken,text="9",relief="groove",font="Arial 20").grid(row=1,column=10,sticky=N+S+W+E)
t10=Label(aken,text="10",relief="groove",font="Arial 20").grid(row=1,column=11,sticky=N+S+W+E)

k1=Button(aken,text="Multimeedia",relief="groove",font="Arial 20",bg="#424983").grid(row=2,column=2,columnspan=2,sticky=N+S+W+E)
ks=Button(aken,text="   ",relief="groove",font="Arial 20").grid(row=3,column=4,sticky=N+S+W+E)
k2=Button(aken,text="Programeerimise alused",relief="groove",font="Arial 20",bg="#1ebbd7").grid(row=2,column=5,columnspan=3,sticky=N+S+W+E)
k0=Button(aken,text="Rühmajuhataja tund",relief="groove",font="Arial 20",bg="#1ebbd7").grid(row=2,column=8,rowspan=2,sticky=N+S+W+E)
k3=Button(aken,text="Programeerimise alused",relief="groove",font="Arial 20",bg="#1ebbd7").grid(row=3,column=2,columnspan=3,sticky=N+S+W+E)
k4=Button(aken,text="Multimeedia",relief="groove",font="Arial 20",bg="#424983").grid(row=3,column=5,columnspan=2,sticky=N+S+W+E)

h1=Button(aken,text="Inglise Keel",relief="groove",font="Arial 20",bg="#424983").grid(row=4,column=2,columnspan=2,sticky=N+S+W+E)
h2=Button(aken,text="Inglise Keel",relief="groove",font="Arial 20",bg="#424983").grid(row=5,column=2,columnspan=2,sticky=N+S+W+E)
h3=Button(aken,text="Operatsioonisüsteemide alused",relief="groove",font="Arial 20",bg="#f603a3").grid(row=4,column=4,rowspan=2,columnspan=2,sticky=N+S+W+E)
h4=Button(aken,text="    ",relief="groove",font="Arial 20").grid(row=4,column=6,rowspan=2,sticky=N+S+W+E)
h5=Button(aken,text="Kehaline kasvatus",relief="groove",font="Arial 20",bg="#f603a3").grid(row=4,column=7,rowspan=2,columnspan=2,sticky=N+S+W+E)
h6=Button(aken,text="Eesti keel",relief="groove",font="Arial 20",bg="#8e7cc3").grid(row=4,column=9,rowspan=1,columnspan=1,sticky=N+S+W+E)
h7=Button(aken,text="Eesti keel",relief="groove",font="Arial 20",bg="#3e3530").grid(row=5,column=9,rowspan=1,columnspan=1,sticky=N+S+W+E)
h8=Button(aken,text="Geograafia",relief="groove",font="Arial 20",bg="#f8ac6a").grid(row=4,column=10,rowspan=2,sticky=N+S+W+E)

y1=Button(aken,text="Programeerimise alused",relief="groove",font="Arial 20",bg="#1ebbd7").grid(row=6,column=2,columnspan=3,sticky=N+S+W+E)
y2=Button(aken,text="Multimeedia",relief="groove",font="Arial 20",bg="#424983").grid(row=7,column=2,columnspan=3,sticky=N+S+W+E)
y3=Button(aken,text="    ",relief="groove",font="Arial 20").grid(row=6,column=5,rowspan=2,sticky=N+S+W+E)
y4=Button(aken,text="Multimeedia",relief="groove",font="Arial 20",bg="#424983").grid(row=6,column=6,columnspan=3,sticky=N+S+W+E)
y5=Button(aken,text="Programeerimise alused",relief="groove",font="Arial 20",bg="#1ebbd7").grid(row=7,column=6,columnspan=3,sticky=N+S+W+E)
y6=Button(aken,text="Multimeedia",relief="groove",font="Arial 20",bg="#424983").grid(row=6,column=6,columnspan=3,sticky=N+S+W+E)



aken.mainloop()



