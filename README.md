# fonction-affine

#entrée : x un nombre réel représentant l'antécédent , a un nombre entier représentant le coef, p un nombre entier représentant la constante
def entrées():
  a=int(input())
  p=int(input())
  return a,p

#cette fonction calcule une fonction affine de 0 à 1
def maeva(a,p):
    y=(a)*x+(p)
    return y

#sortie : y un nombre réel image de x
def sorties (y):
    print(y)


a,p=entrées ()
for x in range (0,10):
  y=maeva (a,p)
  sorties (y)
