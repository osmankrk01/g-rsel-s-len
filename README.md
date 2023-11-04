# g-rsel-s-len
import turtle

def polygon(t, ku, ks):
    aci = 360 / ks

    for _ in range(ks):
        t.forward(ku)
        t.left(aci)


ekran = turtle.Screen()


poligon_turtle = turtle.Turtle()


polygon(poligon_turtle, 100, 8)


ekran.mainloop()
