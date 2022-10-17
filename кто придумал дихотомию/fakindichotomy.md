import math
print("a =")
a = float(input())
print("b =")
b = float(input())
print("эпсилум или как его там =")
e = float(input())

#формула, используемая для примера
#0 = 10 * math.cos(x)-0.1*(x**2)
while b - a > e:
  c = (a+b)/2
  #вставь данную тебе формулу в Fc и Fa, только вместо х вставь с и а соответсвенно, как показано на примере 
  Fc = 10 * math.cos(c)-0.1*(c**2)
  Fa = 10 * math.cos(a)-0.1*(a**2)
  print("a =", a,"b =", b)
  print("c=", c, "Fc=", Fc, "Fa=", Fa)
  if Fc * Fa < 0:
    b = c
  else :
    a = c

x = (a+b)/2
Delx = (b-a)/2
print("x=", x,"дельта х = ",Delx)
