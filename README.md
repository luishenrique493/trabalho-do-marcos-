1-
nomes = ["arthur", "luis", "jeremy", "klaus"]
def mostrar_lista(nomes):
 for item in nomes:
  print(item)
mostrar_lista(nomes)
2-
numeros = [1, 2 ,3 , 4, 5]
def mostrar_maiores(numeros):
    print(max(numeros))   
mostrar_maiores(numeros)
3-
numeros = [1, 2 ,3 , 4, 5]
def segundo_maior(numeros):
    ordenados = (numeros)
    if len(ordenados) > 2:
        segundo_maior=ordenados[-2]
        print(segundo_maior)
       
segundo_maior(numeros)
4-
numeros = [1, 2, 3, 4 ,5 ,6 , 7, 8, 9 ,10]
def encontrar_pares(numeros):
    return[num for num in numeros if num % 2 == 0]
print(encontrar_pares(numeros))
5-
numeros = [1, 2, 3, 4 ,5 ,6 , 7, 8, 9 ,10]
def encontrar_impares(numeros):
    return[num for num in numeros if num % 2 == 1]
print(encontrar_impares(numeros))
6-
lista = [1, 2, 3, 4, 5, 6, 7, 8]
def buscar_numero_loop(lista):
     for elemento in lista:
        if elemento == lista:
            return True
     return False
buscar_numero_loop(lista)
7-

8-
numeros = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
def somar_lista(numeros):
    print(sum(numeros))
somar_lista(numeros)
9-
numeros = [1, 2, 3, 5 ,5 ,5 ,6,6,6,7,7,8,8,9,12,12]
def contando_oco(numeros):
    contador = {}
    for numero in numeros:
        if numero in contador:
            contador[numero] += 1
        else:
            contador[numero] = 1
            print(contador)
contando_oco(numeros)  
10-
numeros = [1,1,2,2,3,3,4,4]
def remover_duplicatas(numeros):
    print(list(set(numeros)))
remover_duplicatas(num
11-
numeros = []
def verficação_vazia(numeros):
    if not numeros:
        print("True")
    else: 
        print("false")
verficação_vazia(numeros)   
12-
lista1 = [1, 2, 3]
lista2 = [4, 5, 6]

lista_junta = lista1 + lista2
print(lista_junta)
13-
numeros = [1, 2,3 ,4 ,5 ,6]
def menor_num(numeros):
    print(min(numeros))
menor_num(numeros)
14-
numeros = [1,2,3,4,5,6]
def media_lista(numeros):
    media = sum(numeros) / len(numeros)
    print(media)
media_lista(numeros)    
15-
lista = [1, 2, 3, 4, 5]
def invert_lista(lista):
      inversa = lista[::-1]
      print(inversa)
invert_lista(lista) 
