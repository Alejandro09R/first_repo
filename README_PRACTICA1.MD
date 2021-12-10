if letra_Adivinar in lista_letras:
      '*' * len(palabra)

print(lista_letras) 
 for x in palabra:  


palabra = input("Introduzca palabra: ")
n_intentos = int(input("Introduzca intentos: "))
new_i = []
num_letras = 0
lista_letras = []
palabra_asteriscos = ""
x=""
while x in palabra:
  num_letras = len(palabra)
  adivina_num_letras = int(input("Adivine numero de letras: "))
  if adivina_num_letras < num_letras:
    print("Intento erróneo. El numero a adivinar es mayor")
  elif adivina_num_letras > num_letras:
    print("Intento erróneo. El numero a adivinar es menor")
  else:
     print("Ha acertado el numero! La palabra tiene ", num_letras, " Letras")
     break
print("Adivine letra introduzca 1:")
print("Adivine palabra introducida 0:")
opciones = int(input())

if opciones == 1:
  letra_Adivinar = input("Adivine letra:")
  for x in palabra:
    lista_letras.append(x)
    lista_letras_asterisco =[]
    palabra_asteriscos = '*' * len(palabra)
  for x in palabra_asteriscos:
    lista_letras_asterisco.append(x)
  for x in range(0, len(lista_letras)):
    if lista_letras[x] == letra_Adivinar:
      for x in range(0, len(lista_letras_asterisco)):
          lista_letras_asterisco[x] == letra_Adivinar
print(lista_letras_asterisco)    