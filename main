'''
Estudo sobre Perceptron de 3 entradas
Jonathan Felix \ @Akhenaton
IA - UNIBRA

Considerar P > 0 = 1 e P < 0 = -1
Se atente aos valores binários das entradas [0] / [1]
'''

import time

def i ():
  print('-'* 30)

i()
print('## Definindo os pesos')
w0 = float(input('Defina o peso 1: '))
w2 = float(input('Defina o peso 2: '))
w3 = float(input('Defina o peso 3: '))
time.sleep(1)

i()
print('## Definindo as Entradas\nApenas valores Binários !!!\n')

x = int(input('Defina a entrada 1: '))
y = int(input('Defina a entrada 2: '))
z = int(input('Defina a entrada 3: '))
i()

print('## Definindo o limiar')
limiar = float(input('Valor da Limiar: '))

p = (x * w0) + (y * w2) + (z * w3) - limiar

i()
print(f'Resultado foi: \nEntradas {x,y,z}\nPesos {w0,w2,w3}\nResultado Esperado:{p:.2f}')
if p > 0:
  print(f'Função de Ativação retorna: 1')
else:
  print(f'Função de Ativação retorna: -1')

i()
print('## Fim do Programa')
