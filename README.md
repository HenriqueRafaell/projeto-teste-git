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


