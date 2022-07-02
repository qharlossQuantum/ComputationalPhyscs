import matplotlib.pyplot as plt
m=1
g=9.8
l=1
dt=0.05
from numpy import pi #con este procedimiento solo importmos el vaor de pi de la libreria numpy en lugar de importar toda la libreria
q=5*pi/180
w=0
t=0
print("Ingrese el número de puntos a graficar\n")
n=int(input("n="))
E=0.5*m*(l**2)*(w**2+(g/l)*(q**2))
plt.plot(t,q,marker="o")
plt.plot(t,E,marker="x")
for i in range(n):
    w=w-(g/l)*q*dt
    q=q+w*dt
    E=0.5*m*(l**2)*(w**2+(g/l)*(q**2))
    t=t+dt
    plt.plot(t,q,marker="o")
    plt.plot(t,E,marker="x")

plt.grid()
plt.show()
