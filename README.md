# projeto-teste-git


'''
senha = input("Diga sua senha :")
usuario = input("Difa seu usuario :")
while senha == usuario:
    print("A sua senha não não pode ser igual o usuario !")
    senha = input("Duga sua senha :")
    usuario = input("Diga seu usuario : ")
'''
'''
num = input("Qual numero voce deseja saber a tabuada ? ")
while not num.isnumeric():
    num = input("Qual numero voce deseja saber a tabuada ? ")
num = int(num)
i = 1
while i <= 10:
    print(f"{num} x {i} = {num*i}")
    i+=1
'''
'''
i = 1
num = 1
while i <=10:
    print(f"{num} x {i} = {num*i}")
    i+=1
    num+=1
'''
'''
num = 1
while num <= 10:
    print(f"A tabuada do {num} é  :")
    i=1
    while i<=10:
        print(f"{num} * {i} = {num*i}")
        i+=1

    if num == 10:
        break
    num += 1
'''
'''
a = 1
b = 1
i = 0
n = int(input("Diga o numero para elaborarmos a sequencia  ???"))
print(a)
print(b)
while i < n:
    c = a+b
    a = b
    b = c
    print(c)
    print(c/a)
    i+=1 
'''
'''
fat = 1
i = 1
n = int(input("Diga um numero positivo, que não seja 0 para calcularmos o fatorial dele  : "))
print(f"O fatorial de {n} é : ")
operacao = ''
while i<=n:
    fat*=i
    if i<n:
        operacao+=str(n-i+1)+' x '
    else:
       operacao+=str(n-i+1)
    i+=1
print(f"{operacao} = {fat}")
'''
num = 7
i = 2
while i < num:
    if num % i:
        print(f"{num} não é primo")
        break


    elif i ==-1:
        print(f"{num} é primo ")
    i+=1



matriz = [[1,2,3],[4,5,6,],[7,8,9]]
for i in range(len(matriz)):
    print(matriz)

matriz = [[1,2,3],[4,5,6,],[7,8,9]]
def printa_matriz(matriz):
    for linha in matriz:
        print(linha)
    return
for i in range(len(matriz)):
    for j in range(len(matriz[i])):
        if j>=i:
          matriz[i][j] = 1
        else:
            matriz[i][j] = 0
printa_matriz(matriz)
'''
''' i representa linhas - j representa colunas'''

import matplotlib.pyplot as plt
def nova_matriz(linha , coluna):
    matriz = []
    for i in range(linha):
        lista = []
        for j in range(coluna):
            lista.append(i*j)
        matriz.append(lista)
    return matriz
def printa_matriz(matriz):
    for linha in matriz:
        print(linha)
    return
matriz = nova_matriz(8,8)
for i in range(len(matriz)):
    for j in range(len(matriz[i])):
        if (j+i) % 2 == 0:
            matriz[i][j] = 1
        else:
            matriz[i][j] = 0
printa_matriz(matriz)
plt.imshow(matriz, cmap= 'grey')
plt.colorbar()
plt.show()


